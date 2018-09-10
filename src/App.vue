<template>
  <v-app id="inspire">
    <v-form>
      <v-container>
        <v-layout row wrap>
  
          <v-flex xs12 sm6 md3>
            <v-text-field
              label="Regular"
            ></v-text-field>
          </v-flex>
  
          <v-flex xs12 sm6 md3>
            <v-text-field
              label="Regular"
              placeholder="Placeholder"
            ></v-text-field>
          </v-flex>
  
          <v-flex xs12 sm6 md3>
            <v-text-field
              label="Solo"
              solo
            ></v-text-field>
          </v-flex>
  
          <v-flex xs12 sm6 md3>
            <v-text-field
              label="Solo"
              placeholder="Placeholder"
              solo
            ></v-text-field>
          </v-flex>
  
          <v-flex xs12 sm6 md3>
            <v-text-field
              label="Box"
              box
            ></v-text-field>
          </v-flex>
  
          <v-flex xs12 sm6 md3>
            <v-text-field
              label="Box"
              placeholder="Placeholder"
              box
            ></v-text-field>
          </v-flex>
  
          <v-flex xs12 sm6 md3>
            <v-text-field
              label="Outline"
              outline
            ></v-text-field>
          </v-flex>
  
          <v-flex xs12 sm6 md3>
            <v-text-field
              label="Outline"
              placeholder="Placeholder"
              outline
            ></v-text-field>
          </v-flex>

          <v-flex xs12 sm6 md3>
            <v-btn color="success">Success</v-btn>
            <v-btn color="error">Error</v-btn>
            <v-btn color="warning">Warning</v-btn>
            <v-btn color="info">Info</v-btn>
          </v-flex>

        </v-layout>
      </v-container>
    </v-form>
  </v-app>
</template>

<script  lang="ts">
import { Component, Vue } from "vue-property-decorator";

@Component
export default class App extends Vue {
  items: object = [
    {
      src: "https://cdn.vuetifyjs.com/images/carousel/squirrel.jpg"
    },
    {
      src: "https://cdn.vuetifyjs.com/images/carousel/sky.jpg"
    },
    {
      src: "https://cdn.vuetifyjs.com/images/carousel/bird.jpg"
    },
    {
      src: "https://cdn.vuetifyjs.com/images/carousel/planet.jpg"
    }
  ];
  private OnClick(művelet: string): void {
    if (művelet == "+") window.alert("Plussz");
  }
}
</script>

<style scoped>
</style>
