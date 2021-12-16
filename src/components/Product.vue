<template>
  <div class="container mb-5">
    <div class="title mb-5 text-center">
      <h1>What Else Do You Order Now</h1>
      <h3>Order now and we are ready to deliver to your destination address</h3>
    </div>
    <div class="row mb-5">
      <div class="col-2">
        <button type="button" class="btn">
          <img src="img/all-menu.png" height="40px" alt="" /> All Menu
        </button>
      </div>
      <div class="col-2">
        <button type="button" class="btn">
          <img src="img/donuts.png" height="40px" alt="" /> Donuts
        </button>
      </div>
      <div class="col-2">
        <button type="button" class="btn">
          <img src="img/dessert.png" height="40px" alt="" /> Dessert
        </button>
      </div>
      <div class="col-2">
        <button type="button" class="btn">
          <img
            src="img/coffee.png"
            height="40px"
            style="margin-left: -3px"
            alt=""
          />
          Hot Drinks
        </button>
      </div>
      <div class="col-2">
        <button type="button" class="btn">
          <img src="img/cup.png" height="40px" alt="" /> Cold Drinks
        </button>
      </div>
      <div class="col-2">
        <button type="button" class="btn">
          <img src="img/discount.png" height="40px" alt="" /> Discount
        </button>
      </div>
    </div>
    <div class="row">
      <div class="col">
        <div class="input-group">
          <div class="input-group-text bg-transparent">
            <i class="fas fa-search"></i>
          </div>
          <input
            type="text"
            class="form-control"
            placeholder="Find your menu here.."
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Product",
};
</script>

<style scoped>
.btn {
  width: 190px;
  height: 70px;
  filter: drop-shadow(0px 0px 10px #e1e1e3);
  border: none;
  background-color: white;
  border-radius: 10px;
  font-style: normal;
  font-weight: 500;
  font-size: 20px;
  line-height: 30px;
  text-align: center;
  outline: none;
  color: #674034;
}

.btn:focus {
  background: #ffe6ef;
  outline: none;
}

.btn:hover {
  background: #ffe6ef;
  outline: none;
}

.btn img {
  margin: 10px 10px 10px 10px;
}

.title h1 {
  font-style: normal;
  font-weight: bold;
  font-size: 48px;
  line-height: 56px;
  /* identical to box height, or 117% */

  text-align: center;
  letter-spacing: 0.012em;

  /* Brown */

  color: #674034;
}

.title h3 {
  color: #a5adbb;
}
</style>
