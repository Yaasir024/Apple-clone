<template>
  <Nav />
  <RouterView />
  <Footer />
</template>

<script>
import { RouterLink, RouterView } from "vue-router";
import Nav from "@/components/Nav.vue";
import Footer from "@/components/Footer.vue";

export default {
  components: {
    Nav,
    Footer,
  },
};
</script>

<style>
@import "@/assets/base.css";
</style>
