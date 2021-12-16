<template>
  <div id="app">
    <Navbar />
    <Banner />
    <Contact />
    <Order />
    <Product />
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Banner from "./components/Banner.vue";
import Contact from "./components/Contact.vue";
import Order from "./components/Order.vue";
import Product from "./components/Product.vue";

export default {
  name: "App",
  components: {
    Navbar,
    Banner,
    Contact,
    Order,
    Product,
  },
};
</script>
