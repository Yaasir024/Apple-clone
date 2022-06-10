
<template>

  <Nav />
  <RouterView />
</template>

<script>
import { RouterLink, RouterView } from 'vue-router'
import Nav from '@/components/Nav.vue'

export default {
  components: {
    Nav,
  }
}
</script>



<style>
@import '@/assets/base.css';


</style>
