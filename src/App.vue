<template>
  <div id="app">
    <Navbar />
    <Hompage />
    <AboutMe />
    <Projects />
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Hompage from "./components/Hompage.vue";
import AboutMe from "./components/AboutMe.vue";
import Projects from "./components/Projects.vue";
export default {
  name: "App",
  components: {
    Navbar,
    Hompage,
    AboutMe,
    Projects,
  },
};
</script>

<style>
body {
  background-color: #485563 !important;
}
#app {
  font-family: "Fondamento", cursive;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #e4e3e3;
}
</style>
