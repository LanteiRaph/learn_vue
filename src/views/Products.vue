<template>
  <div>
    <!----- Header Section ----->
    <div class="container">
      <NavBar />
    </div>
    <!-------Single Produts details ---------->
    <div class="small-container single-product">
      <div class="row row-2">
        <h1>All Products</h1>
        <select>
          <option>Default Sorting</option>
          <option>Sort by Price</option>
          <option>Sort by Popularity</option>
          <option>Sort by rating</option>
          <option>Sort by sale</option>
        </select>
      </div>
      <Product />
    </div>
    <!---- The Footer Section --->
    <Footer />
  </div>
</template>

<script>
//
//Import all needed Components
import NavBar from "../components/TheNavBar.vue";
import Product from "../components/TheProduct.vue";
import Footer from "../components/TheFooter.vue";
export default {
  name: "Product Details",
  components: { NavBar, Product, Footer },
  data() {
    return {};
  }
};
</script>
