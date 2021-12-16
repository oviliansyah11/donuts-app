<template>
  <div class="container banner d-flex align-items-center">
    <h1>
      Make <strong style="color: #ff4a8b">Delivery</strong> And <br />
      Enjoy Soft And Delicious
      <strong style="color: #ff4a8b">Donuts</strong>
    </h1>
  </div>
</template>

<script>
export default {
  name: "Banner",
};
</script>

<style scoped>
.banner {
  margin-top: 30px;
  background-image: url("/img/banner.jpg");
  height: 550px;
  background-size: cover;
  border-radius: 20px;
}

.banner h1 {
  font-style: normal;
  font-weight: bold;
  font-size: 55px;
  /* line-height: 90px;
  letter-spacing: 0.045em; */
  text-transform: capitalize;
  margin-left: 50px;
  color: #4f423e;
}
</style>
