<template>
  <p>Email: {{ email }}</p>
  <p>Name: {{ getname() }}</p>
  <p>Gender: {{ getgender() }}</p>
</template>

<script>
export default {
  name: "DefineMethod",
  data() {
    return {
      email: "example@test.com",
    };
  },
  methods: {
    getname() {
      return "John Doe";
    },
    getgender() {
      return "male";
    },
  },
};
</script>

<style></style>
