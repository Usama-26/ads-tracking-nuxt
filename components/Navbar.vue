<template>
  <header class="text-gray-600 bg-zinc-800 body-font z-10 w-full">
    <div
      class="container mx-auto flex flex-wrap justify-between p-5 items-center"
    >
      <NuxtLink class="flex title-font font-medium items-center text-gray-900">
        <img
          src="~/assets/images/ads-tracking-logo.svg"
          alt="Ads Tracking"
          class="w-48"
        />
      </NuxtLink>
      <!-- Desktop Nav -->
      <div class="lg:flex hidden">
        <nav
          class="md:ml-auto flex flex-wrap items-center text-base justify-center"
        >
          <NuxtLink to="/" class="desktop-link">HOME</NuxtLink>
          <NuxtLink to="/services" class="desktop-link"
            >DIENSTLEISTUNGEN</NuxtLink
          >
          <NuxtLink to="/about" class="desktop-link">KUNDEN</NuxtLink>
          <NuxtLink to="/contact" class="desktop-link">ÜBER UNS</NuxtLink>
        </nav>
        <button
          class="inline-flex items-center transition duration-200 py-2 px-6 focus:outline-none border text-gray-100 hover:bg-green-500 hover:border-green-500 uppercase font-bold rounded-full text-base mt-4 md:mt-0"
        >
          KONTAKT
        </button>
      </div>
      <button
        type="button"
        class="lg:hidden z-10"
        @click="isToggled = !isToggled"
      >
        <XMarkIcon v-if="isToggled" class="w-8 h-8 stroke-white" />
        <Bars3Icon v-else class="w-8 h-8 lg:stroke-green-500 stroke-white" />
      </button>
      <!-- Mobile Nav -->
      <div
        v-if="isToggled"
        class="lg:hidden block absolute h-screen top-0 w-96 right-0 z-5 bg-[#34cc81]"
      >
        <nav
          class="md:ml-auto mt-10 flex flex-wrap gap-8 items-center text-base justify-start"
        >
          <NuxtLink to="/" @click="isToggled = false" class="mobile-link"
            >HOME</NuxtLink
          >
          <NuxtLink
            to="/services"
            @click="isToggled = false"
            class="mobile-link"
          >
            DIENSTLEISTUNGEN</NuxtLink
          >
          <NuxtLink to="/about" @click="isToggled = false" class="mobile-link"
            >KUNDEN</NuxtLink
          >
          <NuxtLink to="/contact" @click="isToggled = false" class="mobile-link"
            >ÜBER UNS</NuxtLink
          >
          <NuxtLink
            class="text-center transition duration-200 py-2 ml-10 focus:outline-none border text-gray-100 hover:bg-green-500 hover:border-green-500 uppercase font-bold w-4/5"
          >
            KONTAKT
          </NuxtLink>
        </nav>
      </div>
    </div>
  </header>
</template>

<script>
import { Bars3Icon } from "@heroicons/vue/24/outline/index.js";
import { XMarkIcon } from "@heroicons/vue/24/outline/index.js";

export default {
  components: { Bars3Icon, XMarkIcon },
  data() {
    return {
      isToggled: false,
    };
  },
};
</script>

<style scoped></style>
