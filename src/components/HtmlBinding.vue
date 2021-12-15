<template>
  <h1>Html Binding</h1>
  <h3>{{ name }}</h3>
  <div v-html="tag1 + tag2"></div>
</template>

<script>
export default {
  name: "HtmlBinding",
  data() {
    return {
      name: "Peter",
      tag1: "<h1>Age: 30</h1>",
      tag2: "<p>Email: peter@example.com</p>",
    };
  },
};
</script>

<style scoped></style>
