<script setup lang="ts">
import { ref, onMounted } from 'vue'
import Navigation from './components/Navigation.vue'
import HeroSection from './components/HeroSection.vue'
import AboutSection from './components/AboutSection.vue'
import WorkflowSection from './components/WorkflowSection.vue'
import ServicesSection from './components/ServicesSection.vue'
import ProductsSection from './components/ProductsSection.vue'
import PartnersSection from './components/PartnersSection.vue'
import ContactSection from './components/ContactSection.vue'
import FooterSection from './components/FooterSection.vue'

const isLoading = ref(true)

onMounted(() => {
  // Hide loader after delay (simulate page loading)
  setTimeout(() => {
    isLoading.value = false
  }, 2500) // 2.5 seconds loading time
})
</script>

<template>
  <div class="min-h-screen bg-primary-900">
    <!-- Page Loader -->
    <div 
      v-if="isLoading" 
      class="fixed inset-0 z-[999999] bg-primary-900/90 backdrop-blur-md flex items-center justify-center"
    >
      <!-- Loading Animation Container -->
      <div class="text-center">
        <!-- Logo with Animation -->
        <div class="mb-8 relative">
          <div class="animate-pulse-slow">
            <img 
              class="h-32 w-auto mx-auto rounded-full shadow-2xl ring-4 ring-gold-500/50 animate-bounce-gentle" 
              src="/images/logo2.png" 
              alt="MIGBEN Logo"
            />
          </div>
          
          <!-- Rotating Ring -->
          <div class="absolute inset-0 rounded-full border-4 border-transparent border-t-gold-400 animate-spin-slow"></div>
          
          <!-- Pulsing Glow -->
          <div class="absolute inset-0 rounded-full bg-gold-400/20 animate-ping"></div>
        </div>
        
        <!-- Company Name with Typewriter Effect -->
        <div class="mb-6">
          <h1 class="text-4xl md:text-5xl font-bold text-white mb-2 animate-fade-in-up">
            <span class="bg-gold-gradient bg-clip-text text-transparent">MIGBEN</span>
          </h1>
          <p class="text-lg text-gray-300 animate-fade-in-up-delay">
            LOGISTICS & CONSULTANCY
          </p>
        </div>
        
        <!-- Loading Bar -->
        <div class="w-64 mx-auto bg-white/20 rounded-full h-2 overflow-hidden">
          <div class="h-full bg-gold-gradient animate-loading-bar rounded-full"></div>
        </div>
        
        <!-- Loading Text -->
        <p class="text-gray-300 mt-4 animate-fade-in-up-delay-2">
          Loading your experience...
        </p>
      </div>
    </div>

    <!-- Main Content -->
    <Navigation />
    <HeroSection />
    <AboutSection />
    <WorkflowSection />
    <ServicesSection />
    <ProductsSection />
    <PartnersSection />
    <ContactSection />
    <FooterSection />
  </div>
</template>

<style scoped>
/* Custom Loading Animations */
@keyframes bounce-gentle {
  0%, 100% {
    transform: translateY(0);
  }
  50% {
    transform: translateY(-10px);
  }
}

@keyframes pulse-slow {
  0%, 100% {
    opacity: 1;
  }
  50% {
    opacity: 0.7;
  }
}

@keyframes spin-slow {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}

@keyframes loading-bar {
  0% {
    width: 0%;
    transform: translateX(-100%);
  }
  50% {
    width: 100%;
    transform: translateX(0%);
  }
  100% {
    width: 100%;
    transform: translateX(100%);
  }
}

@keyframes fade-in-up {
  0% {
    opacity: 0;
    transform: translateY(20px);
  }
  100% {
    opacity: 1;
    transform: translateY(0);
  }
}

/* Animation Classes */
.animate-bounce-gentle {
  animation: bounce-gentle 2s ease-in-out infinite;
}

.animate-pulse-slow {
  animation: pulse-slow 2s ease-in-out infinite;
}

.animate-spin-slow {
  animation: spin-slow 3s linear infinite;
}

.animate-loading-bar {
  animation: loading-bar 2s ease-in-out infinite;
}

.animate-fade-in-up {
  animation: fade-in-up 1s ease-out 0.5s both;
}

.animate-fade-in-up-delay {
  animation: fade-in-up 1s ease-out 1s both;
}

.animate-fade-in-up-delay-2 {
  animation: fade-in-up 1s ease-out 1.5s both;
}
</style>
