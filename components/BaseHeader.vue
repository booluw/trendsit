<template>
  <header
    class="bg-gray-900 text-white py-5 px-5 md:px-12 md:py-7 sticky top-0 flex justify-between items-center"
  >
    <div class="text-white text-2xl">
      Trends <span class="text-green-500">IT</span>
    </div>
    <div class="space-y-2 cursor-pointer" @click="openMenu()">
      <span class="block w-5 h-0.5 bg-gray-300 hover:bg-gray-100"></span>
      <span class="block w-8 h-0.5 bg-gray-300 hover:bg-gray-100"></span>
    </div>
    <!-- Menu -->
    <div class="lg:w-1/4 fixed top-0 right-0 bottom-0 left-0 md:left-auto bg-gray-800 opacity-100 flex flex-col items-center py-20" v-if="burger">
      <svg class="h-6 w-6 text-gray-400 cursor-pointer hover:text-gray-500 absolute top-5 right-5" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" @click="closeMenu()">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
      </svg>
      <ul>
        <li class="mb-5">
          <nuxt-link to="/" class="text-gray-400 text-2xl p-3 hover:text-green-300" exact-active-class="text-green-400">Home</nuxt-link>
        </li>
        <li class="mb-5">
          <nuxt-link to="/about" class="text-gray-400 text-2xl p-3 hover:text-green-300" exact-active-class="text-green-400">About</nuxt-link>
        </li>
        <li class="mb-5">
          <nuxt-link to="/page" class="text-gray-400 text-2xl p-3 hover:text-green-300" exact-active-class="text-green-400">Page</nuxt-link>
        </li>
      </ul>
    </div>
  </header>
</template>

<script>
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
  }
}
</script>

<style>

</style>