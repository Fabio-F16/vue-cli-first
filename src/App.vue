<template>
  <div id="app">
    <MainTitle />
    <HeroJumbotron />
  </div>
</template>

<script>
import MainTitle from "./components/MainTitle.vue";
import HeroJumbotron from "./components/HeroJumbotron.vue";

export default {
  name: "App",
  components: {
    MainTitle,
    HeroJumbotron,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
