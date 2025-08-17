<template>
  <section id="home" class="relative min-h-screen flex items-center justify-center overflow-hidden bg-primary-900">

    <!-- Animated Background Elements -->
    <div class="absolute inset-0 z-10">
      <div class="absolute top-20 left-10 w-20 h-20 bg-gold-400/20 rounded-full animate-float"></div>
      <div class="absolute top-40 right-20 w-16 h-16 bg-primary-400/20 rounded-full animate-float" style="animation-delay: 2s;"></div>
      <div class="absolute bottom-40 left-20 w-12 h-12 bg-gold-300/20 rounded-full animate-float" style="animation-delay: 4s;"></div>
    </div>

    <!-- Content -->
    <div class="relative z-20 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center mt-10">
      <div class="animate-fade-in">
        <!-- Company Logo -->
        <!-- <div class="mb-8">
          <img 
            src="/images/logo.jpeg" 
            alt="MIGBEN Logo" 
            class="mx-auto h-24 w-auto md:h-32 animate-slide-up"
          />
        </div> -->

        <!-- Main Heading -->
        <h1 class="text-4xl md:text-6xl lg:text-7xl font-bold text-white mb-6 animate-slide-up mt-5">
          <span class="block">MIGBEN</span>
          <span class="block bg-gold-gradient bg-clip-text text-transparent">
            LOGISTICS & CONSULTANCY
          </span>
        </h1>

        <!-- Subtitle -->
        <p class="text-xl md:text-2xl text-gray-200 mb-8 max-w-3xl mx-auto leading-relaxed animate-slide-up" style="animation-delay: 0.2s;">
          Global energy and commodity trading house specializing in structured procurement and strategic distribution of refined fuels
        </p>

        <!-- Key Services Pills -->
        <div class="flex flex-wrap justify-center gap-4 mb-10 animate-slide-up" style="animation-delay: 0.4s;">
          <span class="bg-white/10 backdrop-blur-sm text-white px-4 py-2 rounded-full text-sm font-medium border border-white/20">
            Energy Trading
          </span>
          <span class="bg-white/10 backdrop-blur-sm text-white px-4 py-2 rounded-full text-sm font-medium border border-white/20">
            Logistics Solutions
          </span>
          <span class="bg-white/10 backdrop-blur-sm text-white px-4 py-2 rounded-full text-sm font-medium border border-white/20">
            Agricultural Commodities
          </span>
          <span class="bg-white/10 backdrop-blur-sm text-white px-4 py-2 rounded-full text-sm font-medium border border-white/20">
            Business Consultancy
          </span>
        </div>

        <!-- CTA Buttons -->
        <div class="flex flex-col sm:flex-row gap-4 justify-center animate-slide-up" style="animation-delay: 0.6s;">
          <button
            @click="scrollToSection('#services')"
            class="bg-gold-gradient text-primary-900 px-8 py-4 rounded-full text-lg font-semibold hover:shadow-2xl transform hover:scale-105 transition-all duration-300"
          >
            Explore Our Services
          </button>
          <button
            @click="scrollToSection('#contact')"
            class="border-2 border-white text-white px-8 py-4 rounded-full text-lg font-semibold hover:bg-white hover:text-gray-800 transition-all duration-300"
          >
            Get In Touch
          </button>
        </div>

        <!-- Stats Section -->
        <div class="mt-16 grid grid-cols-1 md:grid-cols-3 gap-8 max-w-4xl mx-auto animate-slide-up" style="animation-delay: 0.8s;">
          <div class="bg-white/10 backdrop-blur-sm rounded-xl p-6 border border-white/20">
            <div class="text-3xl font-bold text-gold-400 mb-2">Global</div>
            <div class="text-white text-sm">Trading Network</div>
          </div>
          <div class="bg-white/10 backdrop-blur-sm rounded-xl p-6 border border-white/20">
            <div class="text-3xl font-bold text-gold-400 mb-2">24/7</div>
            <div class="text-white text-sm">Support Services</div>
          </div>
          <div class="bg-white/10 backdrop-blur-sm rounded-xl p-6 border border-white/20">
            <div class="text-3xl font-bold text-gold-400 mb-2">Expert</div>
            <div class="text-white text-sm">Consultancy Team</div>
          </div>
        </div>
      </div>
    </div>

    <!-- Scroll Indicator -->
    <div class="absolute bottom-8 left-1/2 transform -translate-x-1/2 z-20 animate-bounce">
      <div class="w-6 h-10 border-2 border-white/50 rounded-full flex justify-center">
        <div class="w-1 h-3 bg-white/70 rounded-full mt-2 animate-pulse"></div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
const scrollToSection = (elementId: string) => {
  const element = document.querySelector(elementId)
  if (element) {
    element.scrollIntoView({ behavior: 'smooth' })
  }
}
</script>
