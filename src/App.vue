<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <CiaoMondo />
    <JumboHero />
  </div>
</template>

<script>
import CiaoMondo from "./components/CiaoMondo.vue";
import JumboHero from "./components/JumboHero.vue";

export default {
  name: "App",
  components: {
    CiaoMondo,
    JumboHero,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  position: relative;
}
</style>
