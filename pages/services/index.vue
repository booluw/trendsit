<template>
  <div>
    <section class="text-gray-300 relative bg-clip-border bg-center bg-no-repeat bg-cover -z-50 overflow-hidden"
    :style="[{ backgroundImage: 'url(' + require(`~/assets/img/${currentImg}`) + ')'}, {height: '50vh'}]">
      <div class="absolute inset-0 bg-opacity-70 bg-black pt-44 px-5 md:pt-32 md:px-20">
        <div class="text-4xl md:text-7xl md:w-1/3 uppercase font-bold">
          Services
        </div>
      </div>
    </section>
    
    <section class="text-gray-800 bg-white md:flex px-2 md:px-12 py-5 md:py-20 mb-10 items-center justify-end" id="wifi">
      <div class="md:basis-1/2 md:w-1/2 order-2">
        <img src="~/assets/img/wireless-network.jpg" class="h-full w-full rounded-2xl shadow-md object-contain" />
      </div>
      <div class="md:basis-1/2 md:w-1/2 py-5 md:py-10 md:px-14 order-1">
        <h3 class="text-md text-gray-700">Service:</h3>
        <h1 class="text-gray-500 text-4xl md:text-6xl font-bold mb-5">
          Internet Connectivity
        </h1>
        <p>
          Whether you need a VSAT internet connection, Microwave internet connection or Fibre optic internet connection, our team can help get you connected fast. We have a solution that will work for you. So why wait? Contact us today to get started!
          <br/><br/>
          <nuxt-link :to="{ path: '/services/internet-connectivity'}" class="inline-block px-8 py-3 border-2 border-pink-400 text-pink-400 hover:bg-pink-700 hover:text-white hover:border-pink-700">Click To Learn More</nuxt-link>
        </p>
      </div>
    </section>
    <section class="text-gray-800 bg-white md:flex px-2 md:px-12 py-5 md:py-20 mb-10 items-center justify-end" id="network-design">
      <div class="md:basis-1/2 md:w-1/2">
        <img src="~/assets/img/custom-network-design.jpg" class="h-full w-full rounded-2xl shadow-md object-contain" />
      </div>
      <div class="md:basis-1/2 md:w-1/2 py-5 md:py-10 md:px-14">
        <h3 class="text-md text-gray-400">Service:</h3>
        <h1 class="text-gray-800 text-4xl md:text-6xl font-bold mb-5">
          Custom Network Design and Integration
        </h1>
        <p>
          We understand that your business is unique and has a variety of requirements. That's why we offer customized network solutions to meet all those needs!
        </p>
        <ul class="list-disc text-gray-500">
          <li class="pl-5 mt-3 border-l-2 border-gray-500">
            Local Area Network (LAN)
          </li>
          <li class="pl-5 mt-3 border-l-2 border-gray-500">
            Wireless LAN (WLAN)
          </li>
          <li class="pl-5 mt-3 border-l-2 border-gray-500">
            SOHO and SMB Wireless Networking Solutions
          </li>
          <li class="pl-5 mt-3 border-l-2 border-gray-500">
            Campus Network
          </li>
          <li class="pl-5 mt-3 border-l-2 border-gray-500">
            VoIP
          </li>
          <li class="pl-5 mt-3 border-l-2 border-gray-500">
            Teleconference
          </li>
        </ul>
        <br/><br/>
        <nuxt-link :to="{ path: '/services/custom-network-design'}" class="inline-block px-8 py-3 border-2 border-pink-700 text-pink-700 hover:bg-pink-700 hover:text-white hover:border-pink-700">Click To Learn More</nuxt-link>
      </div>
    </section>
    <section class="text-gray-800 bg-white md:flex px-2 md:px-12 py-5 md:py-20 mb-10 items-center justify-end" id="sustainable-energy">
      <div class="md:basis-1/2 md:w-1/2 order-2">
        <img src="~/assets/img/sustainable-energy.jpg" class="h-full w-full rounded-2xl shadow-md object-contain" />
      </div>
      <div class="md:basis-1/2 md:w-1/2 py-5 md:py-10 md:px-14 order-1">
        <h3 class="text-md text-gray-700">Service:</h3>
        <h1 class="text-gray-500 text-4xl md:text-6xl font-bold mb-5">
          Renewable Energy
        </h1>
        <p>
          We offer a wide range of energy solutions tailored to your usage and logistics needs.
        </p>
        <ul class="list-disc text-gray-500">
          <li class="pl-5 mt-3 border-l-2 border-gray-500">
            Solar powered street light installations
          </li>
          <li class="pl-5 mt-3 border-l-2 border-gray-500">
            Solar powered traffic lights
          </li>
          <li class="pl-5 mt-3 border-l-2 border-gray-500">
            Office and commercial system solution
          </li>
          <li class="pl-5 mt-3 border-l-2 border-gray-500">
            Solar Home System (SHS)
          </li>
          <li class="pl-5 mt-3 border-l-2 border-gray-500">
            Service support/maintenance
          </li>
        </ul>
      </div>
    </section>
    <section class="text-gray-800 bg-white md:flex px-2 md:px-12 py-5 md:py-20 mb-10 items-center justify-end" id="systems-analysis">
      <div class="md:basis-1/2 md:w-1/2">
        <img src="~/assets/img/system-analysis.jpg" class="h-full w-full rounded-2xl shadow-md object-contain
        " />
      </div>
      <div class="md:basis-1/2 md:w-1/2 py-5 md:py-10 md:px-14">
        <h3 class="text-md text-gray-400">Service:</h3>
        <h1 class="text-gray-800 text-4xl md:text-6xl font-bold mb-5">
          IT Security
        </h1>
        <p>
          Our security solutions helps keep your personal and organization’s connected ecosystem safe. We provide
        </p>
        <ul class="list-disc text-gray-500">
          <li class="pl-5 mt-3 border-l-2 border-gray-500">
            CCTV Installation
          </li>
          <li class="pl-5 mt-3 border-l-2 border-gray-500">
            Smart Home Security (access point, smart locks, etc.)
          </li>
          <li class="pl-5 mt-3 border-l-2 border-gray-500">
            Data Protection, Network Forensics and Backup Solutions
          </li>
          <li class="pl-5 mt-3 border-l-2 border-gray-500">
            Car Tracking and Fleet Management
          </li>
        </ul>
        <br/><br/>
        <nuxt-link :to="{ path: '/services/it-security'}" class="inline-block px-8 py-3 border-2 border-pink-700 text-pink-700 hover:bg-pink-700 hover:text-white hover:border-pink-700">Click To Learn More</nuxt-link>
      </div>
    </section>
    <section class="text-gray-800 bg-white md:flex px-2 md:px-12 py-5 md:py-20 mb-10 items-center justify-end" id="sustainable-energy">
      <div class="md:basis-1/2 md:w-1/2 order-2">
        <img src="~/assets/img/it-training.jpg" class="h-full w-full rounded-2xl shadow-md object-contain" />
      </div>
      <div class="md:basis-1/2 md:w-1/2 py-5 md:py-10 md:px-14 order-1">
        <h3 class="text-md text-gray-700">Service:</h3>
        <h1 class="text-gray-500 text-4xl md:text-6xl font-bold mb-5">
          Training & <br />Support
        </h1>
        <p>
          We offer after-sales service support and training, and also organize special on-demand trainings on any of our listed services above.
          <br />
          Our team of experts will take you by the hand and train you from start to finish, we are here to help you.
        </p>
      </div>
    </section>
  </div>
