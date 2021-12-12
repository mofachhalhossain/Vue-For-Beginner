<template>
  <h2>I'm your first component</h2>
  <p>{{ msg }}</p>
</template>

<script>
export default {
  name: "FirstComponent",
  props: {
    msg: String,
  },
};
</script>

<style scoped>
h2 {
  color: red;
}
</style>
