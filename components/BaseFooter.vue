<template>
  <footer class="bg-black text-white px-5 py-14 md:px-20 md:py-14">
    <div class="md:flex">
      <div class="md:basis-1/3 md:w-1/3">
        <h1 class="text-4xl font-bold text-pink-600">Trends IT <br />Services</h1>
        <p class="text-gray-400 my-4">
          Trends IT Services is a network services and sustainable energy installation and project service rendering company targeted at training and optimizing work operations in organizations.
        </p>
        <div class="pt-4 md:flex md:gap-2 justify-between md:justify-start flex-wrap">
          <a href="tel:+2348083981055" class="text-white hover:text-pink-600 ease-in-out block md:mr-5" target="_blank">+234 808 398 1055</a>
          <a href="mailto:info.trendsit@gmail.com" class="text-white hover:text-pink-600 ease-in-out block w-full" target="_blank">info.trendsit@gmail.com</a>
        </div>
        <div class="gap-9 pt-4 hidden md:flex text-gray-500">&copy; {{ currentDate.getFullYear() }}</div>
      </div>
      <div class="md:basis-1/3 md:w-1/3 md:ml-24 mt-10 md:mt-0">
        <h3 class="text-gray-700 text-2xl font-bold">Office addresses</h3>
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
          <a href="https://facebook.com/trenditservices" class="text-white hover:text-pink-600 ease-in-out block" target="_blank">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 64 64" style="fill:#db2777;" class="w-10 h-auto hover:opacity-75">
              <path d="M32,6C17.642,6,6,17.642,6,32c0,13.035,9.603,23.799,22.113,25.679V38.89H21.68v-6.834h6.433v-4.548	c0-7.529,3.668-10.833,9.926-10.833c2.996,0,4.583,0.223,5.332,0.323v5.965h-4.268c-2.656,0-3.584,2.52-3.584,5.358v3.735h7.785	l-1.055,6.834h-6.73v18.843C48.209,56.013,58,45.163,58,32C58,17.642,46.359,6,32,6z"></path>
            </svg>
          </a>
          <a href="https://instagram.com/trenditservices" class="text-white hover:text-pink-600 ease-in-out block" target="_blank">
            <svg viewBox="0 0 64 64" style="fill:#db2777;" class="w-10 h-auto hover:opacity-75">
              <path d="M 21.580078 7 C 13.541078 7 7 13.544938 7 21.585938 L 7 42.417969 C 7 50.457969 13.544938 57 21.585938 57 L 42.417969 57 C 50.457969 57 57 50.455062 57 42.414062 L 57 21.580078 C 57 13.541078 50.455062 7 42.414062 7 L 21.580078 7 z M 47 15 C 48.104 15 49 15.896 49 17 C 49 18.104 48.104 19 47 19 C 45.896 19 45 18.104 45 17 C 45 15.896 45.896 15 47 15 z M 32 19 C 39.17 19 45 24.83 45 32 C 45 39.17 39.169 45 32 45 C 24.83 45 19 39.169 19 32 C 19 24.831 24.83 19 32 19 z M 32 23 C 27.029 23 23 27.029 23 32 C 23 36.971 27.029 41 32 41 C 36.971 41 41 36.971 41 32 C 41 27.029 36.971 23 32 23 z"></path>
            </svg>
          </a>
          <a href="https://twitter.com/@trenditservices" class="text-white hover:text-pink-600 ease-in-out block" target="_blank">
            <svg viewBox="0 0 64 64" style="fill:#db2777;" class="w-10 h-auto hover:opacity-75">
              <path d="M61.932,15.439c-2.099,0.93-4.356,1.55-6.737,1.843c2.421-1.437,4.283-3.729,5.157-6.437	c-2.265,1.328-4.774,2.303-7.444,2.817C50.776,11.402,47.735,10,44.366,10c-6.472,0-11.717,5.2-11.717,11.611	c0,0.907,0.106,1.791,0.306,2.649c-9.736-0.489-18.371-5.117-24.148-12.141c-1.015,1.716-1.586,3.726-1.586,5.847	c0,4.031,2.064,7.579,5.211,9.67c-1.921-0.059-3.729-0.593-5.312-1.45c0,0.035,0,0.087,0,0.136c0,5.633,4.04,10.323,9.395,11.391	c-0.979,0.268-2.013,0.417-3.079,0.417c-0.757,0-1.494-0.086-2.208-0.214c1.491,4.603,5.817,7.968,10.942,8.067	c-4.01,3.109-9.06,4.971-14.552,4.971c-0.949,0-1.876-0.054-2.793-0.165C10.012,54.074,16.173,56,22.786,56	c21.549,0,33.337-17.696,33.337-33.047c0-0.503-0.016-1.004-0.04-1.499C58.384,19.83,60.366,17.78,61.932,15.439"></path>
            </svg>
          </a>
        </div>
      </div>
      <!--- div class="md:basis-1/3 md:w-1/3 md:ml-24 mt-10 md:mt-0 hidden md:block">
        <h3 class="text-gray-700 text-2xl font-bold">Send a message</h3>
        <form
          class="mt-4"
          name="contact"
          method="POST"
          action="/pages/success"
          data-netlify="true"
        >
          <label for="email">
            <div class="mb-2">Your Email</div>
            <input
              id="email"
              name="email"
              type="email"
              class="md:p-3 rounded-sm border-b-2 bg-opacity-30 bg-white focus:outline-none focus:border-pink-600 w-full"
              placeholder="JohnDoe@company.com"
              required
            />
          </label>
          <label for="fullname" class="block mt-5">
            <div class="mb-2">Your Full Name</div>
            <input
              id="fullname"
              name="fullname"
              type="text"
              class="md:p-3 rounded-sm border-b-2 bg-opacity-30 bg-white focus:outline-none focus:border-pink-600 w-full"
              placeholder="John Doe"
              required
            />
          </label>
          <label for="message" class="block mt-5">
            <div class="mb-2">Your Message</div>
            <textarea
              id="message"
              name="message"
              class="md:p-3 rounded-sm border-b-2 bg-opacity-30 bg-white focus:outline-none focus:border-pink-600 w-full"
              placeholder="Lorem Ipsum"
            ></textarea>
          </label>
          <button
            type="submit"
            class="mt-4 p-4 bg-pink-600 w-full"
          >
            Send
          </button>
        </form>
      </div --->
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