</template>
<script>
import { gsap, Expo } from 'gsap'

export default {
  name: 'Jumbotron',
  data() {
    return {
      images: [
        'jumbo/golden-switch.jpg',
        'it-training.jpg',
        'Microwave.jpg',
        'services.jpg',
        'VoIP.jpg'
      ],
      timer: null,
      currentIndex: 0
    }
  },
  computed: {
    currentImg () {
      return (this.images[Math.abs(this.currentIndex) % this.images.length])
    }
  },
  mounted() {
    let tl = gsap.timeline();

    tl.from('#hero-text', { scale: 0.9, duration: 1, opacity: 0, ease: Expo.EaseOut})
     .to('.text-reveal', { clipPath: 'polygon(0 0, 100% 0, 100% 100%, 0 100%)', y: 0, stagger: .3, duration: 1 }, "-=2.5");
    this.slideStart()
  },
  methods: {
    slideStart () {
      this.timer = setInterval(this.next, 5000)
    },
    next () {
      this.currentIndex += 1
    }
  },
  head () {
    return {
      title: "Services | Trends IT Services",
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: "Trends IT Services is a network services and sustainable energy installation and project service rendering company targeted at training and optimizing work operations in organizations."
        },
        {
          property: 'og:title',
          content: "Home | Trends IT Services"
        },
        {
          property: 'og:description',
          content: "Trends IT Services is a network services and sustainable energy installation and project service rendering company targeted at training and optimizing work operations in organizations."
        },
        {
          property: 'og:url',
          content: 'https://trendsitservices.com'
        },
        {
          property: 'twitter:card',
          content: 'summary_large_image'
        }
      ],
      script: [{
        type: 'application/ld+json',
        json: {
          '@context': 'https://schema.org',
          '@type': 'Organisation',
          name: "Trends IT Services",
          url: 'https://trendsitservices.com',
          legalName: "Trends IT Services",
          email: 'info.trendsit@gmail.com',
          description: '',
          alternateName: [
            "Trends IT Services",
            "Trends IT",
            "Trends IT Corp"
          ],
          address: {
            '@type': 'PostalAddress',
            addressLocality: 'Olusegun Obasanjo Way, Wuye.',
            postalCode: '900288',
            streetAddress: '2F2, Threshold Business Suite, Plot 976,'
          },
          contactPoint: {
            contactType: 'PR',
            email: 'info.trendsit@gmail.com',
            telephone: '+2348037022330',
            hoursAvaliable: [
              'Mo-Fri 08:00-17:00'
            ],
          }
        }
      }]
    }
  },
}
</script>
