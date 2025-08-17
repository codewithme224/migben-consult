<template>
  <section id="products" class="py-20 bg-gradient-to-br from-primary-900 to-primary-800">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <!-- Section Header -->
      <div class="text-center mb-16">
        <h2 class="text-4xl md:text-5xl font-bold text-white mb-6">
          Our <span class="bg-gold-gradient bg-clip-text text-transparent">Products</span>
        </h2>
        <p class="text-lg text-gray-200 max-w-3xl mx-auto leading-relaxed">
          Premium agricultural commodities and energy products sourced globally
        </p>
      </div>

      <!-- Main Product Categories -->
      <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 mb-20">
        <!-- Agricultural Commodities -->
        <div class="group">
          <div class="bg-white/10 backdrop-blur-md rounded-3xl p-8 border border-white/20 hover:bg-white/15 transition-all duration-300">
            <div class="relative mb-8">
              <img 
                src="/images/product2.jpeg" 
                alt="Agricultural Commodities" 
                class="w-full h-64 object-cover rounded-2xl group-hover:scale-105 transition-transform duration-300"
              />
              <!-- Glassmorphism Overlay -->
              <div class="absolute inset-0 bg-gradient-to-t from-primary-900/60 to-transparent rounded-2xl"></div>
              <div class="absolute inset-0 backdrop-blur-[2px] bg-white/5 rounded-2xl"></div>
              <div class="absolute inset-0 bg-gradient-to-br from-white/10 via-transparent to-black/20 rounded-2xl"></div>
              
              <div class="absolute bottom-4 left-4 right-4">
                <div class="bg-white/10 backdrop-blur-md rounded-xl p-4 border border-white/20 shadow-2xl">
                  <div class="inline-block relative">
                    <h3 class="text-3xl font-bold text-white mb-2 drop-shadow-lg">
                      Agricultural <span class="bg-gold-gradient bg-clip-text text-transparent">Commodities</span>
                    </h3>
                    <div class="absolute -bottom-1 left-0 w-16 h-1 bg-gold-gradient rounded-full"></div>
                  </div>
                  <p class="text-gray-200 text-sm mt-3">Premium quality grains and agricultural products</p>
                </div>
              </div>
            </div>

            <!-- Product Grid -->
            <div class="grid grid-cols-2 gap-4">
              <div class="bg-white/10 rounded-xl p-4 text-center hover:bg-white/20 transition-colors duration-300">
                <div class="text-gold-400 font-semibold mb-1">Sugar Beans</div>
                <div class="text-gray-300 text-sm">(Red Speckled)</div>
              </div>
              <div class="bg-white/10 rounded-xl p-4 text-center hover:bg-white/20 transition-colors duration-300">
                <div class="text-gold-400 font-semibold mb-1">Yellow Maize</div>
                <div class="text-gray-300 text-sm">Premium Grade</div>
              </div>
              <div class="bg-white/10 rounded-xl p-4 text-center hover:bg-white/20 transition-colors duration-300">
                <div class="text-gold-400 font-semibold mb-1">White Maize</div>
                <div class="text-gray-300 text-sm">Food Grade</div>
              </div>
              <div class="bg-white/10 rounded-xl p-4 text-center hover:bg-white/20 transition-colors duration-300">
                <div class="text-gold-400 font-semibold mb-1">Soya Beans</div>
                <div class="text-gray-300 text-sm">Non-GMO</div>
              </div>
              <div class="bg-white/10 rounded-xl p-4 text-center hover:bg-white/20 transition-colors duration-300">
                <div class="text-gold-400 font-semibold mb-1">Wheat</div>
                <div class="text-gray-300 text-sm">Various Grades</div>
              </div>
              <div class="bg-white/10 rounded-xl p-4 text-center hover:bg-white/20 transition-colors duration-300">
                <div class="text-gold-400 font-semibold mb-1">Rice</div>
                <div class="text-gray-300 text-sm">Premium Quality</div>
              </div>
            </div>
          </div>
        </div>

        <!-- Energy Products -->
        <div class="group">
          <div class="bg-white/10 backdrop-blur-md rounded-3xl p-8 border border-white/20 hover:bg-white/15 transition-all duration-300">
            <div class="relative mb-8">
              <img 
                src="/images/product.jpeg" 
                alt="Energy Products" 
                class="w-full h-64 object-cover rounded-2xl group-hover:scale-105 transition-transform duration-300"
              />
              <!-- Glassmorphism Overlay -->
              <div class="absolute inset-0 bg-gradient-to-t from-primary-900/60 to-transparent rounded-2xl"></div>
              <div class="absolute inset-0 backdrop-blur-[2px] bg-white/5 rounded-2xl"></div>
              <div class="absolute inset-0 bg-gradient-to-br from-white/10 via-transparent to-black/20 rounded-2xl"></div>
              
              <div class="absolute bottom-4 left-4 right-4">
                <div class="bg-white/10 backdrop-blur-md rounded-xl p-4 border border-white/20 shadow-2xl">
                  <div class="inline-block relative">
                    <h3 class="text-3xl font-bold text-white mb-2 drop-shadow-lg">
                      Energy <span class="bg-gold-gradient bg-clip-text text-transparent">Products</span>
                    </h3>
                    <div class="absolute -bottom-1 left-0 w-16 h-1 bg-gold-gradient rounded-full"></div>
                  </div>
                  <p class="text-gray-200 text-sm mt-3">Refined petroleum products and fuels</p>
                </div>
              </div>
            </div>

            <!-- Product Grid -->
            <div class="grid grid-cols-1 gap-4">
              <div class="bg-white/10 rounded-xl p-4 hover:bg-white/20 transition-colors duration-300">
                <div class="flex items-center justify-between">
                  <div>
                    <div class="text-gold-400 font-semibold mb-1">Diesel (EN590)</div>
                    <div class="text-gray-300 text-sm">Ultra-low sulfur diesel fuel</div>
                  </div>
                  <div class="w-8 h-8 bg-gold-gradient rounded-full flex items-center justify-center">
                    <svg class="w-4 h-4 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                      <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/>
                    </svg>
                  </div>
                </div>
              </div>
              <div class="bg-white/10 rounded-xl p-4 hover:bg-white/20 transition-colors duration-300">
                <div class="flex items-center justify-between">
                  <div>
                    <div class="text-gold-400 font-semibold mb-1">Jet A1</div>
                    <div class="text-gray-300 text-sm">Aviation turbine fuel</div>
                  </div>
                  <div class="w-8 h-8 bg-gold-gradient rounded-full flex items-center justify-center">
                    <svg class="w-4 h-4 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                      <path d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-8.293l-3-3a1 1 0 00-1.414 1.414L10.586 9H7a1 1 0 100 2h3.586l-1.293 1.293a1 1 0 101.414 1.414l3-3a1 1 0 000-1.414z"/>
                    </svg>
                  </div>
                </div>
              </div>
              <div class="bg-white/10 rounded-xl p-4 hover:bg-white/20 transition-colors duration-300">
                <div class="flex items-center justify-between">
                  <div>
                    <div class="text-gold-400 font-semibold mb-1">Gas Oil</div>
                    <div class="text-gray-300 text-sm">Marine and industrial fuel</div>
                  </div>
                  <div class="w-8 h-8 bg-gold-gradient rounded-full flex items-center justify-center">
                    <svg class="w-4 h-4 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                      <path fill-rule="evenodd" d="M11.3 1.046A1 1 0 0112 2v5h4a1 1 0 01.82 1.573l-7 10A1 1 0 018 18v-5H4a1 1 0 01-.82-1.573l7-10a1 1 0 011.12-.38z" clip-rule="evenodd"/>
                    </svg>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Additional Products -->
      <div class="mb-16">
        <h3 class="text-2xl font-bold text-white text-center mb-8">Additional Products</h3>
        <div class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-6 gap-4">
          <div class="bg-white/10 backdrop-blur-sm rounded-lg p-4 text-center hover:bg-white/20 transition-colors duration-300">
            <div class="text-gold-400 font-semibold text-sm mb-1">Sugar</div>
            <div class="text-gray-300 text-xs">ICUMSA 45</div>
          </div>
          <div class="bg-white/10 backdrop-blur-sm rounded-lg p-4 text-center hover:bg-white/20 transition-colors duration-300">
            <div class="text-gold-400 font-semibold text-sm mb-1">Sunflower Seeds</div>
            <div class="text-gray-300 text-xs">Premium Grade</div>
          </div>
          <div class="bg-white/10 backdrop-blur-sm rounded-lg p-4 text-center hover:bg-white/20 transition-colors duration-300">
            <div class="text-gold-400 font-semibold text-sm mb-1">Sorghum</div>
            <div class="text-gray-300 text-xs">Food Grade</div>
          </div>
          <div class="bg-white/10 backdrop-blur-sm rounded-lg p-4 text-center hover:bg-white/20 transition-colors duration-300">
            <div class="text-gold-400 font-semibold text-sm mb-1">Flour</div>
            <div class="text-gray-300 text-xs">Various Grades</div>
          </div>
          <div class="bg-white/10 backdrop-blur-sm rounded-lg p-4 text-center hover:bg-white/20 transition-colors duration-300">
            <div class="text-gold-400 font-semibold text-sm mb-1">Cassava</div>
            <div class="text-gray-300 text-xs">Fresh & Processed</div>
          </div>
          <div class="bg-white/10 backdrop-blur-sm rounded-lg p-4 text-center hover:bg-white/20 transition-colors duration-300">
            <div class="text-gold-400 font-semibold text-sm mb-1">Marine Fuel</div>
            <div class="text-gray-300 text-xs">High Quality</div>
          </div>
        </div>
      </div>

      <!-- Quality Assurance -->
      <div class="bg-gradient-to-r from-gold-600 to-gold-500 rounded-3xl p-8 md:p-12 text-center">
        <h3 class="text-3xl font-bold text-primary-900 mb-4">Quality Assurance</h3>
        <p class="text-gray-300 mb-8 max-w-2xl mx-auto text-lg">
          All our products meet international standards and undergo rigorous quality control processes to ensure excellence.
        </p>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
          <div class="bg-white/10 rounded-xl p-6 hover:bg-white/20 transition-colors duration-300">
            <div class="w-12 h-12 bg-gold-gradient rounded-lg mx-auto mb-4 flex items-center justify-center">
              <svg class="w-6 h-6 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                <path fill-rule="evenodd" d="M6.267 3.455a3.066 3.066 0 001.745-.723 3.066 3.066 0 013.976 0 3.066 3.066 0 001.745.723 3.066 3.066 0 012.812 2.812c.051.643.304 1.254.723 1.745a3.066 3.066 0 010 3.976 3.066 3.066 0 00-.723 1.745 3.066 3.066 0 01-2.812 2.812 3.066 3.066 0 00-1.745.723 3.066 3.066 0 01-3.976 0 3.066 3.066 0 00-1.745-.723 3.066 3.066 0 01-2.812-2.812 3.066 3.066 0 00-.723-1.745 3.066 3.066 0 010-3.976 3.066 3.066 0 00.723-1.745 3.066 3.066 0 012.812-2.812zm7.44 5.252a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
              </svg>
            </div>
            <h4 class="text-lg font-bold text-gold-400 mb-2">Certified</h4>
            <p class="text-gray-300 text-sm">International quality certifications</p>
          </div>
          <div class="bg-white/10 rounded-xl p-6 hover:bg-white/20 transition-colors duration-300">
            <div class="w-12 h-12 bg-gold-gradient rounded-lg mx-auto mb-4 flex items-center justify-center">
              <svg class="w-6 h-6 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                <path d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"/>
              </svg>
            </div>
            <h4 class="text-lg font-bold text-gold-400 mb-2">Tested</h4>
            <p class="text-gray-300 text-sm">Rigorous quality testing protocols</p>
          </div>
          <div class="bg-white/10 rounded-xl p-6 hover:bg-white/20 transition-colors duration-300">
            <div class="w-12 h-12 bg-gold-gradient rounded-lg mx-auto mb-4 flex items-center justify-center">
              <svg class="w-6 h-6 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                <path d="M3 4a1 1 0 011-1h12a1 1 0 011 1v2a1 1 0 01-1 1H4a1 1 0 01-1-1V4zM3 10a1 1 0 011-1h6a1 1 0 011 1v6a1 1 0 01-1 1H4a1 1 0 01-1-1v-6zM14 9a1 1 0 00-1 1v6a1 1 0 001 1h2a1 1 0 001-1v-6a1 1 0 00-1-1h-2z"/>
              </svg>
            </div>
            <h4 class="text-lg font-bold text-gold-400 mb-2">Tracked</h4>
            <p class="text-gray-300 text-sm">Complete supply chain traceability</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
// Component logic here if needed
</script>
