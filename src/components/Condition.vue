<template>
  <h1>Condition in Vue3</h1>
  <p v-if="show">I'm If</p>
  <p v-else>I'm Else</p>
  <p class="click" v-if="click">I'm Changeable</p>
  <button @click="onclick">Click</button>
</template>

<script>
export default {
  name: "Condition",
  data() {
    return {
      show: true,
      click: true,
    };
  },
  methods: {
    onclick() {
      this.click = !this.click;
    },
  },
};
</script>

<style scoped>
button {
  background: #ccc;
  padding: 5px;
  border-radius: 5px;
  color: rgb(0, 132, 255);
  font-size: 14px;
}
.click {
  color: red;
  font-weight: bold;
}
</style>
