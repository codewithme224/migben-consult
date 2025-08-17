<template>
  <section id="services" class="py-20 bg-primary-900">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <!-- Section Header -->
      <div class="text-center mb-16">
        <h2 class="text-4xl md:text-5xl font-bold text-white mb-6">
          Our <span class="bg-gold-gradient bg-clip-text text-transparent">Services</span>
        </h2>
        <p class="text-lg text-gray-200 max-w-3xl mx-auto leading-relaxed">
          Comprehensive solutions across energy trading, logistics, and business consultancy
        </p>
      </div>

      <!-- Services Grid -->
      <div class="grid grid-cols-1 lg:grid-cols-2 gap-8 mb-16">
        <!-- Energy Trading -->
        <div class="group bg-gradient-to-br from-primary-700 to-primary-800 rounded-2xl shadow-2xl hover:shadow-3xl transition-all duration-500 transform hover:-translate-y-3 overflow-hidden border border-gold-500/20">
          <div class="relative h-64">
            <img 
              src="/images/product.jpeg" 
              alt="Energy Trading" 
              class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500"
            />
            <!-- Glassmorphism Overlay -->
            <div class="absolute inset-0 bg-gradient-to-t from-primary-900/90 to-primary-900/30"></div>
            <div class="absolute inset-0 backdrop-blur-[2px] bg-white/5"></div>
            <div class="absolute inset-0 bg-gradient-to-br from-white/10 via-transparent to-black/20"></div>
            
            <div class="absolute inset-0 flex items-center justify-center">
              <div class="text-center text-white">
                <div class="w-16 h-16 mx-auto mb-4 bg-gold-gradient rounded-full flex items-center justify-center shadow-lg backdrop-blur-sm border border-white/20">
                  <svg class="w-8 h-8 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                    <path d="M13 6a3 3 0 11-6 0 3 3 0 016 0zM18 8a2 2 0 11-4 0 2 2 0 014 0zM14 15a4 4 0 00-8 0v3h8v-3z"/>
                  </svg>
                </div>
                <div class="bg-white/10 backdrop-blur-md rounded-xl p-4 border border-white/20 shadow-2xl">
                  <div class="inline-block relative">
                    <h3 class="text-3xl font-bold text-white mb-2 drop-shadow-lg">
                      Energy <span class="bg-gold-gradient bg-clip-text text-transparent">Trading</span>
                    </h3>
                    <div class="absolute -bottom-1 left-0 w-16 h-1 bg-gold-gradient rounded-full"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="p-8">
            <p class="text-gray-200 mb-6 leading-relaxed">
              Global energy and commodity trading house specializing in structured procurement and strategic distribution of refined fuels.
            </p>
            <div class="space-y-3">
              <div class="flex items-center p-3 bg-primary-600/30 rounded-lg hover:bg-primary-600/50 transition-colors duration-300">
                <div class="w-3 h-3 bg-gold-gradient rounded-full mr-3 flex-shrink-0"></div>
                <span class="text-gray-200">Diesel (EN590)</span>
              </div>
              <div class="flex items-center p-3 bg-primary-600/30 rounded-lg hover:bg-primary-600/50 transition-colors duration-300">
                <div class="w-3 h-3 bg-gold-gradient rounded-full mr-3 flex-shrink-0"></div>
                <span class="text-gray-200">Jet A1 Aviation Fuel</span>
              </div>
              <div class="flex items-center p-3 bg-primary-600/30 rounded-lg hover:bg-primary-600/50 transition-colors duration-300">
                <div class="w-3 h-3 bg-gold-gradient rounded-full mr-3 flex-shrink-0"></div>
                <span class="text-gray-200">Gas Oil & Marine Fuel</span>
              </div>
            </div>
          </div>
        </div>

        <!-- Logistics -->
        <div class="group bg-gradient-to-br from-primary-700 to-primary-800 rounded-2xl shadow-2xl hover:shadow-3xl transition-all duration-500 transform hover:-translate-y-3 overflow-hidden border border-gold-500/20">
          <div class="relative h-64">
            <img 
              src="/images/services.jpeg" 
              alt="Logistics Services" 
              class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500"
            />
            <!-- Glassmorphism Overlay -->
            <div class="absolute inset-0 bg-gradient-to-t from-primary-900/90 to-primary-900/30"></div>
            <div class="absolute inset-0 backdrop-blur-[2px] bg-white/5"></div>
            <div class="absolute inset-0 bg-gradient-to-br from-white/10 via-transparent to-black/20"></div>
            
            <div class="absolute inset-0 flex items-center justify-center">
              <div class="text-center text-white">
                <div class="w-16 h-16 mx-auto mb-4 bg-gold-gradient rounded-full flex items-center justify-center shadow-lg backdrop-blur-sm border border-white/20">
                  <svg class="w-8 h-8 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                    <path d="M8 16.5a1.5 1.5 0 11-3 0 1.5 1.5 0 013 0zM15 16.5a1.5 1.5 0 11-3 0 1.5 1.5 0 013 0z"/>
                    <path d="M3 4a1 1 0 00-1 1v10a1 1 0 001 1h1.05a2.5 2.5 0 014.9 0H10a1 1 0 001-1V5a1 1 0 00-1-1H3z"/>
                  </svg>
                </div>
                <div class="bg-white/10 backdrop-blur-md rounded-xl p-4 border border-white/20 shadow-2xl">
                  <div class="inline-block relative">
                    <h3 class="text-3xl font-bold text-white mb-2 drop-shadow-lg">
                      Logistics <span class="bg-gold-gradient bg-clip-text text-transparent">Solutions</span>
                    </h3>
                    <div class="absolute -bottom-1 left-0 w-16 h-1 bg-gold-gradient rounded-full"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="p-8">
            <p class="text-gray-200 mb-6 leading-relaxed">
              Comprehensive logistics services bridging upstream producers and downstream buyers across international markets.
            </p>
            <div class="space-y-3">
              <div class="flex items-center p-3 bg-primary-600/30 rounded-lg hover:bg-primary-600/50 transition-colors duration-300">
                <div class="w-3 h-3 bg-gold-gradient rounded-full mr-3 flex-shrink-0"></div>
                <span class="text-gray-200">Import & Export (Ocean and Air Freight)</span>
              </div>
              <div class="flex items-center p-3 bg-primary-600/30 rounded-lg hover:bg-primary-600/50 transition-colors duration-300">
                <div class="w-3 h-3 bg-gold-gradient rounded-full mr-3 flex-shrink-0"></div>
                <span class="text-gray-200">Transportation & Distribution</span>
              </div>
              <div class="flex items-center p-3 bg-primary-600/30 rounded-lg hover:bg-primary-600/50 transition-colors duration-300">
                <div class="w-3 h-3 bg-gold-gradient rounded-full mr-3 flex-shrink-0"></div>
                <span class="text-gray-200">Supply Chain Management</span>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Additional Services -->
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
        <!-- Business Support -->
        <div class="bg-gradient-to-br from-primary-600 to-primary-700 backdrop-blur-sm rounded-xl p-6 border border-gold-500/20 hover:shadow-2xl hover:border-gold-500/40 transition-all duration-300 transform hover:-translate-y-1">
          <div class="w-12 h-12 bg-gold-gradient rounded-lg flex items-center justify-center mb-4 shadow-lg">
            <svg class="w-6 h-6 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
              <path d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"/>
            </svg>
          </div>
          <h4 class="text-lg font-semibold text-white mb-3">Business Support</h4>
          <ul class="text-sm text-gray-200 space-y-2">
            <li class="flex items-center">
              <div class="w-1.5 h-1.5 bg-gold-400 rounded-full mr-2"></div>
              Advisory & Consultancy
            </li>
            <li class="flex items-center">
              <div class="w-1.5 h-1.5 bg-gold-400 rounded-full mr-2"></div>
              Financial Management
            </li>
            <li class="flex items-center">
              <div class="w-1.5 h-1.5 bg-gold-400 rounded-full mr-2"></div>
              Production Management
            </li>
          </ul>
        </div>

        <!-- Energy Solutions -->
        <div class="bg-gradient-to-br from-primary-600 to-primary-700 backdrop-blur-sm rounded-xl p-6 border border-gold-500/20 hover:shadow-2xl hover:border-gold-500/40 transition-all duration-300 transform hover:-translate-y-1">
          <div class="w-12 h-12 bg-gold-gradient rounded-lg flex items-center justify-center mb-4 shadow-lg">
            <svg class="w-6 h-6 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
              <path d="M17.293 13.293A8 8 0 016.707 2.707a8.001 8.001 0 1010.586 10.586z"/>
            </svg>
          </div>
          <h4 class="text-lg font-semibold text-white mb-3">Energy Solutions</h4>
          <ul class="text-sm text-gray-200 space-y-2">
            <li class="flex items-center">
              <div class="w-1.5 h-1.5 bg-gold-400 rounded-full mr-2"></div>
              Rooftop Solar Power
            </li>
            <li class="flex items-center">
              <div class="w-1.5 h-1.5 bg-gold-400 rounded-full mr-2"></div>
              Solar Farms
            </li>
            <li class="flex items-center">
              <div class="w-1.5 h-1.5 bg-gold-400 rounded-full mr-2"></div>
              Sustainable Energy
            </li>
          </ul>
        </div>

        <!-- Training -->
        <div class="bg-gradient-to-br from-primary-600 to-primary-700 backdrop-blur-sm rounded-xl p-6 border border-gold-500/20 hover:shadow-2xl hover:border-gold-500/40 transition-all duration-300 transform hover:-translate-y-1">
          <div class="w-12 h-12 bg-gold-gradient rounded-lg flex items-center justify-center mb-4 shadow-lg">
            <svg class="w-6 h-6 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
              <path d="M10.394 2.08a1 1 0 00-.788 0l-7 3a1 1 0 000 1.84L5.25 8.051a.999.999 0 01.356-.257l4-1.714a1 1 0 11.788 1.838L7.667 9.088l1.94.831a1 1 0 00.787 0l7-3a1 1 0 000-1.838l-7-3zM3.31 9.397L5 10.12v4.102a8.969 8.969 0 00-1.05-.174 1 1 0 01-.89-.89 11.115 11.115 0 01.25-3.762zM9.3 16.573A9.026 9.026 0 007 14.935v-3.957l1.818.78a3 3 0 002.364 0l5.508-2.361a11.026 11.026 0 01.25 3.762 1 1 0 01-.89.89 8.968 8.968 0 00-5.35 2.524 1 1 0 01-1.4 0zM6 18a1 1 0 001-1v-2.065a8.935 8.935 0 00-2-.712V17a1 1 0 001 1z"/>
            </svg>
          </div>
          <h4 class="text-lg font-semibold text-white mb-3">Training</h4>
          <ul class="text-sm text-gray-200 space-y-2">
            <li class="flex items-center">
              <div class="w-1.5 h-1.5 bg-gold-400 rounded-full mr-2"></div>
              Industry Training
            </li>
            <li class="flex items-center">
              <div class="w-1.5 h-1.5 bg-gold-400 rounded-full mr-2"></div>
              Capacity Building
            </li>
            <li class="flex items-center">
              <div class="w-1.5 h-1.5 bg-gold-400 rounded-full mr-2"></div>
              Skills Development
            </li>
          </ul>
        </div>

        <!-- Management -->
        <div class="bg-gradient-to-br from-primary-600 to-primary-700 backdrop-blur-sm rounded-xl p-6 border border-gold-500/20 hover:shadow-2xl hover:border-gold-500/40 transition-all duration-300 transform hover:-translate-y-1">
          <div class="w-12 h-12 bg-gold-gradient rounded-lg flex items-center justify-center mb-4 shadow-lg">
            <svg class="w-6 h-6 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
              <path fill-rule="evenodd" d="M6 6V5a3 3 0 013-3h2a3 3 0 013 3v1h2a2 2 0 012 2v3.57A22.952 22.952 0 0110 13a22.95 22.95 0 01-8-1.43V8a2 2 0 012-2h2zm2-1a1 1 0 011-1h2a1 1 0 011 1v1H8V5zm1 5a1 1 0 011-1h.01a1 1 0 110 2H10a1 1 0 01-1-1z" clip-rule="evenodd"/>
              <path d="M2 13.692V16a2 2 0 002 2h12a2 2 0 002-2v-2.308A24.974 24.974 0 0110 15c-2.796 0-5.487-.46-8-1.308z"/>
            </svg>
          </div>
          <h4 class="text-lg font-semibold text-white mb-3">Management</h4>
          <ul class="text-sm text-gray-200 space-y-2">
            <li class="flex items-center">
              <div class="w-1.5 h-1.5 bg-gold-400 rounded-full mr-2"></div>
              Productivity Management
            </li>
            <li class="flex items-center">
              <div class="w-1.5 h-1.5 bg-gold-400 rounded-full mr-2"></div>
              Operations Optimization
            </li>
            <li class="flex items-center">
              <div class="w-1.5 h-1.5 bg-gold-400 rounded-full mr-2"></div>
              Strategic Planning
            </li>
          </ul>
        </div>
      </div>

      <!-- CTA Section -->
      <div class="mt-16 text-center">
        <div class="bg-dark-gradient rounded-2xl p-8 md:p-12">
          <h3 class="text-3xl font-bold text-white mb-4">
            Ready to Transform Your Business?
          </h3>
          <p class="text-gray-200 mb-8 max-w-2xl mx-auto">
            Partner with us for reliable, efficient, and innovative solutions tailored to your energy and logistics needs.
          </p>
          <button
            @click="scrollToSection('#contact')"
            class="bg-gold-gradient text-primary-900 px-8 py-4 rounded-full text-lg font-semibold hover:shadow-xl transform hover:scale-105 transition-all duration-300"
          >
            Start Your Journey
          </button>
        </div>
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
