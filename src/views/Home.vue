<template>
  <div>
    <!-- Hero Section -->
    <div class="relative bg-gray-900 h-[600px]">
      <div class="absolute inset-0 bg-[url('https://images.unsplash.com/photo-1486406146926-c627a92ad1ab?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2070&q=80')] bg-cover bg-center opacity-50"></div>
      <div class="relative container mx-auto px-6 h-full flex items-center">
        <div class="text-white max-w-2xl">
          <h1 class="text-5xl font-bold mb-6">Building Tomorrow's Solutions Today</h1>
          <p class="text-xl mb-8">We help businesses transform their ideas into reality with cutting-edge solutions and innovative strategies.</p>
          <router-link to="/contact" class="bg-blue-600 hover:bg-blue-700 text-white px-8 py-3 rounded-lg inline-block transition-colors">
            Get Started
          </router-link>
        </div>
      </div>
    </div>

    <!-- Features Section -->
    <div class="py-20 bg-white">
      <div class="container mx-auto px-6">
        <div class="grid grid-cols-1 md:grid-cols-3 gap-12">
          <div class="text-center">
            <div class="text-4xl mb-4">💡</div>
            <h3 class="text-xl font-semibold mb-4">Innovative Solutions</h3>
            <p class="text-gray-600">Cutting-edge technology solutions tailored to your business needs</p>
          </div>
          <div class="text-center">
            <div class="text-4xl mb-4">🤝</div>
            <h3 class="text-xl font-semibold mb-4">Expert Team</h3>
            <p class="text-gray-600">Dedicated professionals with years of industry experience</p>
          </div>
          <div class="text-center">
            <div class="text-4xl mb-4">📈</div>
            <h3 class="text-xl font-semibold mb-4">Growth Focus</h3>
            <p class="text-gray-600">Strategies designed to scale your business effectively</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>