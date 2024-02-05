<template>
  <!-- <NavBar/> -->
  <router-view/>
</template>

<script>
import NavBar from './components/NavbarComp.vue'
  export default {
    components: {
      NavBar
    }
  }
</script>

<style>
#app {
  font-family: 'Kanit', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>
