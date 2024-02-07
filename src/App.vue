<template>
  <!-- <NavBar/> -->
  <router-view/>
  <!-- <Footer/> -->
</template>

<script>
import NavBar from './components/NavbarComp.vue'
// import Footer from './components/FooterComp.vue'
  export default {
    components: {
      NavBar,
      // Footer
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
