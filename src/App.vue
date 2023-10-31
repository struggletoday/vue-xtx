<script>
import TopNavigate from './components/TopNavigate.vue';
import TopMenu from './components/TopMenu.vue';
import Banner from './components/Banner.vue';
import Footer from './components/Footer.vue';

export default {
  components: {
    TopNavigate, TopMenu, Banner, Footer
  }
}
</script>

<template>
  <TopNavigate />
  <TopMenu />
  <Banner />
  <Footer />
</template>

<style scoped></style>
