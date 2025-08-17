<template>
  <!-- Desktop Navigation -->
  <nav 
    :class="[
      'hidden md:block fixed top-6 left-1/2 transform -translate-x-1/2 z-[100000] transition-all duration-500 ease-out',
      'bg-white/5 backdrop-blur-xl shadow-2xl shadow-black/20',
      'border border-gold-500/30 rounded-full',
      scrolled ? 'bg-white/10 shadow-3xl scale-95' : 'bg-white/5'
    ]"
  >
    <div class="px-8 py-3">
      <div class="flex items-center space-x-8">
        <!-- Logo -->
        <div class="flex-shrink-0">
          <img class="h-14 w-auto logo-visible transition-transform duration-300 hover:scale-110 rounded-full" src="/images/logo2.png" alt="MIGBEN Logo" />
        </div>

        <!-- Desktop Navigation - Centered -->
        <div class="flex items-center space-x-6">
          <a
            v-for="item in navigation"
            :key="item.name"
            :href="item.href"
            @click="scrollToSection(item.href)"
            :class="[
              'px-3 py-2 text-sm font-medium transition-all duration-300 relative group whitespace-nowrap',
              activeSection === item.href ? 'text-gold-400' : 'text-white/90 hover:text-gold-400'
            ]"
          >
            {{ item.name }}
            <span 
              :class="[
                'absolute bottom-1 left-0 h-0.5 bg-gold-gradient transition-all duration-300 rounded-full',
                activeSection === item.href ? 'w-full' : 'w-0 group-hover:w-full'
              ]"
            ></span>
          </a>
        </div>

        <!-- Contact Button -->
        <div>
          <button
            @click="scrollToSection('#contact')"
            class="bg-gold-gradient text-primary-900 px-4 py-2 rounded-full text-xs font-semibold hover:shadow-lg transform hover:scale-105 transition-all duration-300 whitespace-nowrap"
          >
            Get Quote
          </button>
        </div>
      </div>
    </div>
  </nav>



  <!-- Mobile Menu Button -->
  <div class="md:hidden fixed top-8 right-6 z-[100001]">
    <button
      @click="toggleMobileMenu"
      class="text-white/90 hover:text-gold-400 p-3 rounded-full transition-all duration-300 hover:bg-white/10 bg-white/5 backdrop-blur-sm border border-gold-500/30 shadow-lg"
    >
      <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path v-if="!mobileMenuOpen" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
        <path v-else stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
      </svg>
    </button>
  </div>

    <!-- Mobile Navigation -->
    <div v-if="mobileMenuOpen" class="fixed inset-0 top-0 left-0 right-0 bottom-0 md:hidden bg-black/70 backdrop-blur-md z-[99999]">
      <div class="absolute top-16 left-1/2 transform -translate-x-1/2 w-[96vw] max-w-[500px] bg-gradient-to-br from-primary-800/98 to-primary-900/98 border-2 border-gold-500/50 rounded-3xl shadow-2xl overflow-hidden">
        <!-- Mobile Menu Header -->
        <div class="flex items-center justify-between p-4 bg-gradient-to-r from-primary-700/90 to-primary-800/90 border-b-2 border-gold-500/30">
          <div class="flex items-center space-x-3">
            <img class="h-10 w-auto rounded-full ring-2 ring-gold-500/50" src="/images/logo2.png" alt="MIGBEN Logo" />
            <div class="flex flex-col">
              <span class="text-white font-bold text-base">MIGBEN</span>
              <span class="text-gold-400 text-xs">LOGISTICS & CONSULTANCY</span>
            </div>
          </div>
          
        </div>
        
        <!-- Mobile Menu Items -->
        <div class="p-4 space-y-3">
          <a
            v-for="item in navigation"
            :key="item.name"
            :href="item.href"
            @click="scrollToSection(item.href); toggleMobileMenu()"
            :class="[
              'block px-4 py-4 text-lg font-bold transition-all duration-300 rounded-2xl hover:bg-white/25 border-2 border-transparent hover:border-gold-500/60 hover:scale-105 text-center',
              activeSection === item.href ? 'text-gold-400 bg-white/30 border-gold-500/60 shadow-xl shadow-gold-500/30' : 'text-white hover:text-gold-400'
            ]"
          >
            {{ item.name }}
          </a>
          
          <!-- Mobile CTA Section -->
          <div class="pt-4 border-t-2 border-gold-500/30">
            <button
              @click="scrollToSection('#contact'); toggleMobileMenu()"
              class="w-full bg-gold-gradient text-primary-900 px-6 py-4 rounded-2xl text-lg font-bold hover:shadow-2xl transform hover:scale-105 transition-all duration-300 shadow-xl"
            >
              Get Quote
            </button>
          </div>
        </div>
      </div>
    </div>
</template>

<script setup lang="ts">
import { ref, onMounted, onUnmounted } from 'vue'

const mobileMenuOpen = ref(false)
const scrolled = ref(false)
const activeSection = ref('#home')

const navigation = [
  { name: 'Home', href: '#home' },
  { name: 'About', href: '#about' },
  { name: 'Services', href: '#services' },
  { name: 'Products', href: '#products' },
  { name: 'Partners', href: '#partners' },
  { name: 'Contact', href: '#contact' },
]

const toggleMobileMenu = () => {
  mobileMenuOpen.value = !mobileMenuOpen.value
  
  // Prevent body scroll when mobile menu is open
  if (mobileMenuOpen.value) {
    document.body.style.overflow = 'hidden'
  } else {
    document.body.style.overflow = ''
  }
}

const scrollToSection = (elementId: string) => {
  const element = document.querySelector(elementId)
  if (element) {
    element.scrollIntoView({ behavior: 'smooth' })
  }
}

const updateActiveSection = () => {
  const scrollPosition = window.scrollY + 100 // Offset for better detection
  
  // Check each section to see which one is currently in view
  for (const item of navigation) {
    const element = document.querySelector(item.href) as HTMLElement
    if (element) {
      const elementTop = element.offsetTop
      const elementBottom = elementTop + element.offsetHeight
      
      if (scrollPosition >= elementTop && scrollPosition < elementBottom) {
        activeSection.value = item.href
        break
      }
    }
  }
  
  // Default to home if we're at the top
  if (window.scrollY < 100) {
    activeSection.value = '#home'
  }
}

const handleScroll = () => {
  scrolled.value = window.scrollY > 50
  updateActiveSection()
}

onMounted(() => {
  window.addEventListener('scroll', handleScroll, { passive: true })
  // Initial check
  updateActiveSection()
})

onUnmounted(() => {
  window.removeEventListener('scroll', handleScroll)
})
</script>
