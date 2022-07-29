<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Navbar from './components/Navbar.vue'
</script>

<template>
  <div>
    <Navbar />
    <div class="container">
      <RouterView />
    </div>
  </div>
</template>

<script>
export default {
  components: {Navbar}
}
</script>

<style lang="scss">
  @import "../node_modules/materialize-css/dist/css/materialize.min.css";
</style>
