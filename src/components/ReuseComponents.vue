<template>
  <h1>{{ data.name + data.age }}</h1>
</template>

<script>
export default {
  name: "ReuseComponents",
  props: {
    data: Object,
  },
};
</script>

<style scoped></style>
