<template>
  <header
    class="text-gray-600 z-10 w-full"
    :class="
      isScrolled
        ? 'bg-white fixed top-0 p-3 shadow-md'
        : 'bg-zinc-800 border-y border-gray-300 p-5'
    "
  >
    <div class="mx-auto flex flex-wrap justify-between items-center">
      <NuxtLink to="/">
        <img
          v-if="!isScrolled"
          src="~/assets/images/ads-tracking-logo.svg"
          alt="Ads Tracking"
          class="w-48"
          :src="{ '~/assets/images/ads-tracking-logo-white.svg': isScrolled }"
        />
        <img
          v-else
          src="~/assets/images/ads-tracking-logo-white.svg"
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
            class="desktop-link"
            :class="isScrolled ? 'hover:text-gray-900' : 'hover:text-gray-100'"
            >HOME</NuxtLink
          >
          <NuxtLink
            to="/services"
            class="desktop-link"
            :class="isScrolled ? 'hover:text-gray-900' : 'hover:text-gray-100'"
            >DIENSTLEISTUNGEN</NuxtLink
          >
          <NuxtLink
            to="/customers"
            class="desktop-link"
            :class="isScrolled ? 'hover:text-gray-900' : 'hover:text-gray-100'"
            >KUNDEN</NuxtLink
          >
          <NuxtLink
            to="/about"
            class="desktop-link"
            :class="isScrolled ? 'hover:text-gray-900' : 'hover:text-gray-100'"
            >ÜBER UNS</NuxtLink
          >
        </nav>
        <NuxtLink
          to="/contact"
          class="inline-flex items-center transition duration-200 py-2 px-6 focus:outline-none border hover:bg-green-600 hover:border-green-500 uppercase font-bold rounded-full text-base mt-4 md:mt-0"
          :class="isScrolled ? 'text-gray-100 bg-green-500 ' : 'text-gray-100'"
        >
          KONTAKT
        </NuxtLink>
      </div>
      <button
        type="button"
        class="lg:hidden z-10"
        @click="isToggled = !isToggled"
      >
        <XMarkIcon v-if="isToggled" class="w-8 h-8 stroke-white" />
        <Bars3Icon
          v-else
          class="w-8 h-8 lg:stroke-green-500 stroke-white"
          :class="isScrolled ? 'stroke-gray-900' : 'stroke-green-600'"
        />
      </button>
      <!-- Mobile Nav -->
      <div
        v-if="isToggled"
        class="lg:hidden block fixed h-screen top-0 w-96 right-0 z-5 bg-[#34cc81]"
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
          <NuxtLink
            to="/customers"
            @click="isToggled = false"
            class="mobile-link"
            >KUNDEN</NuxtLink
          >
          <NuxtLink to="/about" @click="isToggled = false" class="mobile-link"
            >ÜBER UNS</NuxtLink
          >
          <NuxtLink
            to="/contact"
            @click="isToggled = false"
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

<style scoped></style>
