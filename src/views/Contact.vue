<template>
  <div class="container mx-auto px-6 py-12">
    <h1 class="text-4xl font-bold text-center mb-12">Contact Us</h1>
    <div class="max-w-2xl mx-auto">
      <form class="space-y-6">
        <div>
          <label class="block text-gray-700 mb-2" for="name">Name</label>
          <input type="text" id="name" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:border-blue-500">
        </div>
        <div>
          <label class="block text-gray-700 mb-2" for="email">Email</label>
          <input type="email" id="email" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:border-blue-500">
        </div>
        <div>
          <label class="block text-gray-700 mb-2" for="message">Message</label>
          <textarea id="message" rows="4" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:border-blue-500"></textarea>
        </div>
        <button type="submit" class="bg-blue-600 text-white px-6 py-2 rounded-lg hover:bg-blue-700 transition-colors">
          Send Message
        </button>
      </form>
    </div>
  </div>
</template>