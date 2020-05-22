<template>
  <div id="app">
    <ProductListOne />
    <ProductListTwo />
  </div>
</template>

<script>
import ProductListOne from "@/components/ProductListOne.vue";
import ProductListTwo from "@/components/ProductListTwo.vue";

export default {
  name: "App",
  components: {
    ProductListOne,
    ProductListTwo,
  },
  data() {
    return {};
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
