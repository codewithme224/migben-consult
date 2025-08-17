<script setup lang="ts">
import Navigation from './components/Navigation.vue'
import HeroSection from './components/HeroSection.vue'
import AboutSection from './components/AboutSection.vue'
import ServicesSection from './components/ServicesSection.vue'
import ProductsSection from './components/ProductsSection.vue'
import PartnersSection from './components/PartnersSection.vue'
import ContactSection from './components/ContactSection.vue'
import FooterSection from './components/FooterSection.vue'
</script>

<template>
  <div class="min-h-screen bg-primary-900">
    <Navigation />
    <HeroSection />
    <AboutSection />
    <ServicesSection />
    <ProductsSection />
    <PartnersSection />
    <ContactSection />
    <FooterSection />
  </div>
</template>
