<template>
  <h1>Non Props Data</h1>
  <div>
    <ul>
      <li v-bind="$attrs">Peter</li>
      <li>Bruce</li>
      <li v-bind="$attrs">Sara</li>
    </ul>
    <h2>{{ item }}</h2>
  </div>
</template>

<script>
export default {
  name: "Non_PropsData",
  props: {
    item: String,
  },
};
</script>

<style scoped></style>
