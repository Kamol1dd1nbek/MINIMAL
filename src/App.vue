<template>
  <div class="app">
    <Navbar/>
    <br>
    <MainPage/>
    <ProcessPage/>
    <Projects/>
    <Team/>
  </div>
</template>

<script setup>
import Navbar from "./components/MianNavbar.vue";
import MainPage from "./components/MainPage.vue";
import ProcessPage from "./components/Process.vue";
import Projects from "./components/Projects.vue";
import Team from "./components/Team.vue";
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

body::-webkit-scrollbar {
  display: none;
}

* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
</style>
