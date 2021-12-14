<template>
  <h2>For Loop</h2>
  <label>Technologies</label>
  <ul>
    <li v-for="item in technology" :key="item">{{ item }}</li>
  </ul>
  <label>Users Name:</label>
  <ul>
    <li v-for="item in users" :key="item.name">{{ item.name }}</li>
  </ul>
  <label>Users age:</label>
  <ul>
    <li v-for="item in users" :key="item.age">{{ item.age }}</li>
  </ul>
  <label>Users name and age:</label>
  <ul>
    <li v-for="item in users" :key="item.name + item.age">
      {{ item.name }} - {{ item.age }}
    </li>
  </ul>
</template>

<script>
export default {
  name: "ForLoop",
  data() {
    return {
      technology: ["java", "javascript", "node", "react", "vue"],
      users: [
        { name: "John", age: 30 },
        { name: "Mary", age: 25 },
        { name: "Peter", age: 35 },
      ],
    };
  },
};
</script>

<style scoped></style>
