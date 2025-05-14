<template>
  <footer class="bg-black text-white py-12">
    <div class="container mx-auto px-4">
     
      <div class="flex flex-col md:flex-row justify-between items-center pt-6 border-t border-gray-800">
        <p class="text-sm text-gray-500 mb-4 md:mb-0">
          © {{ new Date().getFullYear() }} BB Marketing. Tous droits réservés.
        </p>
        <div class="flex gap-6">
          <a href="https://www.instagram.com/bdboostmarketing/" class="text-gray-400 hover:text-[#00A36C] transition-colors duration-300">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="w-6 h-6">
              <rect x="2" y="2" width="20" height="20" rx="5" ry="5"></rect>
              <path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"></path>
              <line x1="17.5" y1="6.5" x2="17.51" y2="6.5"></line>
            </svg>
          </a>
        </div>
      </div>
    </div>
  </footer>
</template>

<script setup>
// Le script est vide car nous n'avons pas besoin de logique spécifique
</script>
