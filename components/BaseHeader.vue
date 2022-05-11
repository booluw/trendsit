<template>
  <header
    class="bg-black text-white py-5 px-5 md:px-12 md:py-7 relative flex justify-between items-center z-50"
  >
    <nuxt-link to="/" class="text-white text-2xl hover:text-opacity-75">
      Trends <span class="text-pink-500">IT</span>
    </nuxt-link>
    <div class="flex items-center">
      <nav class="hidden md:flex font-bold">
        <nuxt-link to="/" class="text-gray-300 mr-5" exact-active-class="text-pink-500">Home</nuxt-link>
        <nuxt-link :to="{ path: '',hash:'#about-us'}" class="text-gray-300 mr-5" exact-active-class="text-pink-500">About Us</nuxt-link>
        <nuxt-link :to="{ path: '/',hash:'#clients'}" class="text-gray-300 mr-5" exact-active-class="text-pink-500">Clients</nuxt-link>
        <nuxt-link :to="{ path: '/services'}" class="text-gray-300 mr-5" exact-active-class="text-pink-500">Services</nuxt-link>
        <nuxt-link to="/products" class="text-gray-300 mr-5" exact-active-class="text-pink-500">Products</nuxt-link>
      </nav>
      <div class="md:hidden space-y-2 cursor-pointer" @click="openMenu()">
        <span class="block w-5 h-0.5 bg-gray-300 hover:bg-gray-100"></span>
        <span class="block w-8 h-0.5 bg-gray-300 hover:bg-gray-100"></span>
      </div>
    </div>
    <!-- Menu -->
    <div class="fixed top-0 right-0 bottom-0 left-0 md:left-auto bg-black opacity-100 flex flex-col py-24" v-if="burger">
      <svg class="h-6 w-6 text-gray-400 cursor-pointer hover:text-gray-500 absolute top-8 right-12" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" @click="closeMenu()">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
      </svg>
      <ul class="px-5 menu">
        <li class="mb-5">
          <nuxt-link to="/" class="text-gray-300 mr-5" exact-active-class="text-pink-500">Home</nuxt-link>
        </li>
        <li class="mb-5">
          <nuxt-link :to="{ path: '',hash:'#about-us'}" class="text-gray-300 mr-5" exact-active-class="text-pink-500">About Us</nuxt-link>
        </li>
        <li class="mb-5">
          <nuxt-link :to="{ path: '/',hash:'#clients'}" class="text-gray-300 mr-5" exact-active-class="text-pink-500">Clients</nuxt-link>
        </li>
        <li class="mb-5">
          <nuxt-link :to="{ path: '/services'}" class="text-gray-300 mr-5" exact-active-class="text-pink-500">Services</nuxt-link>
        </li>
        <li class="mb-5">
          <nuxt-link to="/products" class="text-gray-300 mr-5" exact-active-class="text-pink-500">Products</nuxt-link>
        </li>
      </ul>
    </div>
  </header>
</template>

<script>
// import { gsap, Expo } from 'gsap'

export default {
  data() {
    return {
      burger: false
    }
  },
  methods: {
    openMenu() {
      this.burger = true
    },
    closeMenu() {
      this.burger = false
    }
  },
  watch: {
    $route: {
      handler: function() {
        this.burger = false
      }
    }
  }
}
</script>