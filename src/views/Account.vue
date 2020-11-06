<template>
  <div>
    <NavBar />
    <div class="account-page">
      <div class="container">
        <div class="row">
          <div class="col-2"><img src="images/image1.png" /></div>
          <div class="col-2">
            <div class="form-container">
              <div class="form-btn">
                <span onclick="login()">Login</span>
                <span onclick="register()">Register</span>
                <hr id="indicator" />
              </div>
              <form id="login-form">
                <input type="text" placeholder="Username" />
                <input type="password" placeholder="password" />
                <button type="submit" class="btn">Login</button>
                <br />
                <a href="">Forgot Password</a>
              </form>
              <form id="register-form">
                <input type="text" placeholder="Username" />
                <input type="email" placeholder="Email" />
                <input type="password" placeholder="password" />
                <button type="submit" class="btn">Register</button>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import NavBar from "@/components/TheNavBar.vue";
export default {
  name: "",
  components: { NavBar }
};
</script>
