<template>
  <h2>Simple Form</h2>
  <form>
    <label>Email</label>
    <input type="email" placeholder="Enter Email" v-model="email" /><br />
    <label>Password</label>
    <input
      type="password"
      placeholder="Enter Password"
      v-model="password"
    /><br />
    <button type="button" @click="submit()">Submit</button>
  </form>
</template>

<script>
export default {
  name: "SimpleFormExample",
  data() {
    return {
      email: "",
      password: "",
    };
  },
  methods: {
    submit() {
      alert(this.email + " " + this.password);
    },
  },
};
</script>

<style scoped></style>
