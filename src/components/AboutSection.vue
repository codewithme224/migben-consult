<template>
  <section id="about" class="py-20 bg-primary-800">
    <div class="px-4 mx-auto max-w-7xl sm:px-6 lg:px-8">
      <!-- Section Header -->
      <div class="mb-16 text-center">
        <h2 class="mb-6 text-4xl font-bold text-white md:text-5xl">
          About <span class="text-transparent bg-clip-text bg-gold-gradient">MIGBEN</span>
        </h2>
        <p class="mx-auto max-w-3xl text-lg leading-relaxed text-gray-200">
          Leading the way in global energy trading and logistics solutions
        </p>
      </div>

      <!-- Company Overview -->
      <div class="grid grid-cols-1 gap-12 items-center mb-20 lg:grid-cols-2">
        <div class="order-2 lg:order-1">
          <h3 class="mb-6 text-3xl font-bold text-white">Our Mission</h3>
          <p class="mb-6 leading-relaxed text-gray-200">
            We are a global energy and commodity trading house, specializing in the structured 
            procurement and strategic distribution of refined fuels. Through trade-secure 
            instruments, regulatory-aligned logistics, and an integrity-driven supply chain, 
            we bridge upstream producers and downstream buyers across international markets.
          </p>
          <p class="mb-8 leading-relaxed text-gray-200">
            Our comprehensive approach combines deep market expertise with innovative solutions, 
            ensuring reliable, efficient, and sustainable energy trading operations worldwide.
          </p>
          
          <!-- Key Stats -->
          <div class="grid grid-cols-2 gap-6">
            <div class="p-4 text-center rounded-lg bg-primary-700">
              <div class="mb-1 text-2xl font-bold text-gold-400">Global</div>
              <div class="text-sm text-gray-200">Market Reach</div>
            </div>
            <div class="p-4 text-center rounded-lg bg-primary-700">
              <div class="mb-1 text-2xl font-bold text-gold-400">Expert</div>
              <div class="text-sm text-gray-200">Leadership Team</div>
            </div>
          </div>
        </div>
        
        <div class="order-1 lg:order-2">
          <div class="relative">
            <img 
              src="/images/about.jpeg" 
              alt="About MIGBEN" 
              class="object-cover w-full h-96 rounded-2xl shadow-2xl"
            />
            <div class="absolute inset-0 bg-gradient-to-t to-transparent rounded-2xl from-primary-900/20"></div>
          </div>
        </div>
      </div>

      <!-- Leadership Team -->
      <div class="mb-16">
        <div class="mb-16 text-center">
          <div class="inline-block relative">
            <h3 class="mb-4 text-4xl font-bold text-white md:text-5xl">
              Our <span class="text-transparent bg-clip-text bg-gold-gradient">Leadership</span>
            </h3>
            <div class="absolute -bottom-2 left-1/2 w-24 h-1 rounded-full transform -translate-x-1/2 bg-gold-gradient"></div>
          </div>
          <p class="mx-auto mt-6 max-w-2xl text-lg text-gray-200">
            Meet the visionary leaders driving MIGBEN's success in global energy and commodity trading
          </p>
        </div>
        
        <div class="grid grid-cols-1 gap-8 mx-auto max-w-7xl lg:grid-cols-3">
          <!-- CEO - Featured Card -->
          <div class="mb-8 lg:col-span-3">
            <div class="overflow-hidden bg-gradient-to-br rounded-3xl border shadow-2xl transition-all duration-500 transform group from-primary-700 to-primary-800 hover:shadow-3xl hover:-translate-y-3 border-gold-500/20">
              <div class="flex flex-col lg:flex-row">
                <!-- CEO Image -->
                <div class="overflow-hidden relative lg:w-1/3">
                  <img 
                    src="/images/logo3.png" 
                    alt="CEO Kingsley Ofori Andoh" 
                    class="object-cover w-full h-80 transition-transform duration-500 lg:h-full group-hover:scale-105"
                  />
                  <div class="absolute inset-0 bg-gradient-to-r to-transparent from-primary-900/40"></div>
                  <div class="absolute top-4 left-4">
                    <div class="px-3 py-1 text-xs font-bold rounded-full bg-gold-gradient text-primary-900">
                      CEO
                    </div>
                  </div>
                </div>
                
                <!-- CEO Info -->
                <div class="p-8 lg:w-2/3 lg:p-12">
                  <div class="mb-6">
                    <h4 class="mb-2 text-3xl font-bold text-white lg:text-4xl">Kingsley Ofori Andoh</h4>
                    <p class="mb-4 text-lg font-semibold text-gold-400">Chief Executive Officer</p>
                    <p class="leading-relaxed text-gray-200">
                      Leading MIGBEN with strategic vision and deep industry expertise in global energy trading and logistics solutions.
                    </p>
                  </div>
                  
                  <div class="grid grid-cols-1 gap-4 md:grid-cols-2">
                    <div class="p-4 rounded-xl border backdrop-blur-sm bg-primary-600/50 border-gold-500/10">
                      <div class="flex items-center mb-2">
                        <div class="flex justify-center items-center mr-3 w-8 h-8 rounded-full bg-gold-gradient">
                          <svg class="w-4 h-4 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                            <path d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z"/>
                            <path d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z"/>
                          </svg>
                        </div>
                        <span class="font-medium text-white">Email</span>
                      </div>
                      <p class="text-sm text-gray-300">migbenconsultancy@gmail.com</p>
                    </div>
                    
                    <div class="p-4 rounded-xl border backdrop-blur-sm bg-primary-600/50 border-gold-500/10">
                      <div class="flex items-center mb-2">
                        <div class="flex justify-center items-center mr-3 w-8 h-8 rounded-full bg-gold-gradient">
                          <svg class="w-4 h-4 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                            <path d="M2 3a1 1 0 011-1h2.153a1 1 0 01.986.836l.74 4.435a1 1 0 01-.54 1.06l-1.548.773a11.037 11.037 0 006.105 6.105l.774-1.548a1 1 0 011.059-.54l4.435.74a1 1 0 01.836.986V17a1 1 0 01-1 1h-2C7.82 18 2 12.18 2 5V3z"/>
                          </svg>
                        </div>
                        <span class="font-medium text-white">Phone</span>
                      </div>
                      <p class="text-sm text-gray-300">+233 248604953 / +27 737567328</p>
                    </div>
                    
                    <div class="p-4 rounded-xl border backdrop-blur-sm md:col-span-2 bg-primary-600/50 border-gold-500/10">
                      <div class="flex items-center mb-2">
                        <div class="flex justify-center items-center mr-3 w-8 h-8 rounded-full bg-gold-gradient">
                          <svg class="w-4 h-4 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                            <path fill-rule="evenodd" d="M5.05 4.05a7 7 0 119.9 9.9L10 18.9l-4.95-4.95a7 7 0 010-9.9zM10 11a2 2 0 100-4 2 2 0 000 4z" clip-rule="evenodd"/>
                          </svg>
                        </div>
                        <span class="font-medium text-white">Location</span>
                      </div>
                      <p class="text-sm text-gray-300">Ghana / South Africa</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- Director Cards -->
          <div class="lg:col-span-3">
            <div class="grid grid-cols-1 gap-8 md:grid-cols-2">
              <!-- Director 1 -->
              <div class="overflow-hidden bg-gradient-to-br rounded-2xl border shadow-xl transition-all duration-300 transform group from-primary-700 to-primary-800 hover:shadow-2xl hover:-translate-y-2 border-gold-500/20">
                <div class="flex relative justify-center items-center h-64 bg-gradient-to-br from-primary-800 to-primary-900">
                  <!-- Logo -->
                  <img 
                    src="/images/logo3.png" 
                    alt="MIGBEN Logo" 
                    class="object-cover w-32 h-32 rounded-full ring-4 shadow-2xl transition-all duration-300 ring-gold-500/50 group-hover:scale-110"
                  />
                  
                  <!-- Hover Overlay with Name -->
                  <div class="flex absolute inset-0 justify-center items-center opacity-0 backdrop-blur-sm transition-all duration-300 bg-primary-900/95 group-hover:opacity-100">
                    <div class="text-center transition-transform duration-300 transform translate-y-4 group-hover:translate-y-0">
                      <h4 class="mb-2 text-2xl font-bold text-white drop-shadow-lg">Mignon Ofori Andoh</h4>
                      <p class="text-lg font-semibold text-gold-400">Director</p>
                    </div>
                  </div>
                  
                  <div class="absolute top-4 right-4">
                    <div class="px-3 py-1 text-xs font-bold rounded-full bg-gold-gradient text-primary-900">
                      Director
                    </div>
                  </div>
                </div>
                
                <div class="p-6">
                  <div class="space-y-3">
                    <div class="flex items-center p-3 rounded-lg transition-colors bg-primary-600/30 hover:bg-primary-600/50">
                      <div class="flex flex-shrink-0 justify-center items-center mr-3 w-6 h-6 rounded-full bg-gold-gradient">
                        <svg class="w-3 h-3 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                          <path d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z"/>
                          <path d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z"/>
                        </svg>
                      </div>
                      <span class="text-sm text-gray-200">migbenconsultancy@gmail.com</span>
                    </div>
                    
                    <div class="flex items-center p-3 rounded-lg transition-colors bg-primary-600/30 hover:bg-primary-600/50">
                      <div class="flex flex-shrink-0 justify-center items-center mr-3 w-6 h-6 rounded-full bg-gold-gradient">
                        <svg class="w-3 h-3 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                          <path d="M2 3a1 1 0 011-1h2.153a1 1 0 01.986.836l.74 4.435a1 1 0 01-.54 1.06l-1.548.773a11.037 11.037 0 006.105 6.105l.774-1.548a1 1 0 011.059-.54l4.435.74a1 1 0 01.836.986V17a1 1 0 01-1 1h-2C7.82 18 2 12.18 2 5V3z"/>
                        </svg>
                      </div>
                      <span class="text-sm text-gray-200">+233 240690239 / +27 639912356</span>
                    </div>
                    
                    <div class="flex items-center p-3 rounded-lg transition-colors bg-primary-600/30 hover:bg-primary-600/50">
                      <div class="flex flex-shrink-0 justify-center items-center mr-3 w-6 h-6 rounded-full bg-gold-gradient">
                        <svg class="w-3 h-3 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                          <path fill-rule="evenodd" d="M5.05 4.05a7 7 0 119.9 9.9L10 18.9l-4.95-4.95a7 7 0 010-9.9zM10 11a2 2 0 100-4 2 2 0 000 4z" clip-rule="evenodd"/>
                        </svg>
                      </div>
                      <span class="text-sm text-gray-200">93 Willow way , Penhill Estate , Cape Town , Western Cape, South Africa</span>
                    </div>
                  </div>
                </div>
              </div>

              <!-- Director 2 -->
              <div class="overflow-hidden bg-gradient-to-br rounded-2xl border shadow-xl transition-all duration-300 transform group from-primary-700 to-primary-800 hover:shadow-2xl hover:-translate-y-2 border-gold-500/20">
                <div class="flex relative justify-center items-center h-64 bg-gradient-to-br from-primary-800 to-primary-900">
                  <!-- Logo -->
                  <img 
                    src="/images/logo3.png" 
                    alt="MIGBEN Logo" 
                    class="object-cover w-32 h-32 rounded-full ring-4 shadow-2xl transition-all duration-300 ring-gold-500/50 group-hover:scale-110"
                  />
                  
                  <!-- Hover Overlay with Name -->
                  <div class="flex absolute inset-0 justify-center items-center opacity-0 backdrop-blur-sm transition-all duration-300 bg-primary-900/95 group-hover:opacity-100">
                    <div class="text-center transition-transform duration-300 transform translate-y-4 group-hover:translate-y-0">
                      <h4 class="mb-2 text-2xl font-bold text-white drop-shadow-lg">Robert Currie Opoku</h4>
                      <p class="text-lg font-semibold text-gold-400">Director</p>
                    </div>
                  </div>
                  
                  <div class="absolute top-4 right-4">
                    <div class="px-3 py-1 text-xs font-bold rounded-full bg-gold-gradient text-primary-900">
                      Director
                    </div>
                  </div>
                </div>
                
                <div class="p-6">
                  <div class="space-y-3">
                    <div class="flex items-center p-3 rounded-lg transition-colors bg-primary-600/30 hover:bg-primary-600/50">
                      <div class="flex flex-shrink-0 justify-center items-center mr-3 w-6 h-6 rounded-full bg-gold-gradient">
                        <svg class="w-3 h-3 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                          <path d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z"/>
                          <path d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z"/>
                        </svg>
                      </div>
                      <span class="text-sm text-gray-200">migbenconsultancy@gmail.com</span>
                    </div>
                    
                    <div class="flex items-center p-3 rounded-lg transition-colors bg-primary-600/30 hover:bg-primary-600/50">
                      <div class="flex flex-shrink-0 justify-center items-center mr-3 w-6 h-6 rounded-full bg-gold-gradient">
                        <svg class="w-3 h-3 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                          <path d="M2 3a1 1 0 011-1h2.153a1 1 0 01.986.836l.74 4.435a1 1 0 01-.54 1.06l-1.548.773a11.037 11.037 0 006.105 6.105l.774-1.548a1 1 0 011.059-.54l4.435.74a1 1 0 01.836.986V17a1 1 0 01-1 1h-2C7.82 18 2 12.18 2 5V3z"/>
                        </svg>
                      </div>
                      <span class="text-sm text-gray-200">+233 545 741449 </span>
                    </div>
                    
                    <div class="flex items-center p-3 rounded-lg transition-colors bg-primary-600/30 hover:bg-primary-600/50">
                      <div class="flex flex-shrink-0 justify-center items-center mr-3 w-6 h-6 rounded-full bg-gold-gradient">
                        <svg class="w-3 h-3 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                          <path fill-rule="evenodd" d="M5.05 4.05a7 7 0 119.9 9.9L10 18.9l-4.95-4.95a7 7 0 010-9.9zM10 11a2 2 0 100-4 2 2 0 000 4z" clip-rule="evenodd"/>
                        </svg>
                      </div>
                      <span class="text-sm text-gray-200">Abelenkpe Taxi Rank, Alhaji Sulley Street, Accra, Ghana</span>
                    </div>
                  </div>
                </div>
              </div>
              
            </div>
          </div>
        </div>
      </div>

      <!-- Values Section -->
      <div class="p-8 bg-gradient-to-r rounded-3xl from-primary-900 to-primary-800 md:p-12">
        <div class="mb-12 text-center">
          <h3 class="mb-4 text-3xl font-bold text-white">Our Core Values</h3>
          <p class="mx-auto max-w-2xl text-gray-200">
            The principles that guide our operations and define our commitment to excellence
          </p>
        </div>

        <div class="grid grid-cols-1 gap-8 md:grid-cols-3">
          <div class="text-center">
            <div class="flex justify-center items-center mx-auto mb-4 w-16 h-16 rounded-full bg-gold-gradient">
              <svg class="w-8 h-8 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                <path fill-rule="evenodd" d="M6.267 3.455a3.066 3.066 0 001.745-.723 3.066 3.066 0 013.976 0 3.066 3.066 0 001.745.723 3.066 3.066 0 012.812 2.812c.051.643.304 1.254.723 1.745a3.066 3.066 0 010 3.976 3.066 3.066 0 00-.723 1.745 3.066 3.066 0 01-2.812 2.812 3.066 3.066 0 00-1.745.723 3.066 3.066 0 01-3.976 0 3.066 3.066 0 00-1.745-.723 3.066 3.066 0 01-2.812-2.812 3.066 3.066 0 00-.723-1.745 3.066 3.066 0 010-3.976 3.066 3.066 0 00.723-1.745 3.066 3.066 0 012.812-2.812zm7.44 5.252a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
              </svg>
            </div>
            <h4 class="mb-2 text-xl font-bold text-white">Integrity</h4>
            <p class="text-gray-300">Transparent and ethical business practices in all our operations</p>
          </div>

          <div class="text-center">
            <div class="flex justify-center items-center mx-auto mb-4 w-16 h-16 rounded-full bg-gold-gradient">
              <svg class="w-8 h-8 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/>
              </svg>
            </div>
            <h4 class="mb-2 text-xl font-bold text-white">Excellence</h4>
            <p class="text-gray-300">Commitment to delivering superior quality in every service</p>
          </div>

          <div class="text-center">
            <div class="flex justify-center items-center mx-auto mb-4 w-16 h-16 rounded-full bg-gold-gradient">
              <svg class="w-8 h-8 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                <path d="M13 6a3 3 0 11-6 0 3 3 0 016 0zM18 8a2 2 0 11-4 0 2 2 0 014 0zM14 15a4 4 0 00-8 0v3h8v-3z"/>
              </svg>
            </div>
            <h4 class="mb-2 text-xl font-bold text-white">Innovation</h4>
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
