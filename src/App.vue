<template>
  <main class="columns is-gapless is-multiline">
    <div class="column is-one-quarter"></div>
    <div class="column is-three-quarter"></div>
  </main>
</template>

<script lang="ts">
import { defineComponent } from 'vue';


export default defineComponent({
  name: 'App',

});
</script>

<style>
header {
  padding: 1rem;
  background: #0d3b66;
  width: 100%;
  height: 100vh;
}

@media only screen and (max-width: 768px) {
  header {
    padding: 2.5rem;
    height: auto;
  }
}
</style>
