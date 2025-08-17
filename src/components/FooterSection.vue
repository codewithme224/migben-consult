<template>
  <footer class="bg-primary-900 text-white">
    <!-- Main Footer -->
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-12">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
        <!-- Company Info -->
        <div class="lg:col-span-2">
          <div class="flex items-center mb-6">
            <img src="/images/logo3.png" alt="MIGBEN Logo" class="h-12 w-auto mr-4" />
            <div>
              <h3 class="text-xl font-bold">MIGBEN</h3>
              <p class="text-gold-400 text-sm">Logistics & Consultancy</p>
            </div>
          </div>
          <p class="text-gray-300 mb-6 max-w-md leading-relaxed">
            Global energy and commodity trading house specializing in structured procurement 
            and strategic distribution of refined fuels across international markets.
          </p>
          <div class="flex space-x-4">
            <a href="mailto:migbenconsultancy@gmail.com" class="w-10 h-10 bg-gold-gradient rounded-full flex items-center justify-center hover:scale-110 transition-transform">
              <svg class="w-5 h-5 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                <path d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z"/>
                <path d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z"/>
              </svg>
            </a>
            <a href="tel:+27737567328" class="w-10 h-10 bg-gold-gradient rounded-full flex items-center justify-center hover:scale-110 transition-transform">
              <svg class="w-5 h-5 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                <path d="M2 3a1 1 0 011-1h2.153a1 1 0 01.986.836l.74 4.435a1 1 0 01-.54 1.06l-1.548.773a11.037 11.037 0 006.105 6.105l.774-1.548a1 1 0 011.059-.54l4.435.74a1 1 0 01.836.986V17a1 1 0 01-1 1h-2C7.82 18 2 12.18 2 5V3z"/>
              </svg>
            </a>
            <a href="https://wa.me/27737567328" target="_blank" class="w-10 h-10 bg-gold-gradient rounded-full flex items-center justify-center hover:scale-110 transition-transform">
              <svg class="w-5 h-5 text-primary-900" fill="currentColor" viewBox="0 0 24 24">
                <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893A11.821 11.821 0 0020.885 3.488"/>
              </svg>
            </a>
          </div>
        </div>

        <!-- Quick Links -->
        <div>
          <h4 class="text-lg font-semibold text-gold-400 mb-4">Quick Links</h4>
          <ul class="space-y-2">
            <li>
              <a href="#home" @click="scrollToSection('#home')" class="text-gray-300 hover:text-gold-400 transition-colors">
                Home
              </a>
            </li>
            <li>
              <a href="#about" @click="scrollToSection('#about')" class="text-gray-300 hover:text-gold-400 transition-colors">
                About Us
              </a>
            </li>
            <li>
              <a href="#services" @click="scrollToSection('#services')" class="text-gray-300 hover:text-gold-400 transition-colors">
                Services
              </a>
            </li>
            <li>
              <a href="#products" @click="scrollToSection('#products')" class="text-gray-300 hover:text-gold-400 transition-colors">
                Products
              </a>
            </li>
            <li>
              <a href="#contact" @click="scrollToSection('#contact')" class="text-gray-300 hover:text-gold-400 transition-colors">
                Contact
              </a>
            </li>
          </ul>
        </div>

        <!-- Services -->
        <div>
          <h4 class="text-lg font-semibold text-gold-400 mb-4">Our Services</h4>
          <ul class="space-y-2">
            <li class="text-gray-300">Energy Trading</li>
            <li class="text-gray-300">Logistics Solutions</li>
            <li class="text-gray-300">Agricultural Commodities</li>
            <li class="text-gray-300">Business Consultancy</li>
            <li class="text-gray-300">Import & Export</li>
            <li class="text-gray-300">Transportation</li>
          </ul>
        </div>
      </div>

      <!-- Offices -->
      <div class="mt-12 pt-8 border-t border-primary-700">
        <h4 class="text-lg font-semibold text-gold-400 mb-6 text-center">Our Offices</h4>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
          <div class="bg-primary-800 rounded-lg p-6">
            <h5 class="font-semibold text-white mb-2">South Africa Office</h5>
            <p class="text-gray-300 text-sm mb-2">93 Willow way , Penhill Estate , Cape Town , Western Cape, South Africa</p>
            <p class="text-gold-400 text-sm">+27 639912356</p>
          </div>
          <div class="bg-primary-800 rounded-lg p-6">
            <h5 class="font-semibold text-white mb-2">Ghana Office</h5>
            <p class="text-gray-300 text-sm mb-2">Abelenkpe Taxi Rank, Alhaji Sulley Street, Accra, Ghana</p>
            <p class="text-gold-400 text-sm">+233 545 741 449</p>
          </div>
        </div>
      </div>
    </div>

    <!-- Bottom Footer -->
    <div class="border-t border-primary-700">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-6">
        <div class="flex flex-col md:flex-row justify-between items-center">
          <p class="text-gray-300 text-sm">
            © {{ currentYear }} MIGBEN Logistics & Consultancy. All rights reserved.
          </p>
          <div class="flex space-x-6 mt-4 md:mt-0">
            <a href="#" class="text-gray-300 hover:text-gold-400 text-sm transition-colors">
              Privacy Policy
            </a>
            <a href="#" class="text-gray-300 hover:text-gold-400 text-sm transition-colors">
              Terms of Service
            </a>
            <a href="#" class="text-gray-300 hover:text-gold-400 text-sm transition-colors">
              Cookie Policy
            </a>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script setup lang="ts">
import { computed } from 'vue'

const currentYear = computed(() => new Date().getFullYear())

const scrollToSection = (elementId: string) => {
  const element = document.querySelector(elementId)
  if (element) {
    element.scrollIntoView({ behavior: 'smooth' })
  }
}
</script>
