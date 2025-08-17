<template>
  <section id="workflow" class="overflow-hidden relative py-20 bg-primary-900">
    <!-- Animated Background Elements -->
    <div class="absolute inset-0 z-10">
      <div class="absolute left-10 top-20 w-20 h-20 rounded-full bg-gold-400/10 animate-float"></div>
      <div class="absolute right-20 top-40 w-16 h-16 rounded-full bg-primary-400/10 animate-float" style="animation-delay: 2s;"></div>
      <div class="absolute left-20 bottom-40 w-12 h-12 rounded-full bg-gold-300/10 animate-float" style="animation-delay: 4s;"></div>
    </div>
    
    <div class="relative z-20 px-4 mx-auto max-w-7xl sm:px-6 lg:px-8">
      <!-- Section Header -->
      <div class="mb-16 text-center">
        <h2 class="mb-4 text-4xl font-bold text-white">
          INTERNATIONAL TRADE TRANSACTION PROCEDURE
        </h2>
        <p class="mb-8 text-xl text-gold-400">
          EXPORT WORKFLOW
        </p>
        <div class="mx-auto w-24 h-1 rounded-full bg-gold-500"></div>
      </div>

      <!-- Main Workflow Steps -->
      <div class="relative">
        <!-- Step 1: Customer Sends LOI -->
        <div class="flex justify-center mb-8">
          <div class="relative">
            <div class="px-8 py-4 rounded-full border shadow-lg glassmorphism border-purple-400/30">
              <p class="max-w-md font-medium text-center text-white">
                CUSTOMER SENDS LETTER OF INTENT (LOI) WITH PROOF OF FUNDS
              </p>
            </div>
            <!-- Arrow -->
            <div class="absolute right-0 top-full w-8 h-8 transform translate-x-1/2">
              <svg viewBox="0 0 24 24" fill="none" class="w-full h-full">
                <path d="M12 4L12 20M12 20L18 14M12 20L6 14" stroke="#F59E0B" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
              </svg>
            </div>
          </div>
        </div>

        <!-- Step 2: Seller Issues FCO -->
        <div class="flex justify-center mb-8">
          <div class="relative">
            <div class="px-8 py-4 rounded-full border shadow-lg glassmorphism border-purple-400/30">
              <p class="max-w-md font-medium text-center text-white">
                SELLER ISSUES FULL CORPORATE OFFER (FCO)
              </p>
            </div>
            <!-- Arrow -->
            <div class="absolute right-0 top-full w-8 h-8 transform translate-x-1/2">
              <svg viewBox="0 0 24 24" fill="none" class="w-full h-full">
                <path d="M12 4L12 20M12 20L18 14M12 20L6 14" stroke="#F59E0B" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
              </svg>
            </div>
          </div>
        </div>

        <!-- Step 3: Buyer Confirms FCO -->
        <div class="flex justify-center mb-8">
          <div class="relative">
            <div class="px-8 py-4 rounded-full border shadow-lg glassmorphism border-purple-400/30">
              <p class="max-w-md font-medium text-center text-white">
                BUYER CONFIRMS FCO & ISSUES ICPO
              </p>
            </div>
            <!-- Golden Arrow to next section -->
            <div class="absolute left-0 top-full w-8 h-8 transform -translate-x-1/2">
              <svg viewBox="0 0 24 24" fill="none" class="w-full h-full">
                <path d="M12 4L12 20M12 20L18 14M12 20L6 14" stroke="#F59E0B" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
              </svg>
            </div>
          </div>
        </div>

        <!-- Step 4: Seller Issues Proforma Invoice -->
        <div class="flex justify-center mb-8">
          <div class="relative">
            <div class="px-8 py-4 rounded-full border shadow-lg glassmorphism border-blue-400/30">
              <p class="max-w-md font-medium text-center text-white">
                SELLER ISSUES PROFORMA INVOICE
              </p>
            </div>
            <!-- Arrow -->
            <div class="absolute right-0 top-full w-8 h-8 transform translate-x-1/2">
              <svg viewBox="0 0 24 24" fill="none" class="w-full h-full">
                <path d="M12 4L12 20M12 20L18 14M12 20L6 14" stroke="#F59E0B" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
              </svg>
            </div>
          </div>
        </div>

        <!-- Step 5: Buyer Provides LC Draft -->
        <div class="flex justify-center mb-8">
          <div class="relative">
            <div class="px-8 py-4 rounded-full border shadow-lg glassmorphism border-blue-400/30">
              <p class="max-w-md font-medium text-center text-white">
                BUYER PROVIDES LC DRAFT
              </p>
            </div>
            <!-- Arrow -->
            <div class="absolute right-0 top-full w-8 h-8 transform translate-x-1/2">
              <svg viewBox="0 0 24 24" fill="none" class="w-full h-full">
                <path d="M12 4L12 20M12 20L18 14M12 20L6 14" stroke="#F59E0B" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
              </svg>
            </div>
          </div>
        </div>

        <!-- Step 6: Contract Negotiation -->
        <div class="flex justify-center mb-8">
          <div class="relative">
            <div class="px-8 py-4 rounded-full border shadow-lg glassmorphism border-blue-400/30">
              <p class="max-w-md font-medium text-center text-white">
                CONTRACT NEGOTIATION & SIGNING (SALES PURCHASE AGREEMENT)
              </p>
            </div>
            <!-- Golden Arrow to next section -->
            <div class="absolute left-0 top-full w-8 h-8 transform -translate-x-1/2">
              <svg viewBox="0 0 24 24" fill="none" class="w-full h-full">
                <path d="M12 4L12 20M12 20L18 14M12 20L6 14" stroke="#F59E0B" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
              </svg>
            </div>
          </div>
        </div>

        <!-- Step 7: Buyer Opens Financial Instrument -->
        <div class="flex justify-center mb-8">
          <div class="relative">
            <div class="px-8 py-4 rounded-full border shadow-lg glassmorphism border-gold-400/30">
              <p class="max-w-md font-medium text-center text-white">
                BUYER OPENS FINANCIAL INSTRUMENT / TT
              </p>
            </div>
            <!-- Arrow -->
            <div class="absolute right-0 top-full w-8 h-8 transform translate-x-1/2">
              <svg viewBox="0 0 24 24" fill="none" class="w-full h-full">
                <path d="M12 4L12 20M12 20L18 14M12 20L6 14" stroke="#F59E0B" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
              </svg>
            </div>
          </div>
        </div>

        <!-- Step 8: Seller Prepares Product -->
        <div class="flex justify-center mb-8">
          <div class="relative">
            <div class="px-8 py-4 rounded-full border shadow-lg glassmorphism border-gold-400/30">
              <p class="max-w-md font-medium text-center text-white">
                SELLER PREPARES PRODUCT
              </p>
            </div>
            <!-- Arrow -->
            <div class="absolute right-0 top-full w-8 h-8 transform translate-x-1/2">
              <svg viewBox="0 0 24 24" fill="none" class="w-full h-full">
                <path d="M12 4L12 20M12 20L18 14M12 20L6 14" stroke="#F59E0B" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
              </svg>
            </div>
          </div>
        </div>

        <!-- Step 9: Inspection & Pre-shipment -->
        <div class="flex justify-center mb-8">
          <div class="relative">
            <div class="px-8 py-4 rounded-full border shadow-lg glassmorphism border-gold-400/30">
              <p class="max-w-md font-medium text-center text-white">
                INSPECTION & PRE-SHIPMENT VERIFICATION
              </p>
            </div>
            <!-- Arrow -->
            <div class="absolute right-0 top-full w-8 h-8 transform translate-x-1/2">
              <svg viewBox="0 0 24 24" fill="none" class="w-full h-full">
                <path d="M12 4L12 20M12 20L18 14M12 20L6 14" stroke="#F59E0B" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
              </svg>
            </div>
          </div>
        </div>

        <!-- Step 10: Loading & First Consignment -->
        <div class="flex justify-center mb-8">
          <div class="relative">
            <div class="px-8 py-4 rounded-full border shadow-lg glassmorphism border-orange-400/30">
              <p class="max-w-md font-medium text-center text-white">
                LOADING - FIRST CONSIGNMENT WITHIN 30 DAYS AFTER CONFIRMATION OF LETTER OF CREDIT (LC) FROM BUYER'S BANK
              </p>
            </div>
            <!-- Arrow -->
            <div class="absolute right-0 top-full w-8 h-8 transform translate-x-1/2">
              <svg viewBox="0 0 24 24" fill="none" class="w-full h-full">
                <path d="M12 4L12 20M12 20L18 14M12 20L6 14" stroke="#F59E0B" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
              </svg>
            </div>
          </div>
        </div>

        <!-- Step 11: Payment -->
        <div class="flex justify-center">
          <div class="relative">
            <div class="px-8 py-4 rounded-full border shadow-lg glassmorphism border-orange-400/30">
              <p class="max-w-md font-medium text-center text-white">
                PAYMENT WITHIN 3 DAYS AFTER HANDING OVER THE DOCUMENTS
              </p>
            </div>
          </div>
        </div>
      </div>

      <!-- How Each Step Works Section -->
      <div class="mt-20">
        <div class="mb-12 text-center">
          <h3 class="mb-4 text-3xl font-bold text-white">
            HOW EACH STEP WORKS
          </h3>
          <div class="mx-auto w-20 h-1 rounded-full bg-gold-500"></div>
        </div>

        <div class="grid grid-cols-1 gap-8 md:grid-cols-2 lg:grid-cols-3">
          <!-- Step 1 Details -->
          <div class="text-center">
            <div class="inline-flex justify-center items-center mb-4 w-20 h-12 rounded-full border glassmorphism border-purple-400/30">
              <span class="font-bold text-white">STEP 1</span>
            </div>
            <div class="p-6 text-left rounded-lg border glassmorphism border-purple-400/30">
              <p class="text-sm leading-relaxed text-white">
                The customer initiates the trade process by providing a Letter of Intent (LOI), which formally expresses their interest in purchasing specific goods. Alongside the LOI, proof of funds is provided to assure Sterling that the customer has the financial capability to complete the transaction.
              </p>
            </div>
          </div>

          <!-- Step 2 Details -->
          <div class="text-center">
            <div class="inline-flex justify-center items-center mb-4 w-20 h-12 rounded-full border glassmorphism border-purple-400/30">
              <span class="font-bold text-white">STEP 2</span>
            </div>
            <div class="p-6 text-left rounded-lg border glassmorphism border-purple-400/30">
              <p class="text-sm leading-relaxed text-white">
                After receiving the LOI and verifying proof of funds, MIGBEN prepares and sends a Full Corporate Offer (FCO). This document outlines the terms of the offer, including product details, pricing, quantity, delivery terms, and other relevant conditions.
              </p>
            </div>
          </div>

          <!-- Step 3 Details -->
          <div class="text-center">
            <div class="inline-flex justify-center items-center mb-4 w-20 h-12 rounded-full border glassmorphism border-purple-400/30">
              <span class="font-bold text-white">STEP 3</span>
            </div>
            <div class="p-6 text-left rounded-lg border glassmorphism border-purple-400/30">
              <p class="text-sm leading-relaxed text-white">
                The buyer reviews the FCO, agrees to the terms, and confirms their acceptance by issuing an Irrevocable Corporate Purchase Order (ICPO). The ICPO is a formal commitment to purchase and is legally binding.
              </p>
            </div>
          </div>

          <!-- Step 4 Details -->
          <div class="text-center">
            <div class="inline-flex justify-center items-center mb-4 w-20 h-12 rounded-full border glassmorphism border-blue-400/30">
              <span class="font-bold text-white">STEP 4</span>
            </div>
            <div class="p-6 text-left rounded-lg border glassmorphism border-blue-400/30">
              <p class="text-sm leading-relaxed text-white">
                Based on the ICPO, MIGBEN issues a Proforma Invoice. This document provides a detailed breakdown of costs, including product price, freight, and any additional charges. It acts as a preliminary invoice for the buyer's reference.
              </p>
            </div>
          </div>

          <!-- Step 5 Details -->
          <div class="text-center">
            <div class="inline-flex justify-center items-center mb-4 w-20 h-12 rounded-full border glassmorphism border-blue-400/30">
              <span class="font-bold text-white">STEP 5</span>
            </div>
            <div class="p-6 text-left rounded-lg border glassmorphism border-blue-400/30">
              <p class="text-sm leading-relaxed text-white">
                The buyer arranges a draft of the Letter of Credit (LC) through their bank. This draft ensures the buyer's payment obligations are backed by their financial institution, providing security for both parties.
              </p>
            </div>
          </div>

          <!-- Step 6 Details -->
          <div class="text-center">
            <div class="inline-flex justify-center items-center mb-4 w-20 h-12 rounded-full border glassmorphism border-blue-400/30">
              <span class="font-bold text-white">STEP 6</span>
            </div>
            <div class="p-6 text-left rounded-lg border glassmorphism border-blue-400/30">
              <p class="text-sm leading-relaxed text-white">
                Both parties engage in final negotiations to clarify and agree upon the terms of the Sales Purchase Agreement (SPA). Once satisfied, the SPA is signed, making the agreement official and binding.
              </p>
            </div>
          </div>

          <!-- Step 7 Details -->
          <div class="text-center">
            <div class="inline-flex justify-center items-center mb-4 w-20 h-12 rounded-full border glassmorphism border-gold-400/30">
              <span class="font-bold text-white">STEP 7</span>
            </div>
            <div class="p-6 text-left rounded-lg border glassmorphism border-gold-400/30">
              <p class="text-sm leading-relaxed text-white">
                The buyer activates the financial instrument, typically a confirmed, Irrevocable, transferable Letter of Credit (LC). This instrument guarantees payment upon fulfilling the conditions of the agreement.
              </p>
            </div>
          </div>

          <!-- Step 8 Details -->
          <div class="text-center">
            <div class="inline-flex justify-center items-center mb-4 w-20 h-12 rounded-full border glassmorphism border-gold-400/30">
              <span class="font-bold text-white">STEP 8</span>
            </div>
            <div class="p-6 text-left rounded-lg border glassmorphism border-gold-400/30">
              <p class="text-sm leading-relaxed text-white">
                Upon confirmation of the LC, MIGBEN begins preparing the goods. This involves procurement, quality checks, packaging, and ensuring the products meet the agreed specifications.
              </p>
            </div>
          </div>

          <!-- Step 9 Details -->
          <div class="text-center">
            <div class="inline-flex justify-center items-center mb-4 w-20 h-12 rounded-full border glassmorphism border-gold-400/30">
              <span class="font-bold text-white">STEP 9</span>
            </div>
            <div class="p-6 text-left rounded-lg border glassmorphism border-gold-400/30">
              <p class="text-sm leading-relaxed text-white">
                Before shipment, an inspection is conducted to verify the quality, quantity, and compliance of the goods with the buyer's requirements. This step ensures the shipment meets international standards and buyer expectations.
              </p>
            </div>
          </div>

          <!-- Step 10 Details -->
          <div class="text-center">
            <div class="inline-flex justify-center items-center mb-4 w-20 h-12 rounded-full border glassmorphism border-orange-400/30">
              <span class="font-bold text-white">STEP 10</span>
            </div>
            <div class="p-6 text-left rounded-lg border glassmorphism border-orange-400/30">
              <p class="text-sm leading-relaxed text-white">
                The first consignment is scheduled for loading and shipped within 30 days of LC confirmation from the buyer's bank. All necessary documentation for customs and transport is prepared during this phase.
              </p>
            </div>
          </div>

          <!-- Step 11 Details -->
          <div class="text-center">
            <div class="inline-flex justify-center items-center mb-4 w-20 h-12 rounded-full border glassmorphism border-orange-400/30">
              <span class="font-bold text-white">STEP 11</span>
            </div>
            <div class="p-6 text-left rounded-lg border glassmorphism border-orange-400/30">
              <p class="text-sm leading-relaxed text-white">
                After shipment, MIGBEN hands over the shipping documents to their bank, including the bill of lading, packing list, and certificate of origin to release the payment within 3 days of submission.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
// Component logic can be added here if needed
</script>

<style scoped>
/* Enhanced shadow for the pill shapes */
.shadow-lg {
  box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
}
</style>
