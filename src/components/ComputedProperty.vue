<template>
  <h2>Computed Properties</h2>
  <p>Product_price: {{ product_price }} dollar</p>
  <p>Final: {{ getResult }} dollar</p>
  <h3>Message: {{ message }}</h3>
  <p>Reverse Message: {{ getMessage }}</p>
</template>

<script>
export default {
  name: "ComputedProperty",
  data() {
    return {
      product_price: 100,
      purchage_price: 95,
      discount: 5,
      message: "I'm a Product",
    };
  },
  computed: {
    getResult() {
      return (this.product_price - this.purchage_price) * this.discount;
    },
    getMessage() {
      return this.message.split("").reverse().join("");
    },
  },
};
</script>

<style scoped></style>
