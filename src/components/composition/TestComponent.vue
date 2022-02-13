<template>
  <h2>Hello Resuability</h2>
  <hr />
  <FeeStatus />
  <hr />
  <ProductStatus />
  <hr />
  <SavingStatus />
</template>

<script>
import FeeStatus from "../mixin/FeeStatus";
import ProductStatus from "../mixin/ProductStatus";
import SavingStatus from "../mixin/SavingStatus";
import {} from "vue";
export default {
  name: "TestComponent",
  components: {
    FeeStatus,
    ProductStatus,
    SavingStatus,
  },
};
</script>

<style></style>
