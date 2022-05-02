<template>
  <div class="leading-normal tracking-normal text-white gradient">
    <Header />
    <nuxt />
    <!-- <Footer /> -->
  </div>
</template>

<script>
import Header from '@/components/Header.vue'
import Footer from '@/components/Footer.vue'

export default {
  components: {
    Header,
    Footer
  }
}
</script>

<style>
.gradient {
  background: radial-gradient(circle at 80% 20%, #2d2f54 0%, #a8527c 100%);
  background-attachment: fixed;
}
</style>
