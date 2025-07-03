<template>
  <aside class="w-64 bg-sidebar text-white flex flex-col p-4 shadow-lg">
    <div class="flex items-center justify-center mb-8 mt-2">
      <span class="text-2xl font-bold text-primary">Admin Panel</span>
    </div>
    <nav class="flex-1">
      <ul>
        <li class="mb-2">
          <NuxtLink to="/" class="flex items-center p-3 rounded-lg text-text-secondary hover:bg-gray-700 hover:text-white transition-colors duration-200" active-class="bg-primary text-white">
            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="mr-3"><path d="M3 9l9-7 9 7v11a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z"></path><polyline points="9 22 9 12 15 12 15 22"></polyline></svg>
            Dashboard
          </NuxtLink>
        </li>
        <li class="mb-2">
          <NuxtLink to="/scheduler" class="flex items-center p-3 rounded-lg text-text-secondary hover:bg-gray-700 hover:text-white transition-colors duration-200" active-class="bg-primary text-white">
            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="mr-3"><path d="M6 2v6h.01L6 8.01A3 3 0 1 0 9 5H6V2zm3 14H6v-3h3a3 3 0 1 0-3-3v3h3zm-3 4v-3h3a3 3 0 1 0-3-3v3h3z"></path><path d="M12 2v6h.01L12 8.01A3 3 0 1 0 15 5H12V2zm3 14H12v-3h3a3 3 0 1 0-3-3v3h3zm-3 4v-3h3a3 3 0 1 0-3-3v3h3z"></path><path d="M18 2v6h.01L18 8.01A3 3 0 1 0 21 5H18V2zm3 14h-3v-3h3a3 3 0 1 0-3-3v3h3zm-3 4v-3h3a3 3 0 1 0-3-3v3h3z"></path></svg>
            Scheduler
          </NuxtLink>
        </li>
        <li class="mb-2">
          <NuxtLink to="/message-templates" class="flex items-center p-3 rounded-lg text-text-secondary hover:bg-gray-700 hover:text-white transition-colors duration-200" active-class="bg-primary text-white">
            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="mr-3"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"></path><polyline points="22,6 12,13 2,6"></polyline></svg>
            Mesaj Şablonları
          </NuxtLink>
        </li>
        <li class="mb-2">
          <NuxtLink to="/projects" class="flex items-center p-3 rounded-lg text-text-secondary hover:bg-gray-700 hover:text-white transition-colors duration-200" active-class="bg-primary text-white">
            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="mr-3"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg>
            Proje Yönetimi
          </NuxtLink>
        </li>
      </ul>
    </nav>
  </aside>
</template>

<script setup>
// No script needed for now
</script>
