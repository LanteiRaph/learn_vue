<template>
  <!-------Single Produts details ---------->
  <div class="small-container single-product">
    <div class="row">
      <div class="col-2">
        <img src="images/gallery-1.jpg" width="100%" id="product-img" />
        <div class="small-img-row">
          <div class="small-img-col">
            <img src="images/gallery-1.jpg" width="100%" class="small-img" />
          </div>
          <div class="small-img-col">
            <img src="images/gallery-2.jpg" width="100%" class="small-img" />
          </div>
          <div class="small-img-col">
            <img src="images/gallery-3.jpg" width="100%" class="small-img" />
          </div>
          <div class="small-img-col">
            <img src="images/gallery-4.jpg" width="100%" class="small-img" />
          </div>
        </div>
      </div>
      <div class="col-2">
        <p>Home / T-shirt</p>
        <h1>Red Printed T-shirt by Muiruri</h1>
        <h4>Sh500</h4>
        <select>
          <option>Select Size</option>
          <option>XXl</option>
          <option>Xl</option>
          <option>Large</option>
          <option>Medium</option>
          <option>Small</option>
        </select>
        <input type="number" value="1" />
        <a href="" class="btn"> Add to Cart</a>
        <h3>Product Details <i class="fa fa-ident"></i></h3>
        <br />
        <p>
          Give your summer wadrobe a style upgrade with the Muiruri man Active
          T-shirt. Team it with apart of shorts for your morning workout or
          demin for an eveing out.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Product Deatil",
  components: {},
  data() {
    return {};
  }
};
</script>
