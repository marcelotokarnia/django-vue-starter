<template>
  <div>
    <Navbar />
    <Main />
  </div>
</template>

<script lang="ts">
  import Vue from 'vue'
  import Main from '@src/components/Main.vue'
  import Navbar from '@src/components/Navbar.vue'
  export default Vue.extend({
    name: 'App',
    components: {
      Main,
      Navbar
    }
  })
</script>

<style>
</style>