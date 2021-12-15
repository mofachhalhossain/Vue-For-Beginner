<template>
  <h1>Class Binding</h1>
  <!-- one static class and one dynamic class -->
  <h2 class="staticClass" :class="{ green: colorfull }">Home Component</h2>
  <!-- Two dynamic classes -->
  <h2 :class="{ green: colorfull, dynamicClass: colorfull }">Home Component</h2>
  <h2 :class="adjustStyle">Multiple class</h2>
  <button @click="colorfull = !colorfull">Change Me</button>
</template>

<script>
export default {
  name: "ClassBinding",
  data() {
    return {
      colorfull: true,
    };
  },
  computed: {
    adjustStyle() {
      return {
        green: this.colorfull,
        staticClass: true,
      };
    },
  },
};
</script>

<style scoped>
.green {
  color: green;
  background-color: orangered;
  width: 200px;
  padding: 10px;
  text-align: center;
  margin-left: 42%;
}
.staticClass {
  color: black;
  background-color: orangered;
  width: 200px;
  padding: 10px;
  text-align: center;
  margin-left: 42%;
}
.dynamicClass {
  color: yellow;
  background-color: paleturquoise;
  width: 200px;
  padding: 10px;
  text-align: center;
  margin-left: 42%;
}
</style>
