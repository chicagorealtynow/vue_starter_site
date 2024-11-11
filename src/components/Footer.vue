<template>
  <footer class="bg-gray-800 text-white mt-auto">
    <div class="container mx-auto px-6 py-8">
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <div>
          <h3 class="text-lg font-semibold mb-4">Business Corp</h3>
          <p class="text-gray-400">Providing innovative solutions since 1970</p>
        </div>
        <div>
          <h3 class="text-lg font-semibold mb-4">Quick Links</h3>
          <ul class="space-y-2">
            <li v-for="item in menuItems" :key="item.path">
              <router-link :to="item.path" class="text-gray-400 hover:text-white transition-colors">
                {{ item.name }}
              </router-link>
            </li>
          </ul>
        </div>
        <div>
          <h3 class="text-lg font-semibold mb-4">Contact</h3>
          <p class="text-gray-400">123 Business Street</p>
          <p class="text-gray-400">Enterprise City, EC 12345</p>
          <p class="text-gray-400">contact@businesscorp.com</p>
        </div>
      </div>
      <div class="border-t border-gray-700 mt-8 pt-8 text-center text-gray-400">
        <p>&copy; 1970 Business Corp. All rights reserved.</p>
      </div>
    </div>
  </footer>
</template>

<script setup>
const menuItems = [
  { name: 'Home', path: '/' },
  { name: 'Services', path: '/services' },
  { name: 'About', path: '/about' },
  { name: 'Contact', path: '/contact' }
]
</script>