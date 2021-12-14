<template>
  <h1>Get checkboxAndRadioButton</h1>
  <h3>Technologies</h3>
  <input type="checkbox" value="java" id="java" v-model="technology" />
  <label>Java</label><br />
  <input type="checkbox" value="node" id="node" v-model="technology" />
  <label>Node</label><br />
  <input type="checkbox" value="React" id="React" v-model="technology" />
  <label>React</label><br />
  <input type="checkbox" value="Vue3" id="Vue3" v-model="technology" />
  <label>Vue3</label>
  <p>Technologies: {{ technology }}</p>
  <h3>Profession</h3>
  <input type="radio" value="intern" id="intern" v-model="profession" />
  <label>Intern</label><br />
  <input type="radio" value="juniorDev" id="juniorDev" v-model="profession" />
  <label>Junior Dev</label><br />
  <input type="radio" value="seniorDev" id="seniorDev" v-model="profession" />
  <label>Senior Dev</label><br />
  <p>Profession: {{ profession }}</p>
</template>

<script>
export default {
  name: "CheckboxAndRadioButton",
  data() {
    return {
      technology: [],
      profession: "",
    };
  },
};
</script>

<style scoped></style>
