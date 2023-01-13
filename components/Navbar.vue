<template>
  <header class="text-gray-600 bg-zinc-800 body-font z-10 w-full">
    <div
      class="container mx-auto flex flex-wrap justify-between p-5 items-center"
    >
      <NuxtLink class="flex title-font font-medium items-center text-gray-900">
        <img
          src="./../assets/images/ads-tracking-logo.svg"
          alt="Ads Tracking"
          class="w-48"
        />
      </NuxtLink>
      <!-- Desktop Nav -->
      <div class="lg:flex hidden">
        <nav
          class="md:ml-auto flex flex-wrap items-center text-base justify-center"
        >
          <NuxtLink
            to="/"
            class="mr-5 font-bold text-base text-gray-500 uppercase transition duration-200 hover:text-gray-100"
            >HOME</NuxtLink
          >
          <NuxtLink
            to="/services"
            class="mr-5 font-bold text-base text-gray-500 uppercase transition duration-200 hover:text-gray-100"
          >
            DIENSTLEISTUNGEN</NuxtLink
          >
          <NuxtLink
            to="/about"
            class="mr-5 font-bold text-base text-gray-500 uppercase transition duration-200 hover:text-gray-100"
            >KUNDEN</NuxtLink
          >
          <NuxtLink
            to="/contact"
            class="mr-5 font-bold text-base text-gray-500 uppercase transition duration-200 hover:text-gray-100"
            >ÜBER UNS</NuxtLink
          >
        </nav>
        <button
          class="inline-flex items-center transition duration-200 py-2 px-6 focus:outline-none border text-gray-100 hover:bg-green-500 hover:border-green-500 uppercase font-bold rounded-full text-base mt-4 md:mt-0"
        >
          KONTAKT
        </button>
      </div>
      <button type="button" class="lg:hidden">
        <Bars3Icon class="w-8 h-8 stroke-green-500" />
      </button>
      <!-- Mobile Nav -->
    </div>
  </header>
</template>

<script>
import { Bars3Icon } from "@heroicons/vue/24/outline/index";

export default { components: { Bars3Icon } };
</script>

<style scoped></style>
