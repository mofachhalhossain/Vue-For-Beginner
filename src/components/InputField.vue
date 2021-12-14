<template>
  <h1>Get InputField</h1>
  <input type="text" placeholder="Enter email" v-model="email" /><br /><br />
  <input
    type="password"
    placeholder="Enter password"
    v-model="password"
  /><br /><br />
  <button type="button" @click="getData()">Get Data</button>
</template>

<script>
export default {
  name: "InputField",
  data() {
    return {
      email: "",
      password: "",
    };
  },
  methods: {
    getData() {
      console.warn(this.email, this.password);
    },
  },
};
</script>

<style scoped></style>
