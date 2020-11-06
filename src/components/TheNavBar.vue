<template>
  <div class="navbar">
    <div class="logo">
      <a href="index.php"
        ><img src="../assets/images/logo.png" width="125px"
      /></a>
    </div>
    <nav>
      <ul id="menuItems">
        <li><router-link to="/products">Wardrobe</router-link></li>
        <li><router-link to="/Art">Drawings/Art</router-link></li>
        <li><router-link to="/">Designer</router-link></li>
        <li><router-link href="account.php">Account</router-link></li>
      </ul>
    </nav>
    <a href="/cart"
      ><img src="../assets/images/cart.png" width="30px" height="30px"
    /></a>
    <a href="/account" padding="10px"
      ><img src="../assets/user.png" width="30px" height="30px"
    /></a>
    <img
      src="../assets/images/menu.png"
      class="menu-icon"
      onclick="menutoggle()"
      width="30px"
      height="30px"
    />
  </div>
</template>

<script>
export default {
  name: "NavBar",
  data() {
    return {
      menuItems: null
    };
  },
  props: {
    msg: String
  },
  methods: {
    menutoggle() {
      //
      if (this.menuItems.style.maxHeight === "0px") {
        this.menuItems.style.maxHeight = "200px";
      } else {
        this.menuItems.style.maxHeight = "0px";
      }
    },
    manageMenu() {
      this.menuItems = this.$el.querySelector("#menuItems");
      this.menuItems.style.maxHeight = "0px";
      console.log(this.menuItems);
    }
  },
  created() {},
  mounted() {
    //
    //mange the Menu icon, no visble to large screens.
    this.manageMenu();
  }
};
</script>
