<template>
  <div>
    <div class="Header">
      <div class="container">
        <NavBar />
        <Banner />
        <Featured />
        <div class="small-container">
          <h2>Featured Products</h2>
          <Product />
          <h2 class="title">Latest Products</h2>
          <Product />
        </div>
      </div>
    </div>
    <!--- Offer -->
    <Offer />
    <!--- Testimonials --->
    <Testimonials />
    <!--- Brands -->
    <Brands />
    <!--- Footer -->
    <Footer />
  </div>
</template>

<script>
//
// @ is an alias to /src
import NavBar from "@/components/TheNavBar.vue";
import Banner from "@/components/TheBanner.vue";
import Featured from "@/components/TheFeatured.vue";
import Product from "@/components/TheProduct.vue";
import Offer from "@/components/TheOffer.vue";
import Testimonials from "@/components/TheTestimonials.vue";
import Footer from "@/components/TheFooter.vue";
import Brands from "@/components/TheBrand.vue";
//
//Decalre the Class componet to manage all the functions and data to the template.
export default {
  name: "Home",
  components: {
    NavBar,
    Banner,
    Featured,
    Product,
    Offer,
    Testimonials,
    Footer,
    Brands
  },
  data() {
    return {};
  },
  methods: {}
};
</script>
<style>
.container {
  max-width: 1300px;
  margin: auto;
  padding-left: 25px;
  padding-right: 25px;
}
.row {
  display: flex;
  align-items: center;
  flex-wrap: wrap;
  justify-content: space-around;
}
.col-2 {
  flex-basis: 45%;
  min-width: 300px;
}
.col-2 img {
  max-width: 100%;
  padding: 50px 0px;
}
.col-2 h1 {
  font-size: 50px;
  line-height: 60px;
  margin: 25px 0;
}
.btn {
  display: inline-block;
  background: #ff523b;
  color: #fff;
  padding: 8px 30px;
  margin: 30px 0;
  border-radius: 30px;
  transition: background 0.5s;
}
.btn:hover {
  background: #563434;
}
.header {
  background: radial-gradient(#fff, #ffd6d6);
}
.header .row {
  margin-top: 70px;
}
</style>
