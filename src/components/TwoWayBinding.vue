<template>
  <h1>Two way binding</h1>
  <input type="text" v-model="count" />
  <p>{{ count }}</p>
</template>

<script>
export default {
  name: "TwoWayBinding",
  data() {
    return {
      count: "",
    };
  },
};
</script>
