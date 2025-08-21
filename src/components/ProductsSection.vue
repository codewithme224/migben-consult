<template>
  <section id="products" class="py-20 bg-gradient-to-br from-primary-900 to-primary-800">
    <div class="px-4 mx-auto max-w-7xl sm:px-6 lg:px-8">
      <!-- Section Header -->
      <div class="mb-16 text-center">
        <h2 class="mb-6 text-4xl font-bold text-white md:text-5xl">
          Our <span class="text-transparent bg-clip-text bg-gold-gradient">Products</span>
        </h2>
        <p class="mx-auto max-w-3xl text-lg leading-relaxed text-gray-200">
          Premium agricultural commodities and energy products sourced globally
        </p>
      </div>

      <!-- Main Product Categories -->
      <div class="grid grid-cols-1 gap-12 mb-20 lg:grid-cols-2">
        <!-- Agricultural Commodities -->
        <div class="group">
          <div class="p-8 rounded-3xl border backdrop-blur-md transition-all duration-300 bg-white/10 border-white/20 hover:bg-white/15">
            <div class="relative mb-8">
              <img 
                src="/images/product2.jpeg" 
                alt="Agricultural Commodities" 
                class="object-cover w-full h-64 rounded-2xl transition-transform duration-300 group-hover:scale-105"
              />
              <!-- Glassmorphism Overlay -->
              <div class="absolute inset-0 bg-gradient-to-t to-transparent rounded-2xl from-primary-900/60"></div>
              <div class="absolute inset-0 backdrop-blur-[2px] bg-white/5 rounded-2xl"></div>
              <div class="absolute inset-0 bg-gradient-to-br via-transparent rounded-2xl from-white/10 to-black/20"></div>
              
              <div class="absolute right-4 bottom-4 left-4">
                <div class="p-4 rounded-xl border shadow-2xl backdrop-blur-md bg-white/10 border-white/20">
                  <div class="inline-block relative">
                    <h3 class="mb-2 text-3xl font-bold text-white drop-shadow-lg">
                      Agricultural <span class="text-transparent bg-clip-text bg-gold-gradient">Commodities</span>
                    </h3>
                    <div class="absolute left-0 -bottom-1 w-16 h-1 rounded-full bg-gold-gradient"></div>
                  </div>
                  <p class="mt-3 text-sm text-gray-200">Premium quality grains and agricultural products</p>
                </div>
              </div>
            </div>

            <!-- Product Grid -->
            <div class="grid grid-cols-2 gap-4">
              <div class="p-4 text-center rounded-xl transition-colors duration-300 bg-white/10 hover:bg-white/20">
                <div class="mb-1 font-semibold text-gold-400">Sugar Beans</div>
                <div class="text-sm text-gray-300">(Red Speckled)</div>
              </div>
              <div class="p-4 text-center rounded-xl transition-colors duration-300 bg-white/10 hover:bg-white/20">
                <div class="mb-1 font-semibold text-gold-400">Yellow Maize</div>
                <div class="text-sm text-gray-300">Premium Grade</div>
              </div>
              <div class="p-4 text-center rounded-xl transition-colors duration-300 bg-white/10 hover:bg-white/20">
                <div class="mb-1 font-semibold text-gold-400">White Maize</div>
                <div class="text-sm text-gray-300">Food Grade</div>
              </div>
              <div class="p-4 text-center rounded-xl transition-colors duration-300 bg-white/10 hover:bg-white/20">
                <div class="mb-1 font-semibold text-gold-400">Soya Beans</div>
                <div class="text-sm text-gray-300">Non-GMO</div>
              </div>
              <div class="p-4 text-center rounded-xl transition-colors duration-300 bg-white/10 hover:bg-white/20">
                <div class="mb-1 font-semibold text-gold-400">Wheat</div>
                <div class="text-sm text-gray-300">Various Grades</div>
              </div>
              <div class="p-4 text-center rounded-xl transition-colors duration-300 bg-white/10 hover:bg-white/20">
                <div class="mb-1 font-semibold text-gold-400">Rice</div>
                <div class="text-sm text-gray-300">Premium Quality</div>
              </div>
            </div>
          </div>
        </div>

        <!-- Energy Products -->
        <div class="group">
          <div class="p-8 rounded-3xl border backdrop-blur-md transition-all duration-300 bg-white/10 border-white/20 hover:bg-white/15">
            <div class="relative mb-8">
              <img 
                src="/images/product.jpeg" 
                alt="Energy Products" 
                class="object-cover w-full h-64 rounded-2xl transition-transform duration-300 group-hover:scale-105"
              />
              <!-- Glassmorphism Overlay -->
              <div class="absolute inset-0 bg-gradient-to-t to-transparent rounded-2xl from-primary-900/60"></div>
              <div class="absolute inset-0 backdrop-blur-[2px] bg-white/5 rounded-2xl"></div>
              <div class="absolute inset-0 bg-gradient-to-br via-transparent rounded-2xl from-white/10 to-black/20"></div>
              
              <div class="absolute right-4 bottom-4 left-4">
                <div class="p-4 rounded-xl border shadow-2xl backdrop-blur-md bg-white/10 border-white/20">
                  <div class="inline-block relative">
                    <h3 class="mb-2 text-3xl font-bold text-white drop-shadow-lg">
                      Energy <span class="text-transparent bg-clip-text bg-gold-gradient">Products</span>
                    </h3>
                    <div class="absolute left-0 -bottom-1 w-16 h-1 rounded-full bg-gold-gradient"></div>
                  </div>
                  <p class="mt-3 text-sm text-gray-200">Refined petroleum products and fuels</p>
                </div>
              </div>
            </div>

            <!-- Product Grid -->
            <div class="grid grid-cols-1 gap-4">
              <div class="p-4 rounded-xl transition-colors duration-300 bg-white/10 hover:bg-white/20">
                <div class="flex justify-between items-center">
                  <div>
                    <div class="mb-1 font-semibold text-gold-400">Diesel (EN590)</div>
                    <div class="text-sm text-gray-300">Ultra-low sulfur diesel fuel</div>
                  </div>
                  <div class="flex justify-center items-center w-8 h-8 rounded-full bg-gold-gradient">
                    <svg class="w-4 h-4 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                      <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/>
                    </svg>
                  </div>
                </div>
              </div>
              <div class="p-4 rounded-xl transition-colors duration-300 bg-white/10 hover:bg-white/20">
                <div class="flex justify-between items-center">
                  <div>
                    <div class="mb-1 font-semibold text-gold-400">Jet A1</div>
                    <div class="text-sm text-gray-300">Aviation turbine fuel</div>
                  </div>
                  <div class="flex justify-center items-center w-8 h-8 rounded-full bg-gold-gradient">
                    <svg class="w-4 h-4 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                      <path d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-8.293l-3-3a1 1 0 00-1.414 1.414L10.586 9H7a1 1 0 100 2h3.586l-1.293 1.293a1 1 0 101.414 1.414l3-3a1 1 0 000-1.414z"/>
                    </svg>
                  </div>
                </div>
              </div>
              <div class="p-4 rounded-xl transition-colors duration-300 bg-white/10 hover:bg-white/20">
                <div class="flex justify-between items-center">
                  <div>
                    <div class="mb-1 font-semibold text-gold-400">Gas Oil</div>
                    <div class="text-sm text-gray-300">Marine and industrial fuel</div>
                  </div>
                  <div class="flex justify-center items-center w-8 h-8 rounded-full bg-gold-gradient">
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
        <h3 class="mb-8 text-2xl font-bold text-center text-white">Additional Products</h3>
        <div class="grid grid-cols-2 gap-4 md:grid-cols-4 lg:grid-cols-6">
          <div class="p-4 text-center rounded-lg backdrop-blur-sm transition-colors duration-300 bg-white/10 hover:bg-white/20">
            <div class="mb-1 text-sm font-semibold text-gold-400">Sugar</div>
            <div class="text-xs text-gray-300">ICUMSA 45</div>
          </div>
          <div class="p-4 text-center rounded-lg backdrop-blur-sm transition-colors duration-300 bg-white/10 hover:bg-white/20">
            <div class="mb-1 text-sm font-semibold text-gold-400">Sunflower Oil/Seeds</div>
            <div class="text-xs text-gray-300">Premium Grade</div>
          </div>
          <div class="p-4 text-center rounded-lg backdrop-blur-sm transition-colors duration-300 bg-white/10 hover:bg-white/20">
            <div class="mb-1 text-sm font-semibold text-gold-400">Sorghum</div>
            <div class="text-xs text-gray-300">Food Grade</div>
          </div>
          <div class="p-4 text-center rounded-lg backdrop-blur-sm transition-colors duration-300 bg-white/10 hover:bg-white/20">
            <div class="mb-1 text-sm font-semibold text-gold-400">Flour</div>
            <div class="text-xs text-gray-300">Various Grades</div>
          </div>
          <div class="p-4 text-center rounded-lg backdrop-blur-sm transition-colors duration-300 bg-white/10 hover:bg-white/20">
            <div class="mb-1 text-sm font-semibold text-gold-400">Cassava</div>
            <div class="text-xs text-gray-300">Fresh & Processed</div>
          </div>
          <div class="p-4 text-center rounded-lg backdrop-blur-sm transition-colors duration-300 bg-white/10 hover:bg-white/20">
            <div class="mb-1 text-sm font-semibold text-gold-400">Marine Fuel</div>
            <div class="text-xs text-gray-300">High Quality</div>
          </div>
        </div>
      </div>

      <!-- Quality Assurance -->
      <div class="p-8 text-center bg-gradient-to-r rounded-3xl from-gold-600 to-gold-500 md:p-12">
        <h3 class="mb-4 text-3xl font-bold text-primary-900">Quality Assurance</h3>
        <p class="mx-auto mb-8 max-w-2xl text-lg text-gray-300">
          All our products meet international standards and undergo rigorous quality control processes to ensure excellence.
        </p>
        <div class="grid grid-cols-1 gap-6 md:grid-cols-3">
          <div class="p-6 rounded-xl transition-colors duration-300 bg-white/10 hover:bg-white/20">
            <div class="flex justify-center items-center mx-auto mb-4 w-12 h-12 rounded-lg bg-gold-gradient">
              <svg class="w-6 h-6 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                <path fill-rule="evenodd" d="M6.267 3.455a3.066 3.066 0 001.745-.723 3.066 3.066 0 013.976 0 3.066 3.066 0 001.745.723 3.066 3.066 0 012.812 2.812c.051.643.304 1.254.723 1.745a3.066 3.066 0 010 3.976 3.066 3.066 0 00-.723 1.745 3.066 3.066 0 01-2.812 2.812 3.066 3.066 0 00-1.745.723 3.066 3.066 0 01-3.976 0 3.066 3.066 0 00-1.745-.723 3.066 3.066 0 01-2.812-2.812 3.066 3.066 0 00-.723-1.745 3.066 3.066 0 010-3.976 3.066 3.066 0 00.723-1.745 3.066 3.066 0 012.812-2.812zm7.44 5.252a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
              </svg>
            </div>
            <h4 class="mb-2 text-lg font-bold text-gold-400">Certified</h4>
            <p class="text-sm text-gray-300">International quality certifications</p>
          </div>
          <div class="p-6 rounded-xl transition-colors duration-300 bg-white/10 hover:bg-white/20">
            <div class="flex justify-center items-center mx-auto mb-4 w-12 h-12 rounded-lg bg-gold-gradient">
              <svg class="w-6 h-6 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                <path d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"/>
              </svg>
            </div>
            <h4 class="mb-2 text-lg font-bold text-gold-400">Tested</h4>
            <p class="text-sm text-gray-300">Rigorous quality testing protocols</p>
          </div>
          <div class="p-6 rounded-xl transition-colors duration-300 bg-white/10 hover:bg-white/20">
            <div class="flex justify-center items-center mx-auto mb-4 w-12 h-12 rounded-lg bg-gold-gradient">
              <svg class="w-6 h-6 text-primary-900" fill="currentColor" viewBox="0 0 20 20">
                <path d="M3 4a1 1 0 011-1h12a1 1 0 011 1v2a1 1 0 01-1 1H4a1 1 0 01-1-1V4zM3 10a1 1 0 011-1h6a1 1 0 011 1v6a1 1 0 01-1 1H4a1 1 0 01-1-1v-6zM14 9a1 1 0 00-1 1v6a1 1 0 001 1h2a1 1 0 001-1v-6a1 1 0 00-1-1h-2z"/>
              </svg>
            </div>
            <h4 class="mb-2 text-lg font-bold text-gold-400">Tracked</h4>
            <p class="text-sm text-gray-300">Complete supply chain traceability</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
// Component logic here if needed
</script>
