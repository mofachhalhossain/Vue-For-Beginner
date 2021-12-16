<template>
  <h3>WatcherOrObserver</h3>
  <h1>{{ count }}</h1>
  <button @click="counter()">Add</button>
</template>

<script>
export default {
  name: "WatcherOrObserver",
  data() {
    return { count: 0 };
  },
  methods: {
    counter() {
      this.count = this.count + 1;
    },
  },
  watch: {
    count(val) {
      if (val >= 3) {
        alert("Stop counting!");
      }
    },
  },
};
</script>

<style scoped></style>
