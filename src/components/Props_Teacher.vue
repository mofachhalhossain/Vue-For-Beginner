<template>
  <h1>Teacher Component</h1>
  <h3>Name: {{ name }}</h3>
</template>

<script>
export default {
  name: "Props_Teacher",
  props: {
    name: String,
  },
};
</script>

<style scoped></style>
