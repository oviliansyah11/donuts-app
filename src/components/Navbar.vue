<template>
  <nav class="navbar navbar-expand-lg mt-3">
    <div class="container">
      <img src="img/logo.png" height="60px" alt="" />
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse">
        <ul class="navbar-nav mx-auto">
          <li class="nav-item">
            <a class="nav-link active" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Need Help?</a>
          </li>
        </ul>
        <div class="cart">
          <div class="icon">
            <a href="#"><i class="fas fa-shopping-cart"></i></a>
          </div>
        </div>
        <button class="btn btn-login" type="submit">Sign In</button>
        <button class="btn btn-signup" type="submit">Sign Up</button>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style scoped>
.cart {
  width: 38px;
  height: 38px;
  background: #ffe6ef;
  margin-right: 40px;
  border-radius: 50px;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 10px;
}

nav .navbar-nav li a {
  color: black;
}

nav .navbar-nav .active {
  color: #ff4a8b;
}

.btn-login {
  background-color: #eeeeee;
  border: 1px solid #eeeeee;
  box-sizing: border-box;
  border-radius: 4px;
  font-weight: 500;
  font-size: 16px;
  width: 120px;
  height: 46px;
  color: #c9c9c9;
  margin-right: 20px;
  font-weight: 500;
}

.btn-signup {
  background-color: #ff4a8b;
  border: 1px solid #eeeeee;
  box-sizing: border-box;
  border-radius: 4px;
  font-weight: 500;
  font-size: 16px;
  width: 120px;
  height: 46px;
  color: white;
  font-weight: 500;
}
</style>
