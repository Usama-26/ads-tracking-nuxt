<template>
  <header
    class="text-gray-600 z-10 w-full border-b"
    :class="
      isScrolled
        ? 'bg-white fixed top-0 p-3 shadow-md border-none'
        : 'bg-zinc-700 p-5 border-zinc-500'
    "
  >
    <div class="mx-auto flex flex-wrap justify-between items-center h-10">
      <NuxtLink to="/">
        <img
          v-if="!isScrolled"
          src="~/assets/images/ads-tracking-logo.svg"
          alt="Ads Tracking"
          class="lg:w-96 sm:w-72 w-56"
          :src="{ '~/assets/images/ads-tracking-logo-white.svg': isScrolled }"
        />
        <img
          v-else
          src="~/assets/images/ads-tracking-logo-white.svg"
          alt="Ads Tracking"
          class="lg:w-96 sm:w-72 w-56"
        />
      </NuxtLink>
      <!-- Desktop Nav -->
      <div class="lg:flex hidden">
        <nav class="md:ml-auto flex flex-wrap items-center text-base justify-center">
          <NuxtLink
            to="/"
            class="desktop-link text-gray-500"
            @click="handleActiveLink"
            :class="isScrolled ? 'hover:text-gray-900' : 'hover:text-gray-100'"
            >HOME</NuxtLink
          >
          <NuxtLink
            to="/services"
            class="desktop-link text-gray-500"
            @click="handleActiveLink"
            :class="isScrolled ? 'hover:text-gray-900' : 'hover:text-gray-100'"
            >DIENSTLEISTUNGEN</NuxtLink
          >
          <NuxtLink
            to="/customers"
            class="desktop-link text-gray-500"
            @click="handleActiveLink"
            :class="isScrolled ? 'hover:text-gray-900' : 'hover:text-gray-100'"
            >KUNDEN</NuxtLink
          >
          <NuxtLink
            to="/about"
            class="desktop-link text-gray-500"
            @click="handleActiveLink"
            :class="isScrolled ? 'hover:text-gray-900' : 'hover:text-gray-100'"
            >ÜBER UNS
          </NuxtLink>
        </nav>
        <NuxtLink
          to="/contact"
          class="inline-flex items-center transition duration-200 py-2 px-6 focus:outline-none border hover:bg-green-600 hover:border-[#34cc81] uppercase font-bold rounded-full text-base mt-4 md:mt-0"
          :class="isScrolled ? 'text-gray-100 bg-[#34cc81] ' : 'text-gray-100'"
        >
          KONTAKT
        </NuxtLink>
      </div>
      <button type="button" class="lg:hidden z-10" @click="isToggled = !isToggled">
        <XMarkIcon v-if="isToggled" class="w-6 h-6 stroke-2 stroke-white" />
        <Bars3Icon
          v-else
          class="w-8 h-8 lg:stroke-[#34cc81] stroke-white"
          :class="isScrolled ? 'stroke-gray-900' : 'stroke-green-600'"
        />
      </button>
      <!-- Mobile Nav -->
      <div
        v-if="isToggled"
        class="lg:hidden block fixed h-screen md:w-72 w-[90%] transition-all ease-linear shadow top-0 right-0 z-5 bg-[#34cc81]"
      >
        <nav class="mobile-nav mx-5 mt-24 flex flex-wrap items-center text-base justify-start">
          <NuxtLink to="/" @click="isToggled = false" class="mobile-link">Home</NuxtLink>
          <NuxtLink to="/services" @click="isToggled = false" class="mobile-link">
            Dienstleistungen
          </NuxtLink>
          <NuxtLink to="/customers" @click="isToggled = false" class="mobile-link">Kunden</NuxtLink>
          <NuxtLink to="/about" @click="isToggled = false" class="mobile-link">Über Uns</NuxtLink>
          <NuxtLink
            to="/contact"
            @click="isToggled = false"
            class="text-center bg-white rounded-sm transition duration-200 mt-3 py-2 focus:outline-none border text-black font-bold w-full"
          >
            Kontakt
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
      isScrolled: false,
      isToggled: false,
    };
  },
  mounted() {
    window.addEventListener("scroll", this.handleScroll);
  },
  methods: {
    handleScroll() {
      if (window.scrollY > 50) {
        this.isScrolled = true;
      } else {
        this.isScrolled = false;
      }
    },
  },
};
</script>

<style scoped>
a.router-link-active {
  @apply text-green-600;
}

.mobile-nav > a.router-link-active {
  @apply !text-white bg-[rgba(0,0,0,0.03)];
}
</style>
