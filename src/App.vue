<template>
  <div id="app">
    <PersonalInfo />
  </div>
</template>

<script>
import PersonalInfo from "./components/PersonalInfo.vue";

export default {
  name: "App",
  components: {
    PersonalInfo,
  },
};
</script>

<style>
body {
  background-color: #000000;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ffff;
  background-color: #000000;
  margin-top: 60px;
}
a {
  color: #9b9b9b;
}
</style>
