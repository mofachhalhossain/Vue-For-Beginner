<template>
  <h1>Hello I'm Vue3</h1>
  <!-- <FirstComponent msg="Hello" /> -->
  <!-- <Interpolation /> -->
  <!-- <DefineMethod /> -->
  <!-- <Events /> -->
  <!-- <TwoWayBinding /> -->
  <!-- <InputField /> -->
  <!-- <CheckboxAndRadioButton /> -->
  <!-- <Condition /> -->
  <!-- <ForLoop /> -->
  <PassDataParentToChild :name="name" :user="user" :getemail="getemail" />
</template>

<script>
/* import FirstComponent from "./components/FirstComponent.vue"; */
/* import Interpolation from "./components/Interpolation.vue"; */
/* import DefineMethod from "./components/DefineMethod.vue"; */
/* import Events from "./components/Events.vue"; */
/* import TwoWayBinding from "./components/TwoWayBinding.vue"; */
/* import InputField from "./components/InputField.vue"; */
/* import CheckboxAndRadioButton from "./components/CheckboxAndRadioButton.vue"; */
/* import Condition from "./components/Condition.vue"; */
/* import ForLoop from "./components/ForLoop.vue"; */
import PassDataParentToChild from "./components/PassDataParentToChild.vue";

export default {
  name: "App",
  components: {
    /* FirstComponent, */
    /* Interpolation, */
    /* DefineMethod, */
    /* Events, */
    /* TwoWayBinding, */
    /* InputField, */
    /* CheckboxAndRadioButton, */
    /* Condition, */
    /* ForLoop, */
    PassDataParentToChild,
  },
  data() {
    return {
      name: "Sara",
      user: {
        name: "Sara",
        age: "23",
      },
    };
  },
  methods: {
    getemail() {
      alert("Function called");
    },
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
