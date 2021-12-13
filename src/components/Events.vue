<template>
  <h1 @mousemove="getconsole()">l</h1>
  <button @click="onclick()">Click</button>
  <button @dblclick="dbclick()">Double Click</button>
  <h2>{{ count }}</h2>
  <button @click="counti()">Count</button>
</template>

<script>
export default {
  name: "Events",
  data() {
    return {
      count: 0,
    };
  },
  methods: {
    onclick() {
      alert("Clicked");
    },
    dbclick() {
      alert("Double Clicked");
    },
    getconsole() {
      console.log("mouse moved");
    },
    counti() {
      this.count = this.count + 1;
    },
  },
};
</script>

<style scoped></style>
