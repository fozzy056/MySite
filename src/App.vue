<template>
  <div>
    <NavBar />
    <div id="app">
      <!-- <Footer msg="Est ce que c'est bô ?" /> -->
      <router-view />
    </div>
    <Footer />
  </div>
</template>

<script>
import Footer from "./components/Footer.vue";
import NavBar from "./components/NavBar";

export default {
  name: "App",
  components: {
    Footer,
    NavBar
  }
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
