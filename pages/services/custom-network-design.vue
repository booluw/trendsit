<template>
  <div>
    <section class="text-gray-300 relative bg-clip-border bg-center bg-no-repeat bg-cover -z-50 overflow-hidden"
    :style="[{ backgroundImage: 'url(' + require(`~/assets/img/${currentImg}`) + ')'}, {height: '50vh'}]">
      <div class="absolute inset-0 bg-opacity-70 bg-black pt-44 px-5 md:pt-32 md:px-20">
        <div class="text-3xl md:text-5xl md:w-1/3 uppercase font-bold">
          Custom Network Design and Integration
        </div>
      </div>
    </section>
    <section class="px-5 py-5 md:px-20 md:py-32 md:flex justify-between items-center">
      <div class="md:w-3/5">
        <h1 class="text-gray-500 text-2xl md:text-4xl font-bold mb-5">
          Local Area Network (LAN)
        </h1>
        <p>
          Your business success depends on the performance of your Local Area Network. This is why we offer both wired and wireless options to deploy Local Area Networks services for you.
          From network planning & design to implementation or maintenance - our team makes sure that LAN works seamlessly with all aspects in order to get maximum productivity from them at their very beginning so they can last throughout time!
          <br />
          <b>Key Benefits & Features:</b>
          <ul class="list-none text-gray-500">
            <li class="pl-5 mt-3 border-l-2 border-gray-500">
              24/7 service support
            </li>
            <li class="pl-5 mt-3 border-l-2 border-gray-500">
              High speed of delivery
            </li>
            <li class="pl-5 mt-3 border-l-2 border-gray-500">
              Procurement, installation, management and maintenance of LAN equipment.
            </li>
          </ul>
        </p>
      </div>
      <div class="md:2/5">
        <img src="~/assets/img/LAN.jpg" class="md:w-3/4 mt-10 md:mt-0 h-auto rounded-2xl shadow-md object-contain block mx-auto" />
      </div>
    </section>
    <section class="px-5 py-5 md:px-20 md:py-32 md:flex justify-between items-center">
      <div class="md:2/5">
        <img src="~/assets/img/SOHO.jpg" class="md:w-3/4 mt-10 md:mt-0 h-auto rounded-2xl shadow-md object-contain block mx-auto" />
      </div>
      <div class="md:w-3/5">
        <h1 class="text-gray-500 text-2xl md:text-4xl font-bold mb-5">
          SOHO and SMB Wireless Networking Solutions
        </h1>
        <p>
          SOHO (Small Office and Home Office) and SMB (Small and Medium Business) wireless network is the perfect solution for small businesses like yours who want to give their employees more freedom, while still maintaining a single Internet connection. 
          <br/>
          With Wi-Fi networks, you can improve workflow and be mobile with all of your network devices connected seamlessly!
        </p>
      </div>
    </section>
    <section class="px-5 py-5 md:px-20 md:py-32 md:flex justify-between items-center">
      <div class="md:w-3/5">
        <h1 class="text-gray-500 text-2xl md:text-4xl font-bold mb-5">
          Campus Network
        </h1>
        <p>
          We offer this service to schools who want to seamlessly interconnect their network for easy sharing of files and resources around the campus.
          <br />
          <b>Our Campus Network solution offers:</b>
          <ul class="list-none text-gray-500">
            <li class="pl-5 mt-3 border-l-2 border-gray-500">
              Reliability
            </li>
            <li class="pl-5 mt-3 border-l-2 border-gray-500">
              Redundancy and backup/restore technology
            </li>
            <li class="pl-5 mt-3 border-l-2 border-gray-500">
              Simplify management
            </li>
            <li class="pl-5 mt-3 border-l-2 border-gray-500">
              Cost-effective, dual-site platforms
            </li>
            <li class="pl-5 mt-3 border-l-2 border-gray-500">
              24/7 service support
            </li>
          </ul>
        </p>
      </div>
      <div class="md:2/5">
        <img src="~/assets/img/wireless-network.jpg" class="md:w-3/4 mt-10 md:mt-0 h-auto rounded-2xl shadow-md object-contain block mx-auto" />
      </div>
    </section>
    <section class="px-5 py-5 md:px-20 md:py-32 md:flex justify-between items-center">
      <div class="md:2/5">
        <img src="~/assets/img/VoIP.jpg" class="md:w-3/4 mt-10 md:mt-0 h-auto rounded-2xl shadow-md object-contain block mx-auto" />
      </div>
      <div class="md:w-3/5">
        <h1 class="text-gray-500 text-2xl md:text-4xl font-bold mb-5">
          VoIP
        </h1>
        <p>
          Looking for a VoIP solution that is both private and reliable? Look no further than Trends IT Services. Our VoIP solutions are perfect for businesses that need to communicate with clients and customers without sacrificing privacy or reliability.
          
          <ul class="text-gray-500">
            <li class="pl-5 mt-3 border-l-2 border-gray-500">
              Cloud-based VoIP
            </li>
            <li class="pl-5 mt-3 border-l-2 border-gray-500">
              Easy Mobility
            </li>
            <li class="pl-5 mt-3 border-l-2 border-gray-500">
              HD Audio Calling
            </li>
            <li class="pl-5 mt-3 border-l-2 border-gray-500">
              Remote Management
            </li>
            <li class="pl-5 mt-3 border-l-2 border-gray-500">
              Extended IP PBX
            </li>
            <li class="pl-5 mt-3 border-l-2 border-gray-500">
              Latest IP Devices
            </li>
          </ul>
        </p>
      </div>
    </section>
    <section class="px-5 py-5 md:px-20 md:py-32 md:flex justify-between items-center">
      <div class="md:w-3/5">
        <h1 class="text-gray-500 text-2xl md:text-4xl font-bold mb-5">
          Teleconference
        </h1>
        <p>
          Whether you need to set up an audio conference or video conference, Trends IT is your reliable and cost-effective teleconference service provider with a variety of service delivery compatible with your business or/and organisational needs.
          <br /><br />
          Trends IT can provide you with telepresence systems, video phones, and mobile applications for video communication. All the abovementioned allows you to organize high-quality teleconferences at any time and from anywhere.
          <br /><br />
          Trends IT teleconferencing service will be the most reliable of your business partners. Our technical team will provide the service support that will satisfy even the most demanding customers.
        </p>
      </div>
      <div class="md:2/5">
        <img src="~/assets/img/Teleconference1.jpg" class="md:w-3/4 mt-10 md:mt-0 h-auto rounded-2xl shadow-md object-contain block mx-auto" />
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
      title: "Custom Network and Designs | Trends IT Services",
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