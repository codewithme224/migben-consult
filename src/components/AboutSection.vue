<template>
  <section id="about" class="py-20 bg-primary-800">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <!-- Section Header -->
      <div class="text-center mb-16">
        <h2 class="text-4xl md:text-5xl font-bold text-white mb-6">
          About <span class="bg-gold-gradient bg-clip-text text-transparent">MIGBEN</span>
        </h2>
        <p class="text-lg text-gray-200 max-w-3xl mx-auto leading-relaxed">
          Leading the way in global energy trading and logistics solutions
        </p>
      </div>

      <!-- Company Overview -->
      <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center mb-20">
        <div class="order-2 lg:order-1">
          <h3 class="text-3xl font-bold text-white mb-6">Our Mission</h3>
          <p class="text-gray-200 mb-6 leading-relaxed">
            We are a global energy and commodity trading house, specializing in the structured 
            procurement and strategic distribution of refined fuels. Through trade-secure 
            instruments, regulatory-aligned logistics, and an integrity-driven supply chain, 
            we bridge upstream producers and downstream buyers across international markets.
          </p>
          <p class="text-gray-200 mb-8 leading-relaxed">
            Our comprehensive approach combines deep market expertise with innovative solutions, 
            ensuring reliable, efficient, and sustainable energy trading operations worldwide.
          </p>
          
          <!-- Key Stats -->
          <div class="grid grid-cols-2 gap-6">
            <div class="bg-primary-700 rounded-lg p-4 text-center">
              <div class="text-2xl font-bold text-gold-400 mb-1">Global</div>
              <div class="text-sm text-gray-200">Market Reach</div>
            </div>
            <div class="bg-primary-700 rounded-lg p-4 text-center">
              <div class="text-2xl font-bold text-gold-400 mb-1">Expert</div>
              <div class="text-sm text-gray-200">Leadership Team</div>
            </div>
          </div>
        </div>
        
        <div class="order-1 lg:order-2">
          <div class="relative">
            <img 
              src="/images/about.jpeg" 
              alt="About MIGBEN" 
              class="w-full h-96 object-cover rounded-2xl shadow-2xl"
            />
            <div class="absolute inset-0 bg-gradient-to-t from-primary-900/20 to-transparent rounded-2xl"></div>
          </div>
        </div>
      </div>

      <!-- Leadership Team -->
      <div class="mb-16">
        <div class="text-center mb-16">
          <div class="inline-block relative">
            <h3 class="text-4xl md:text-5xl font-bold text-white mb-4">
              Our <span class="bg-gold-gradient bg-clip-text text-transparent">Leadership</span>
            </h3>
            <div class="absolute -bottom-2 left-1/2 transform -translate-x-1/2 w-24 h-1 bg-gold-gradient rounded-full"></div>
          </div>
          <p class="text-lg text-gray-200 max-w-2xl mx-auto mt-6">
            Meet the visionary leaders driving MIGBEN's success in global energy and commodity trading
          </p>
        </div>
        
        <div class="grid grid-cols-1 lg:grid-cols-3 gap-8 max-w-7xl mx-auto">
          <!-- CEO - Featured Card -->
          <div class="lg:col-span-3 mb-8">
            <div class="group bg-gradient-to-br from-primary-700 to-primary-800 rounded-3xl shadow-2xl hover:shadow-3xl transition-all duration-500 transform hover:-translate-y-3 overflow-hidden border border-gold-500/20">
              <div class="flex flex-col lg:flex-row">
                <!-- CEO Image -->
                <div class="lg:w-1/3 relative overflow-hidden">
                  <img 
                    src="/images/logo2.png" 
                    alt="CEO Kingsley Ofori Andoh" 
                    class="w-full h-80 lg:h-full object-cover group-hover:scale-105 transition-transform duration-500"
                  />
                  <div class="absolute inset-0 bg-gradient-to-r from-primary-900/40 to-transparent"></div>
                  <div class="absolute top-4 left-4">
                    <div class="bg-gold-gradient text-primary-900 px-3 py-1 rounded-full text-xs font-bold">
                      CEO
                    </div>
                  </div>
                </div>
                
                <!-- CEO Info -->
                <div class="lg:w-2/3 p-8 lg:p-12">
                  <div class="mb-6">
                    <h4 class="text-3xl lg:text-4xl font-bold text-white mb-2">Kingsley Ofori Andoh</h4>
                    <p class="text-gold-400 font-semibold text-lg mb-4">Chief Executive Officer</p>
                    <p class="text-gray-200 leading-relaxed">
                      Leading MIGBEN with strategic vision and deep industry expertise in global energy trading and logistics solutions.
                    </p>
                  </div>
                  
                  <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                    <div class="bg-primary-600/50 rounded-xl p-4 backdrop-blur-sm border border-gold-500/10">
                      <div class="flex items-center mb-2">
                        <div class="w-8 h-8 bg-gold-gradient rounded-full flex items-center justify-center mr-3">
                          <svg class="w-4 h-4 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                            <path d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z"/>
                            <path d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z"/>
                          </svg>
                        </div>
                        <span class="text-white font-medium">Email</span>
                      </div>
                      <p class="text-gray-300 text-sm">migbenconsultancy@gmail.com</p>
                    </div>
                    
                    <div class="bg-primary-600/50 rounded-xl p-4 backdrop-blur-sm border border-gold-500/10">
                      <div class="flex items-center mb-2">
                        <div class="w-8 h-8 bg-gold-gradient rounded-full flex items-center justify-center mr-3">
                          <svg class="w-4 h-4 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                            <path d="M2 3a1 1 0 011-1h2.153a1 1 0 01.986.836l.74 4.435a1 1 0 01-.54 1.06l-1.548.773a11.037 11.037 0 006.105 6.105l.774-1.548a1 1 0 011.059-.54l4.435.74a1 1 0 01.836.986V17a1 1 0 01-1 1h-2C7.82 18 2 12.18 2 5V3z"/>
                          </svg>
                        </div>
                        <span class="text-white font-medium">Phone</span>
                      </div>
                      <p class="text-gray-300 text-sm">+27 73 7567 328</p>
                    </div>
                    
                    <div class="md:col-span-2 bg-primary-600/50 rounded-xl p-4 backdrop-blur-sm border border-gold-500/10">
                      <div class="flex items-center mb-2">
                        <div class="w-8 h-8 bg-gold-gradient rounded-full flex items-center justify-center mr-3">
                          <svg class="w-4 h-4 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                            <path fill-rule="evenodd" d="M5.05 4.05a7 7 0 119.9 9.9L10 18.9l-4.95-4.95a7 7 0 010-9.9zM10 11a2 2 0 100-4 2 2 0 000 4z" clip-rule="evenodd"/>
                          </svg>
                        </div>
                        <span class="text-white font-medium">Location</span>
                      </div>
                      <p class="text-gray-300 text-sm">Willow Way 95, Penhill - Cape Town, Western Cape, South Africa</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- Director Cards -->
          <div class="lg:col-span-3">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
              <!-- Director 1 -->
              <div class="group bg-gradient-to-br from-primary-700 to-primary-800 rounded-2xl shadow-xl hover:shadow-2xl transition-all duration-300 transform hover:-translate-y-2 overflow-hidden border border-gold-500/20">
                <div class="relative">
                  <img 
                    src="/images/director2.jpeg" 
                    alt="Director Mignon Adine Dianne" 
                    class="w-full h-64 object-cover group-hover:scale-110 transition-transform duration-300"
                  />
                  <div class="absolute inset-0 bg-gradient-to-t from-primary-900/90 to-primary-900/20"></div>
                  <div class="absolute top-4 right-4">
                    <div class="bg-gold-gradient text-primary-900 px-3 py-1 rounded-full text-xs font-bold">
                      Director
                    </div>
                  </div>
                  <div class="absolute bottom-4 left-4 right-4">
                    <div class="bg-primary-900/80 backdrop-blur-sm rounded-xl p-4 border border-gold-500/30">
                      <h4 class="text-xl font-bold text-white mb-1 drop-shadow-lg">Mignon Adine Dianne</h4>
                      <p class="text-gold-400 font-semibold text-sm">Director</p>
                    </div>
                  </div>
                </div>
                
                <div class="p-6">
                  <div class="space-y-3">
                    <div class="flex items-center p-3 bg-primary-600/30 rounded-lg hover:bg-primary-600/50 transition-colors">
                      <div class="w-6 h-6 bg-gold-gradient rounded-full flex items-center justify-center mr-3 flex-shrink-0">
                        <svg class="w-3 h-3 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                          <path d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z"/>
                          <path d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z"/>
                        </svg>
                      </div>
                      <span class="text-gray-200 text-sm">migbenconsultancy@gmail.com</span>
                    </div>
                    
                    <div class="flex items-center p-3 bg-primary-600/30 rounded-lg hover:bg-primary-600/50 transition-colors">
                      <div class="w-6 h-6 bg-gold-gradient rounded-full flex items-center justify-center mr-3 flex-shrink-0">
                        <svg class="w-3 h-3 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                          <path d="M2 3a1 1 0 011-1h2.153a1 1 0 01.986.836l.74 4.435a1 1 0 01-.54 1.06l-1.548.773a11.037 11.037 0 006.105 6.105l.774-1.548a1 1 0 011.059-.54l4.435.74a1 1 0 01.836.986V17a1 1 0 01-1 1h-2C7.82 18 2 12.18 2 5V3z"/>
                        </svg>
                      </div>
                      <span class="text-gray-200 text-sm">+27 73 7567 328</span>
                    </div>
                    
                    <div class="flex items-center p-3 bg-primary-600/30 rounded-lg hover:bg-primary-600/50 transition-colors">
                      <div class="w-6 h-6 bg-gold-gradient rounded-full flex items-center justify-center mr-3 flex-shrink-0">
                        <svg class="w-3 h-3 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                          <path fill-rule="evenodd" d="M5.05 4.05a7 7 0 119.9 9.9L10 18.9l-4.95-4.95a7 7 0 010-9.9zM10 11a2 2 0 100-4 2 2 0 000 4z" clip-rule="evenodd"/>
                        </svg>
                      </div>
                      <span class="text-gray-200 text-sm">Cape Town, South Africa</span>
                    </div>
                  </div>
                </div>
              </div>

              <!-- Director 2 -->
              <div class="group bg-gradient-to-br from-primary-700 to-primary-800 rounded-2xl shadow-xl hover:shadow-2xl transition-all duration-300 transform hover:-translate-y-2 overflow-hidden border border-gold-500/20">
                <div class="relative">
                  <img 
                    src="/images/director.jpeg" 
                    alt="Director Robert Currie Opoku" 
                    class="w-full h-64 object-cover group-hover:scale-110 transition-transform duration-300"
                  />
                  <div class="absolute inset-0 bg-gradient-to-t from-primary-900/90 to-primary-900/20"></div>
                  <div class="absolute top-4 right-4">
                    <div class="bg-gold-gradient text-primary-900 px-3 py-1 rounded-full text-xs font-bold">
                      Director
                    </div>
                  </div>
                  <div class="absolute bottom-4 left-4 right-4">
                    <div class="bg-primary-900/80 backdrop-blur-sm rounded-xl p-4 border border-gold-500/30">
                      <h4 class="text-xl font-bold text-white mb-1 drop-shadow-lg">Robert Currie Opoku</h4>
                      <p class="text-gold-400 font-semibold text-sm">Director</p>
                    </div>
                  </div>
                </div>
                
                <div class="p-6">
                  <div class="space-y-3">
                    <div class="flex items-center p-3 bg-primary-600/30 rounded-lg hover:bg-primary-600/50 transition-colors">
                      <div class="w-6 h-6 bg-gold-gradient rounded-full flex items-center justify-center mr-3 flex-shrink-0">
                        <svg class="w-3 h-3 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                          <path d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z"/>
                          <path d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z"/>
                        </svg>
                      </div>
                      <span class="text-gray-200 text-sm">migbenconsultancy@gmail.com</span>
                    </div>
                    
                    <div class="flex items-center p-3 bg-primary-600/30 rounded-lg hover:bg-primary-600/50 transition-colors">
                      <div class="w-6 h-6 bg-gold-gradient rounded-full flex items-center justify-center mr-3 flex-shrink-0">
                        <svg class="w-3 h-3 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                          <path d="M2 3a1 1 0 011-1h2.153a1 1 0 01.986.836l.74 4.435a1 1 0 01-.54 1.06l-1.548.773a11.037 11.037 0 006.105 6.105l.774-1.548a1 1 0 011.059-.54l4.435.74a1 1 0 01.836.986V17a1 1 0 01-1 1h-2C7.82 18 2 12.18 2 5V3z"/>
                        </svg>
                      </div>
                      <span class="text-gray-200 text-sm">+233 545 741 449</span>
                    </div>
                    
                    <div class="flex items-center p-3 bg-primary-600/30 rounded-lg hover:bg-primary-600/50 transition-colors">
                      <div class="w-6 h-6 bg-gold-gradient rounded-full flex items-center justify-center mr-3 flex-shrink-0">
                        <svg class="w-3 h-3 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                          <path fill-rule="evenodd" d="M5.05 4.05a7 7 0 119.9 9.9L10 18.9l-4.95-4.95a7 7 0 010-9.9zM10 11a2 2 0 100-4 2 2 0 000 4z" clip-rule="evenodd"/>
                        </svg>
                      </div>
                      <span class="text-gray-200 text-sm">Accra, Ghana</span>
                    </div>
                  </div>
                </div>
              </div>
              
            </div>
          </div>
        </div>
      </div>

      <!-- Values Section -->
      <div class="bg-gradient-to-r from-primary-900 to-primary-800 rounded-3xl p-8 md:p-12">
        <div class="text-center mb-12">
          <h3 class="text-3xl font-bold text-white mb-4">Our Core Values</h3>
          <p class="text-gray-200 max-w-2xl mx-auto">
            The principles that guide our operations and define our commitment to excellence
          </p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
          <div class="text-center">
            <div class="w-16 h-16 bg-gold-gradient rounded-full flex items-center justify-center mx-auto mb-4">
              <svg class="w-8 h-8 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                <path fill-rule="evenodd" d="M6.267 3.455a3.066 3.066 0 001.745-.723 3.066 3.066 0 013.976 0 3.066 3.066 0 001.745.723 3.066 3.066 0 012.812 2.812c.051.643.304 1.254.723 1.745a3.066 3.066 0 010 3.976 3.066 3.066 0 00-.723 1.745 3.066 3.066 0 01-2.812 2.812 3.066 3.066 0 00-1.745.723 3.066 3.066 0 01-3.976 0 3.066 3.066 0 00-1.745-.723 3.066 3.066 0 01-2.812-2.812 3.066 3.066 0 00-.723-1.745 3.066 3.066 0 010-3.976 3.066 3.066 0 00.723-1.745 3.066 3.066 0 012.812-2.812zm7.44 5.252a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
              </svg>
            </div>
            <h4 class="text-xl font-bold text-white mb-2">Integrity</h4>
            <p class="text-gray-300">Transparent and ethical business practices in all our operations</p>
          </div>

          <div class="text-center">
            <div class="w-16 h-16 bg-gold-gradient rounded-full flex items-center justify-center mx-auto mb-4">
              <svg class="w-8 h-8 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/>
              </svg>
            </div>
            <h4 class="text-xl font-bold text-white mb-2">Excellence</h4>
            <p class="text-gray-300">Commitment to delivering superior quality in every service</p>
          </div>

          <div class="text-center">
            <div class="w-16 h-16 bg-gold-gradient rounded-full flex items-center justify-center mx-auto mb-4">
              <svg class="w-8 h-8 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                <path d="M13 6a3 3 0 11-6 0 3 3 0 016 0zM18 8a2 2 0 11-4 0 2 2 0 014 0zM14 15a4 4 0 00-8 0v3h8v-3z"/>
              </svg>
            </div>
            <h4 class="text-xl font-bold text-white mb-2">Innovation</h4>
            <p class="text-gray-300">Pioneering solutions that drive industry advancement</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
// Component logic here if needed
</script>
