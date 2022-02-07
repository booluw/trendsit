<template>
  <header
    class="bg-black text-white py-5 px-5 md:px-12 md:py-7 relative flex justify-between items-center z-50"
  >
    <div class="text-white text-2xl">
      Trends <span class="text-pink-500">IT</span>
    </div>
    <div class="space-y-2 cursor-pointer" @click="openMenu()">
      <span class="block w-5 h-0.5 bg-gray-300 hover:bg-gray-100"></span>
      <span class="block w-8 h-0.5 bg-gray-300 hover:bg-gray-100"></span>
    </div>
    <!-- Menu -->
    <div class="lg:w-1/4 fixed top-0 right-0 bottom-0 left-0 md:left-auto bg-black opacity-100 flex flex-col py-24" v-if="burger">
      <svg class="h-6 w-6 text-gray-400 cursor-pointer hover:text-gray-500 absolute top-8 right-12" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" @click="closeMenu()">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
      </svg>
      <ul class="px-5 menu">
        <li class="mb-5">
          <nuxt-link to="/" class="menu__link text-gray-400 text-2xl p-3 hover:text-pink-300 ease-in-out duration-300" exact-active-class="text-pink-400">Home</nuxt-link>
        </li>
        <li class="mb-5">
          <nuxt-link to="/about" class="menu__link text-gray-400 text-2xl p-3 hover:text-pink-300 ease-in-out duration-300" exact-active-class="text-pink-400">About</nuxt-link>
        </li>
        <li class="mb-5">
          <nuxt-link to="/page" class="menu__link text-gray-400 text-2xl p-3 hover:text-pink-300 ease-in-out duration-300" exact-active-class="text-pink-400">Page</nuxt-link>
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
    openMenu() {/*
      let tl = gsap.timeline();
      tl.from('.menu__link', {opacity: .6, y: -3}) */
      this.burger = true
    },
    closeMenu() {
      this.burger = false
    }
  }
}
</script>