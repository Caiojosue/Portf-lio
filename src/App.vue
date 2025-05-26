<script setup>
import Navbar from './components/NavbarComponents.vue';
import Footer from './components/FooterComponents.vue';
</script>

<template>
  <div class="flex flex-col min-h-screen bg-white">
    <Navbar />
    <div class="main container mx-auto px-4 py-6">
      <router-view></router-view>
    </div>
    <Footer></Footer>
  </div>
</template>