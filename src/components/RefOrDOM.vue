<template>
  <h1>Ref Or Dom</h1>
  <input type="text" ref="input" />
  <button @click="refData()">Click</button>
</template>

<script>
export default {
  name: "RefOrDOM",
  methods: {
    refData() {
      this.$refs.input.focus();
      /* this.$refs.input.value = "Hello"; */
      this.$refs.input.style.color = "red";
      console.warn(this.$refs.input.value);
    },
  },
};
</script>

<style scoped></style>
