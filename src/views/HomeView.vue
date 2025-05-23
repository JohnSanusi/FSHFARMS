<script setup>
import Hero from "@/components/Hero.vue";
import Sidebar from " @/components/Sidebar.vue";
import About from "@/components/About.vue";
import HomeGallery from "@/components/Home-Gallery.vue";
import Products from "@/components/Products.vue";
import Contact from "@/components/Contact.vue";
import Footer from "@components/Footer.vue";
</script>

<template>
  <header>
    <Sidebar />
    <Hero />
  </header>
  <main>
    <About />
    <Products />
    <HomeGallery />
    <Contact />
  </main>
  <footer>
    <Footer />
  </footer>
</template>
