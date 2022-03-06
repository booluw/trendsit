<template>
  <div>
    <section class="text-gray-300 relative bg-clip-border bg-center bg-no-repeat bg-cover -z-50 overflow-hidden"
    :style="[{ backgroundImage: 'url(' + require(`~/assets/img/${currentImg}`) + ')'}, {height: '50vh'}]">
      <div class="absolute inset-0 bg-opacity-70 bg-black pt-48 px-5 md:pt-32 md:px-20">
        <div class="text-4xl md:text-8xl uppercase font-bold">
          Internet <br />
          Connectivity
        </div>
      </div>
    </section>
    <div id="internet-and-network"></div>
    <section class="px-5 py-10 md:px-20 md:py-32 md:flex justify-between items-start">
      <div class="md:w-3/5">
        Whether you need a VSAT internet connection, Microwave internet connection or Fibre optic internet connection, our team can help get you connected fast. <b>We have a solution that will work for you.</b>
        <div class="mt-5">
          <h3 class="font-bold text-2xl text-gray-800 mb-2">VSAT Connection</h3>
          VSAT (a very small aperture terminal) is the perfect solution for businesses that need fast, reliable data transmission but don't have the space or budget for a physical network. 
          So if you're looking to make your business more efficient and scalable, VSAT is the answer.Trends I.T ISP specializes in providing internet Service over VSAT solutions through Ku-Band, Ka-Band and C-Band satellite links, so you can stay connected no matter where you are.Trends I.T ISP possesses many years of experience in providing VSAT network design, integration and services to clients in remote locations all over Nigeria.
        </div>
        <div class="mt-5">
          <h3 class="font-bold text-2xl text-gray-800 mb-2">Microwave Connection</h3>
          With a microwave connection, your organisation can be assured of reliable wireless network technology. Trends I.T is here to help you to enjoy a high-speed reliable and fast internet connection.
        </div>
        <div class="mt-5">
          <h3 class="font-bold text-2xl text-gray-800 mb-2">Fibre Optic Connection</h3>
          Do you wish to blaze your way to fast connectivity without breaking the bank!
          Looking for a lightning-fast internet connection? Look no further than Fibre Optic Connection!
          Our speedy service will give you the bandwidth you need to stay connected and productive. Plus, our high-quality optics ensure clear, uninterrupted streaming. So whether you're catching up on work or enjoying some downtime, Fibre Optic Connection has got you covered. Don't wait - call today!
        </div>
      </div>
      <div class="md:2/5">
        <img src="~/assets/img/internet.jpg" class="md:w-3/4 mt-10 md:mt-0 h-auto rounded-2xl shadow-md object-contain block mx-auto" />
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
      title: "Internet Connectivity | Trends IT Services",
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