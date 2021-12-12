<template>
  <p>Interpolation:</p>
  <p>Name: {{ setname() }}</p>
  <p>Age: {{ getage("34") }}</p>
  <p>Email & Mobile: {{ email + " " + mobile }}</p>
</template>

<script>
export default {
  name: "Interpolation",
  data() {
    return {
      email: "test@test.com",
      mobile: "1234567890",
      setname() {
        return "Anil Siddhu";
      },
      getage(x) {
        return x;
      },
    };
  },
};
</script>

<style scoped>
p {
  color: gray;
}
</style>
