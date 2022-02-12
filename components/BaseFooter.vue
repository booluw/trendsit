<template>
  <footer class="bg-black text-white px-5 py-14 md:px-20 md:py-14">
    <div class="md:flex">
      <div class="md:basis-1/3 md:w-1/3">
        <h1 class="text-4xl font-bold text-pink-600">Trends IT <br />Services</h1>
        <p class="text-gray-400 my-4">
          Trends IT Services is a network services and sustainable energy installation and project service rendering company targeted at training and optimizing work operations in organizations.
        </p>
        <div class="pt-4 md:flex md:gap-2 justify-between md:justify-start flex-wrap">
          <a href="tel:+2348037022330" class="text-white hover:text-pink-600 ease-in-out block mb-3 md:mb-0" target="_blank">+234 803 702 2330</a>
          <a href="tel:+2348083981055" class="text-white hover:text-pink-600 ease-in-out block md:mr-5" target="_blank">+234 808 398 1055</a>
          <a href="mailto:info.trendsit@gmail.com" class="text-white hover:text-pink-600 ease-in-out block w-full" target="_blank">info.trendsit@gmail.com</a>
        </div>
        <div class="gap-9 pt-4 hidden md:flex text-gray-500">&copy; {{ currentDate.getFullYear() }}</div>
      </div>
      <div class="md:basis-1/3 md:w-1/3 md:ml-24 mt-10 md:mt-0">
        <h3 class="text-gray-800 text-2xl font-bold">Office addresses</h3>
        <div class="mt-5">
          <h3 class="inline text-gray-600 font-semibold">Niger State:</h3>
          <p class="inline">
            Opposite Federal University of Technology Minna, Trends IT Hub
          </p>
        </div>
        <div class="mt-5">
          <h3 class="inline text-gray-600 font-semibold">Abuja - FCT:</h3>
          <p class="inline">
            2F2, Threshold Business Suite, Plot 976, Olusegun Obasanjo Way, Wuye.
          </p>
        </div>
        <div class="mt-5">
          <h3 class="inline text-gray-600 font-semibold">Plateau State:</h3>
          <p class="inline">
            Opposite Corona School Rayfield, Jos.
          </p>
        </div>
        <div class="gap-9 pt-10 flex">
          <a href="https://facebook.com/trenditservices" class="text-white hover:text-pink-600 ease-in-out block" target="_blank">facebook</a>
          <a href="https://instagram.com/trenditservices" class="text-white hover:text-pink-600 ease-in-out block" target="_blank">instagram</a>
          <a href="https://twitter.com/@trenditservices" class="text-white hover:text-pink-600 ease-in-out block" target="_blank">twitter</a>
        </div>
      </div>
      <div class="mt-10 md:hidden block text-center text-gray-500">&copy; {{ currentDate.getFullYear() }}</div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'BaseFooter',
  data() {
    return {
      currentDate: new Date()
    }
  },
}
</script>
