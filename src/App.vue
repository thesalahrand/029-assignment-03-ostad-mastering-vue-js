<script setup>
import Preloader from './components/Preloader.vue'
import Navbar from './components/Navbar.vue'
import Hero from './components/Hero.vue'
import BestFeatures from './components/BestFeatures.vue'
import Services from './components/Services.vue'
import AppScreenshots from './components/AppScreenshots.vue'
import Pricing from './components/Pricing.vue'
import Testimonials from './components/Testimonials.vue'
import DownloadApp from './components/DownloadApp.vue'
import ContactUs from './components/ContactUs.vue'
import Footer from './components/Footer.vue'
</script>

<template>
  <Preloader />
  <Navbar />
  <div class="main">
    <Hero />
    <BestFeatures />
    <Services />
    <AppScreenshots />
    <Pricing />
    <Testimonials />
    <DownloadApp />
    <ContactUs />
  </div>
  <Footer />
</template>

<style scoped></style>
