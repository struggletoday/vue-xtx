<script>
import TopNavigate from './components/TopNavigate.vue';
import TopMenu from './components/TopMenu.vue';
import Banner from './components/Banner.vue';
import Footer from './components/Footer.vue';
import Product from './components/Product.vue';


export default {
  components: {
    TopNavigate, TopMenu, Banner, Footer, Product
  }
}
</script>

<template>
  <TopNavigate />
  <TopMenu />
  <Banner />
  <Product />
  <Footer />
</template>

<style scoped></style>
