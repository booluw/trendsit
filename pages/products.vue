<template>
  <div>
    <section class="text-gray-300 relative bg-clip-border bg-center bg-no-repeat bg-cover -z-50 overflow-hidden"
    :style="[{ backgroundImage: 'url(' + require(`~/assets/img/${currentImg}`) + ')'}, {height: '50vh'}]">
      <div class="absolute inset-0 bg-opacity-70 bg-black pt-48 px-5 md:pt-32 md:px-20">
        <div class="text-4xl md:text-8xl uppercase font-bold">
          Our <br />
          Products
        </div>
      </div>
    </section>
    <div id="internet-and-network"></div>
    <section class="px-5 py-10 md:px-20 md:py-32 md:flex justify-between items-start">
      <div class="md:w-3/5">
        <ul class="list-none text-gray-500 mt-10">
          <li class="pl-5 mt-3 border-l-2 border-gray-500">
            Networking Devices
          </li>
          <li class="pl-5 mt-3 border-l-2 border-gray-500">
            Servers
          </li>
          <li class="pl-5 mt-3 border-l-2 border-gray-500">
            IP/VOIP/telephone accessories
          </li>
          <li class="pl-5 mt-3 border-l-2 border-gray-500">
            Solar Batteries
          </li>
          <li class="pl-5 mt-3 border-l-2 border-gray-500">
            Solar Panels
          </li>
        </ul>
      </div>
      <div class="md:2/5">
        <img src="~/assets/img/products.jpg" class="md:w-3/4 mt-10 md:mt-0 h-auto rounded-2xl shadow-md object-contain block mx-auto" />
      </div>
    </section>
  </div>
</template>

<script>
export default {
  data() {
    return {
      currentImg: 'services.jpg'
    }
  },
  head () {
    return {
      title: "Products | Trends IT Services",
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

<style>

</style>