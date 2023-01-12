<template>
  <header class="text-gray-600 bg-zinc-800 body-font z-10 fixed top-0 w-full">
    <div
      class="container mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center"
    >
      <NuxtLink
        class="flex title-font font-medium items-center text-gray-900 mb-4 md:mb-0"
      >
        <img
          src="./../assets/images/ads-tracking-logo.svg"
          alt="Ads Tracking"
        />
      </NuxtLink>
      <nav
        class="md:ml-auto flex flex-wrap items-center text-base justify-center"
      >
        <NuxtLink
          class="mr-5 font-bold text-base text-gray-500 uppercase transition duration-200 hover:text-gray-100"
          >Home</NuxtLink
        >
        <NuxtLink
          class="mr-5 font-bold text-base text-gray-500 uppercase transition duration-200 hover:text-gray-100"
          >Services</NuxtLink
        >
        <NuxtLink
          class="mr-5 font-bold text-base text-gray-500 uppercase transition duration-200 hover:text-gray-100"
          >Customers</NuxtLink
        >
        <NuxtLink
          class="mr-5 font-bold text-base text-gray-500 uppercase transition duration-200 hover:text-gray-100"
          >About us</NuxtLink
        >
      </nav>
      <button
        class="inline-flex items-center transition duration-200 py-2 px-6 focus:outline-none border text-gray-100 hover:bg-green-500 hover:border-green-500 uppercase font-bold rounded-full text-base mt-4 md:mt-0"
      >
        Button
      </button>
    </div>
  </header>
</template>

<script></script>

<style scoped></style>
