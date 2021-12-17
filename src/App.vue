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
  <!-- <PassDataParentToChild :name="name" :user="user" :getemail="getemail" /> -->

  <!-- <ul>
    <li v-for="item in users" :key="item">
      <ReuseComponents :data="item" />
    </li>
  </ul> -->
  <!-- <HtmlBinding /> -->
  <!-- <ClassBinding /> -->
  <!-- <Props_Student :name="name" :email="email" />
  <Props_Teacher name="Peter" /> -->
  <!-- <RefOrDOM /> -->
  <!-- <SimpleFormExample :submit="submit" /> -->
  <!-- <Non_PropsData item="some data" name="user-cmp" /> -->
  <!-- <ComputedProperty /> -->
  <!-- <WatcherOrObserver /> -->
  <Slots><h1>Code step by step</h1></Slots>
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
/* import PassDataParentToChild from "./components/PassDataParentToChild.vue"; */
/* import ReuseComponents from "./components/ReuseComponents.vue"; */
/* import HtmlBinding from "./components/HtmlBinding.vue"; */
/* import ClassBinding from "./components/ClassBinding.vue"; */
/* import Props_Student from "./components/Props_Student.vue";
import Props_Teacher from "./components/Props_Teacher.vue"; */
/* import RefOrDOM from "./components/RefOrDOM.vue"; */
/* import SimpleFormExample from "./components/SimpleFormExample.vue"; */
/* import Non_PropsData from "./components/Non_PropsData.vue"; */
/* import ComputedProperty from "./components/ComputedProperty.vue"; */
/* import WatcherOrObserver from "./components/WatcherOrObserver.vue"; */
import Slots from "./components/Slots.vue";

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
    /* PassDataParentToChild, */
    /* ReuseComponents, */
    /* HtmlBinding, */
    /* ClassBinding, */
    /* Props_Student,
    Props_Teacher, */
    /* RefOrDOM, */
    /* SimpleFormExample, */
    /* Non_PropsData, */
    /* ComputedProperty, */
    /* WatcherOrObserver, */
    Slots,
  },
  /* data() {
    return {
      email: this.email,
      password: this.password,
    };
  },
  props: { submit: Function }, */
  /*  data passing from parent to child: */
  /* data() {
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
}; */

  /* data() {
    return {
      users: [
        { name: "Sara", age: "23" },
        { name: "John", age: "24" },
        { name: "Bob", age: "25" },
      ],
    };
}; */
  /* props and child to parent data transfer */
  /* data() {
    return {
      name: "Bruce",
    };
  },
  props: { email: String }, */
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
