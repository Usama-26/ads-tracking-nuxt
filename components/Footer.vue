<template>
  <footer class="text-gray-600 body-font footer-background">
    <div class="container py-16 lg:px-20 px-10 mx-auto">
      <div class="flex gap-8 md:flex-nowrap flex-wrap">
        <div class="flex md:flex-nowrap flex-wrap w-full gap-16">
          <div class="md:w-1/2 w-full">
            <NuxtLink to="/" class="inline-block mb-8">
              <img
                src="~/assets/images/ads-tracking-logo-white.svg"
                alt="Ads Tracking Logo"
                class="md:w-60 w-96"
              />
            </NuxtLink>
            <h3 class="font-bold text-sm leading-loose pb-4 lg:w-4/5">
              Mehr Umsatz & bessere Daten – Ihr Vorsprung mit serverseitigem Tracking
            </h3>
            <NuxtLink
              to="contact"
              class="py-2 px-4 inline-block my-2 font-bold text-white rounded-full bg-[#34cc81]"
              >KONTAKT AUFNEHMEN</NuxtLink
            >
          </div>
          <div class="md:w-1/2 w-full">
            <h4 class="text-[#34cc81] tracking-widest">NAVIGATOR</h4>
            <ul class="text-sm">
              <li class="my-3">
                <NuxtLink
                  class="inline-block hover:text-gray-900 hover:translate-x-1 transition duration-300"
                  to="home"
                  >Home</NuxtLink
                >
              </li>
              <li class="my-3">
                <NuxtLink
                  class="inline-block hover:text-gray-900 hover:translate-x-1 transition duration-300"
                  to="services"
                  >Dienstleistungen</NuxtLink
                >
              </li>
              <li class="my-3">
                <NuxtLink
                  class="inline-block hover:text-gray-900 hover:translate-x-1 transition duration-300"
                  to="customers"
                  >Kunden</NuxtLink
                >
              </li>
              <li class="my-3">
                <NuxtLink
                  class="inline-block hover:text-gray-900 hover:translate-x-1 transition duration-300"
                  to="about"
                  >Über Uns</NuxtLink
                >
              </li>
              <li class="my-3">
                <NuxtLink
                  class="inline-block hover:text-gray-900 hover:translate-x-1 transition duration-300"
                  to="contact"
                  >Kontakt</NuxtLink
                >
              </li>
            </ul>
          </div>
        </div>
        <div class="flex md:flex-nowrap flex-wrap w-full gap-16">
          <div class="md:w-1/2 w-full">
            <h4 class="text-[#34cc81] tracking-widest">KONTAKT</h4>
            <ul class="text-sm">
              <li class="my-3 hover:text-gray-900 hover:underline">
                <a href="mailto:anfrage@ads-tracking.de" class="inline-flex gap-1"
                  ><EnvelopeIcon class="w-4 h-4" />anfrage@ads-tracking.de</a
                >
              </li>
              <li class="my-3 hover:text-gray-900 hover:underline">
                <a href="tel:+4970669290181" class="inline-flex gap-1"
                  ><PhoneIcon class="w-4 h-4" /> +49 7066 9290181
                </a>
              </li>
              <li class="my-3">
                <span class="inline-flex gap-1"
                  ><ClockIcon class="w-4 h-4" /> Mo-Fr | 9:00 -17:00 Uhr</span
                >
              </li>
            </ul>
          </div>
          <div class="md:w-1/2 w-full">
            <h4 class="text-[#34cc81] tracking-widest">UNTERNEHMEN</h4>
            <ul class="text-sm">
              <li class="my-3">
                <NuxtLink
                  class="inline-block hover:text-gray-900 hover:translate-x-1 transition duration-300"
                  to="/imprint"
                  >Impressum</NuxtLink
                >
              </li>
              <li class="my-3">
                <NuxtLink
                  class="inline-block hover:text-gray-900 hover:translate-x-1 transition duration-300"
                  to="/terms"
                  >Allgemeine Geschäftsbedingungen</NuxtLink
                >
              </li>
              <li class="my-3">
                <NuxtLink
                  class="inline-block hover:text-gray-900 hover:translate-x-1 transition duration-300"
                  to="/dataprotection"
                  >Datenschutzerklärung</NuxtLink
                >
              </li>
            </ul>
          </div>
        </div>
      </div>
      <div class="flex gap-8">
        <div class="w-1/2 border-t border-black mt-10"></div>
        <div class="w-1/2 border-t border-black mt-10"></div>
      </div>
      <div class="w-full flex flex-wrap text-center text-gray-600 mt-4">
        <div class="md:w-1/3 w-full"></div>
        <div class="md:w-1/3 w-full mb-8">
          <span class="font-bold">Copyright © 2023 ADS Tracking</span>
        </div>
        <div class="md:w-1/3 w-full">
          <div class="flex justify-end gap-4">
            <a href="https://www.facebook.com/AdsTracking">
              <svg
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                class="w-5 h-5 fill-[#34cc81]"
                viewBox="0 0 24 24 "
              >
                <path d="M18 2h-3a5 5 0 00-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 011-1h3z"></path>
              </svg>
            </a>
            <a href="https://www.instagram.com/adstracking">
              <svg
                fill="none"
                stroke="currentColor"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                class="w-5 h-5 stroke-[#34cc81]"
                viewBox="0 0 24 24"
              >
                <rect width="20" height="20" x="2" y="2" rx="5" ry="5"></rect>
                <path d="M16 11.37A4 4 0 1112.63 8 4 4 0 0116 11.37zm1.5-4.87h.01"></path>
              </svg>
            </a>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
import { PhoneIcon, EnvelopeIcon, ClockIcon } from "@heroicons/vue/24/solid/index.js";
export default {
  components: {
    PhoneIcon,
    EnvelopeIcon,
    ClockIcon,
  },
};
</script>

<style scoped>
.footer-background {
  background: url("~/assets/images/footer-bg.webp");
}
</style>
