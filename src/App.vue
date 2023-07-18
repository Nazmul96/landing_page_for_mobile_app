<script setup>
  import HeaderTop from './components/HeaderTop.vue'
  import BannerTop from './components/BannerTop.vue'
  import Home from './components/Home.vue'
  import Footer from './components/Footer.vue'
  import Testimonial from './components/Testimonial.vue'
  import Cta from './components/Cta.vue'
  import Pricing from './components/Pricing.vue'
  import BlogPage from './components/BlogPage.vue'
  import ContactUs from './components/ContactUs.vue'

</script>

<template>
 <HeaderTop/>
 <BannerTop/>
  
 <main id="main">
   
  <Home/>
  <Pricing/>
  <BlogPage/>
  <Testimonial/>
  <ContactUs/>
  <Cta/>
  

 </main><!-- End #main -->

 <Footer/>

</template>

<style scoped>
@import '/src/assets/bootstrap.min.css';
</style>
