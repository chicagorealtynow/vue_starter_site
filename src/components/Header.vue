<template>
  <header class="bg-white shadow-md">
    <nav class="container mx-auto px-6 py-4">
      <div class="flex justify-between items-center">
        <div class="text-xl font-bold text-gray-800">Business Corp</div>
        <div class="hidden md:flex space-x-8">
          <router-link v-for="item in menuItems" 
            :key="item.path" 
            :to="item.path"
            class="text-gray-600 hover:text-gray-900 transition-colors">
            {{ item.name }}
          </router-link>
        </div>
      </div>
    </nav>
  </header>
</template>

<script setup>
const menuItems = [
  { name: 'Home', path: '/' },
  { name: 'Services', path: '/services' },
  { name: 'About', path: '/about' },
  { name: 'Contact', path: '/contact' }
]
</script>