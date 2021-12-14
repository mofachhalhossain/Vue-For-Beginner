<template>
  <h2>PassDataParentToChild</h2>
  <p>{{ name }}</p>
  <p>{{ user.age }}</p>
  <button @click="getemail()">click</button>
</template>

<script>
export default {
  name: "PassDataParentToChild",
  props: { name: String, user: Object, getemail: Function },
};
</script>

<style scoped></style>
