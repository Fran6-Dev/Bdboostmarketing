<template>
  <section
    class="py-24 bg-gradient-to-b from-black to-gray-900 relative overflow-hidden"
  >
    <!-- Effet de grille en arrière-plan avec animation -->
    <div
      class="absolute inset-0 bg-[linear-gradient(rgba(0,163,108,0.1)_1px,transparent_1px),linear-gradient(90deg,rgba(0,163,108,0.1)_1px,transparent_1px)] bg-[size:4rem_4rem] [mask-image:radial-gradient(ellipse_60%_50%_at_50%_0%,#000_70%,transparent_100%)] animate-grid"
    ></div>

    <div class="container mx-auto px-4 relative">
      <!-- Section Hero -->
      <div
        class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center mb-24 mt-16"
      >
        <div class="max-w-xl animate-fade-in-up">
          <div class="inline-block mb-6">
            <span class="px-6 py-2.5 bg-gradient-to-r from-[#00A36C]/20 to-[#00A36C]/10 text-[#00A36C] rounded-full text-sm font-medium">Marketing Digital</span>
          </div>
          <h1 class="text-5xl font-bold text-white mb-6 leading-tight">
            Donner du pouvoir aux marques avec des solutions de marketing basées
            sur
            <span class="text-[#00A36C] relative inline-block group">
              les données
              <span class="absolute -bottom-1 left-0 w-full h-0.5 bg-[#00A36C] transform scale-x-0 group-hover:scale-x-100 transition-transform duration-300"></span>
            </span>
          </h1>
          <p class="text-lg text-gray-300 mb-8 leading-relaxed">
            Dédié à l'élaboration de stratégies percutantes qui se connectent
            avec le public, permettent de générer des résultats mesurables et de
            favoriser une croissance significative
          </p>
          <div class="flex flex-wrap gap-4 mb-8">
            <div class="flex items-center space-x-2 text-gray-300">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-[#00A36C]" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
              </svg>
              <span>Stratégies sur mesure</span>
            </div>
            <div class="flex items-center space-x-2 text-gray-300">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-[#00A36C]" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
              </svg>
              <span>Résultats mesurables</span>
            </div>
            <div class="flex items-center space-x-2 text-gray-300">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-[#00A36C]" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
              </svg>
              <span>Croissance durable</span>
            </div>
          </div>
          <button
            class="bg-[#00A36C] hover:bg-[#008F5E] text-white px-8 py-3 rounded-lg transition-all duration-300 hover:-translate-y-0.5 shadow-lg hover:shadow-[#00A36C]/20 font-medium relative overflow-hidden group"
          >
            <span class="absolute inset-0 bg-white/20 transform scale-x-0 group-hover:scale-x-100 transition-transform origin-left duration-300"></span>
            <a
              href="https://form.typeform.com/to/FAk2O04a"
              class="text-white no-underline font-medium relative z-10"
            >
              Contactez-nous
            </a>
          </button>
        </div>
        <div class="flex justify-center items-center animate-fade-in-up delay-200">
          <div class="relative group">
            <div
              class="absolute -inset-4 bg-gradient-to-r from-[#00A36C] to-[#008F5E] rounded-2xl blur opacity-30 group-hover:opacity-50 transition-opacity duration-300"
            ></div>
            <div class="relative bg-gray-900/50 backdrop-blur-sm p-8 rounded-2xl border border-gray-800">
              <img
                src="../assets/chiffrebb.png"
                alt="chiffre bb"
                class="relative max-w-full h-auto rounded-xl shadow-2xl transform group-hover:scale-105 transition-transform duration-300"
              />
              <div class="mt-6 grid grid-cols-2 gap-4">
                <div class="text-center p-4 bg-gray-800/50 rounded-lg">
                  <div class="text-3xl font-bold text-[#00A36C] mb-1">+150%</div>
                  <div class="text-gray-300 text-sm">Engagement moyen</div>
                </div>
                <div class="text-center p-4 bg-gray-800/50 rounded-lg">
                  <div class="text-3xl font-bold text-[#00A36C] mb-1">24/7</div>
                  <div class="text-gray-300 text-sm">Support client</div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Section Partenaires -->
      <div class="relative">
        <div class="absolute inset-0 bg-gradient-to-b from-transparent via-[#00A36C]/5 to-transparent"></div>
        <div class="relative bg-black/50 backdrop-blur-sm rounded-2xl border border-gray-800 p-12">
          <div class="text-center mb-12">
            <span class="px-6 py-2.5 bg-gradient-to-r from-[#00A36C]/20 to-[#00A36C]/10 text-[#00A36C] rounded-full text-sm font-medium mb-4">Nos partenaires</span>
            <h2 class="text-3xl font-bold text-white m-4">Ils nous font confiance</h2>
            <p class="text-gray-300 max-w-2xl mx-auto">
              Rejoignez les rangs des nombreuses marques que nous avons aidées à
              atteindre une croissance constante
            </p>
          </div>
          <div class="grid grid-cols-1 md:grid-cols-3 gap-8 max-w-4xl mx-auto">
            <div
            >
              <img
                src="../assets/logonts.png"
                alt="logo nts"
                class="h-16 w-auto mx-auto opacity-80 hover:opacity-100 transition-all duration-300"
              />
            </div>
            <div
            >
              <img
                src="../assets/logodelta.png"
                alt="logo delta"
                class="h-16 w-auto mx-auto opacity-80 hover:opacity-100 transition-all duration-300"
              />
            </div>
            <div
            >
              <img
                src="../assets/logobsb.png"
                alt="logo nts"
                class="h-16 w-auto mx-auto opacity-80 hover:opacity-100 transition-all duration-300"
              />
            </div>
          </div>
          <div class="text-center mt-8">
            <p class="text-gray-400 italic">... et bien d'autres</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup></script>

<style scoped>
@keyframes grid {
  0% {
    transform: translateY(0);
  }
  100% {
    transform: translateY(4rem);
  }
}

.animate-grid {
  animation: grid 20s linear infinite;
}

@keyframes fade-in-up {
  from {
    opacity: 0;
    transform: translateY(20px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

.animate-fade-in-up {
  animation: fade-in-up 0.6s ease-out forwards;
}

.delay-200 {
  animation-delay: 200ms;
}
</style>
