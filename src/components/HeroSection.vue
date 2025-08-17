<template>
  <section id="home" class="flex overflow-hidden relative justify-center items-center min-h-screen bg-primary-900">

    <!-- Animated Background Elements -->
    <div class="absolute inset-0 z-10">
      <div class="absolute left-10 top-20 w-20 h-20 rounded-full bg-gold-400/20 animate-float"></div>
      <div class="absolute right-20 top-40 w-16 h-16 rounded-full bg-primary-400/20 animate-float" style="animation-delay: 2s;"></div>
      <div class="absolute left-20 bottom-40 w-12 h-12 rounded-full bg-gold-300/20 animate-float" style="animation-delay: 4s;"></div>
    </div>

    <!-- Content -->
    <div class="relative z-20 px-4 mx-auto mt-10 max-w-7xl text-center sm:px-6 lg:px-8">
      <div class="animate-fade-in">
        <!-- Company Logo -->
        <!-- <div class="mb-8">
          <img 
            src="/images/logo.jpeg" 
            alt="MIGBEN Logo" 
            class="mx-auto w-auto h-24 md:h-32 animate-slide-up"
          />
        </div> -->

        <!-- Main Heading -->
        <h1 class="mt-10 mb-6 text-4xl font-bold text-white md:text-6xl lg:text-7xl animate-slide-up">
          <span class="block">MIGBEN</span>
          <span class="block text-transparent bg-clip-text bg-gold-gradient">
            LOGISTICS & CONSULTANCY
          </span>
        </h1>

        <!-- Subtitle -->
        <p class="mx-auto mb-8 max-w-3xl text-xl leading-relaxed text-gray-200 md:text-2xl animate-slide-up" style="animation-delay: 0.2s;">
          Global energy and commodity trading house specializing in structured procurement and strategic distribution of refined fuels
        </p>

        <!-- Key Services Pills -->
        <div class="flex flex-wrap gap-4 justify-center mb-10 animate-slide-up" style="animation-delay: 0.4s;">
          <span class="px-4 py-2 text-sm font-medium text-white rounded-full border backdrop-blur-sm bg-white/10 border-white/20">
            Energy Trading
          </span>
          <span class="px-4 py-2 text-sm font-medium text-white rounded-full border backdrop-blur-sm bg-white/10 border-white/20">
            Logistics Solutions
          </span>
          <span class="px-4 py-2 text-sm font-medium text-white rounded-full border backdrop-blur-sm bg-white/10 border-white/20">
            Agricultural Commodities
          </span>
          <span class="px-4 py-2 text-sm font-medium text-white rounded-full border backdrop-blur-sm bg-white/10 border-white/20">
            Business Consultancy
          </span>
        </div>

        <!-- CTA Buttons -->
        <div class="flex flex-col gap-4 justify-center sm:flex-row animate-slide-up" style="animation-delay: 0.6s;">
          <button
            @click="scrollToSection('#services')"
            class="px-8 py-4 text-lg font-semibold rounded-full transition-all duration-300 transform bg-gold-gradient text-primary-900 hover:shadow-2xl hover:scale-105"
          >
            Explore Our Services
          </button>
          <button
            @click="scrollToSection('#contact')"
            class="px-8 py-4 text-lg font-semibold text-white rounded-full border-2 border-white transition-all duration-300 hover:bg-white hover:text-gray-800"
          >
            Get In Touch
          </button>
        </div>

        <!-- Stats Section -->
        <div class="grid grid-cols-1 gap-8 mx-auto mt-16 max-w-4xl md:grid-cols-3 animate-slide-up" style="animation-delay: 0.8s;">
          <div class="p-6 rounded-xl border backdrop-blur-sm bg-white/10 border-white/20">
            <div class="mb-2 text-3xl font-bold text-gold-400">Global</div>
            <div class="text-sm text-white">Trading Network</div>
          </div>
          <div class="p-6 rounded-xl border backdrop-blur-sm bg-white/10 border-white/20">
            <div class="mb-2 text-3xl font-bold text-gold-400">24/7</div>
            <div class="text-sm text-white">Support Services</div>
          </div>
          <div class="p-6 rounded-xl border backdrop-blur-sm bg-white/10 border-white/20">
            <div class="mb-2 text-3xl font-bold text-gold-400">Expert</div>
            <div class="text-sm text-white">Consultancy Team</div>
          </div>
        </div>
      </div>
    </div>

    <!-- Scroll Indicator -->
    <div class="absolute bottom-8 left-1/2 z-20 animate-bounce transform -translate-x-1/2">
      <div class="flex justify-center w-6 h-10 rounded-full border-2 border-white/50">
        <div class="mt-2 w-1 h-3 rounded-full animate-pulse bg-white/70"></div>
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
