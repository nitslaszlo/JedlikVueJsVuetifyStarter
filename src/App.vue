<template>
  <v-app id="inspire">
    <v-toolbar>
    <v-toolbar-side-icon></v-toolbar-side-icon>
    <v-toolbar-title>Title</v-toolbar-title>
    <v-spacer></v-spacer>
    <v-toolbar-items class="hidden-sm-and-down">
      <v-btn flat>Link One</v-btn>
      <v-btn flat>Link Two</v-btn>
      <v-btn flat>Link Three</v-btn>
    </v-toolbar-items>
  </v-toolbar>
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
  private OnClick(művelet: string): void {
    if (művelet == "+") window.alert("Plussz");
  }
}
</script>

<style scoped>
</style>
