<template>
  <div>
    <section class="text-gray-300 relative bg-clip-border bg-center bg-no-repeat bg-cover -z-50 overflow-hidden"
    :style="[{ backgroundImage: 'url(' + require(`~/assets/img/${currentImg}`) + ')'}, {height: '50vh'}]">
      <div class="absolute inset-0 bg-opacity-70 bg-black pt-44 px-5 md:pt-32 md:px-20">
        <div class="text-4xl md:text-7xl md:w-1/3 uppercase font-bold">
          IT Security
        </div>
      </div>
    </section>
    <section class="px-5 py-5 md:px-20 md:py-32 md:flex justify-between items-center">
      <div class="md:w-3/5">
        <h1 class="text-gray-500 text-2xl md:text-4xl font-bold mb-5">
          CCTV Installation
        </h1>
        <p>
          For your surveillance and other security needs.
          CCTV installation is a must-have security measure for any business or home. Trends IT Services offers professional CCTV installation services that will have your property protected in no time. Our experienced technicians will work with you to determine the best system for your needs and set it up quickly and efficiently so you can rest easy knowing your property is safe.
        </p>
      </div>
      <div class="md:2/5">
        <img src="~/assets/img/cctv.jpg" class="md:w-3/4 mt-10 md:mt-0 h-auto rounded-2xl shadow-md object-contain block mx-auto" />
      </div>
    </section>
    <section class="px-5 py-5 md:px-20 md:py-32 md:flex justify-between items-center">
      <div class="md:1/8">
        <img src="~/assets/img/home-security.jpg" class="md:w-3/4 mt-10 md:mt-0 h-auto rounded-2xl shadow-md object-contain block mx-auto" />
      </div>
      <div class="md:w-7/8">
        <h1 class="text-gray-500 text-2xl md:text-4xl font-bold mb-5">
          Home Security
        </h1>
        <p>
          If you're looking for a reliable and affordable home security solution, Trends IT Services is a perfect choice. We offer a wide range of products and services that will keep your home safe and secure, including access point services, smart locks, and more.
          <br /><br />
          We're committed to providing the best possible service to our customers, and our team of experts are always on hand to provide advice and support. Contact us today to find out more about our home security solutions.
        </p>
      </div>
    </section>
    <section class="px-5 py-5 md:px-20 md:py-32 md:flex justify-between items-center">
      <div class="md:w-3/5">
        <h1 class="text-gray-500 text-2xl md:text-4xl font-bold mb-5">
          Data Protection, Forensics and Backup Solutions.
        </h1>
        <p>
          Did you know that over 2.5 quintillion bytes of data are created every day? That's a lot of data! And it's only going to continue to grow. With all of this data being created, it's more important than ever to have a reliable data protection solution in place.
          <br /><br />
          That's where we come in. At Trends IT Services, we offer Data Protection, Forensics and Backup Solutions that are second to none. We understand the importance of your data and we work hard to keep it safe and secure.
          <br /><br />
          With our Data Protection solutions, you can rest assured that your data is safe from damage or loss. We use the latest cutting-edge technologies to protect your data and with Trend IT Services, you can be sure that your business is always protected.
        </p>
      </div>
      <div class="md:2/5">
        <img src="~/assets/img/Data Protection, forensics,.jpg" class="md:w-3/4 mt-10 md:mt-0 h-auto rounded-2xl shadow-md object-contain block mx-auto" />
      </div>
    </section>
    <section class="px-5 py-5 md:px-20 md:py-32 md:flex justify-between items-center">
      <div class="md:2/5">
        <img src="~/assets/img/Vehicle Tracking.jpg" class="md:w-3/4 mt-10 md:mt-0 h-auto rounded-2xl shadow-md object-contain block mx-auto" />
      </div>
      <div class="md:w-3/5">
        <h1 class="text-gray-500 text-2xl md:text-4xl font-bold mb-5">
          Car Tracking and Fleet Management
        </h1>
        <p>
          Looking for a way to keep your car safe and fleet organized? Trends IT Services has the perfect solution:
          <br /><br />
          With our car tracking and fleet management system, you can keep an eye on your car anyhere it is 24/7. Plus, our system makes managing a fleet of vehicles easy and efficient. So whether you're a business owner with a large fleet or just want to keep tabs on your precious car or cargo, Trends IT Services have you covered.
        </p>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  data() {
    return {
      currentImg: 'cctv.jpg'
    }
  },
  head () {
    return {
      title: "IT Security | Trends IT Services",
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