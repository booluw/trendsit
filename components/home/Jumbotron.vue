<template>
  <section class="relative text-gray-300 text-center bg-clip-border bg-center bg-no-repeat bg-cover -z-50" :style="
    [{ backgroundImage: 'url(' + require('~/assets/img/golden-switch.jpg') + ')'}, {height: '80vh'}]" id="hero-text">
    <div class="absolute inset-0 bg-opacity-70 bg-black py-52 flex flex-col items-center content-between">
      <div class="text-2xl md:text-4xl uppercase font-bold text-reveal">
        Quality Technology Service you can trust
      </div>
      <div class="text-1xl md:text-2xl text-reveal mt-7 md:mt-20 md:w-3/4 px-2 md:px-0">
        Trends IT Services is a <i>network services</i> and sustainable energy installation and project service rendering company targeted at training and optimizing work operations in organizations.
      </div>
    </div>
  </section>
</template>

<script>
import { gsap, Expo } from 'gsap'

export default {
  name: 'Jumbotron',
  mounted() {
    let tl = gsap.timeline();

    tl.from('#hero-text', { scale: 0.9, duration: 1, opacity: 0, ease: Expo.EaseOut})
     .to('.text-reveal', { clipPath: 'polygon(0 0, 100% 0, 100% 100%, 0 100%)', y: 0, stagger: .3, duration: 1 }, "-=2.5")
  }
}
</script>

<style>
.text-reveal {
  transition: all 1.5s;
  transform: translateY(-3rem);
  clip-path: polygon(0 0, 100% 0, 100% 0, 0 0);
}
</style>