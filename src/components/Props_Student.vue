<template>
  <h2>Student Component</h2>
  <h3>Name: {{ name }}</h3>
  <p>{{ email }}</p>
</template>

<script>
export default {
  name: "Props_Student",
  props: {
    name: String,
  },
  data() {
    return {
      email: "student@test.com",
    };
  },
};
</script>

<style scopped></style>
