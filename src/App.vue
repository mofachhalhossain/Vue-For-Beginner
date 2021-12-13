<template>
  <h1>Hello I'm Vue3</h1>
  <!-- <FirstComponent msg="Hello" /> -->
  <!-- <Interpolation /> -->
  <!-- <DefineMethod /> -->
  <Events />
</template>

<script>
/* import FirstComponent from "./components/FirstComponent.vue"; */
/* import Interpolation from "./components/Interpolation.vue"; */
/* import DefineMethod from "./components/DefineMethod.vue"; */
import Events from "./components/Events.vue";
export default {
  name: "App",
  components: {
    /* FirstComponent, */
    /* Interpolation, */
    /* DefineMethod, */
    Events,
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
