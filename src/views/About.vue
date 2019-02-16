<template>
  <div class="about">
    <h1>This is an about page</h1>
    <v-icon large lifet class="mdi-twitter"></v-icon>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

@Component
export default class About extends Vue {}
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
}
</style>