<template>
  <section class="text-gray-100 bg-[#34cc81]">
    <div
      class="container w-full mx-auto flex px-5 lg:px-20 py-20 md:flex-row flex-col items-center"
    >
      <div
        class="lg:flex-grow md:w-3/5 lg:pr-24 md:pr-16 flex flex-col md:items-start mx-4 mb-16 md:mb-0 items-center text-left"
      >
        <h3 class="tracking-widest mb-8">WIR SIND IHR FULL-SERVICE DIENSTLEISTER</h3>
        <h1 class="title-font sm:text-5xl text-4xl mb-4 font-bold text-gray-100 mr-4">
          SERVER­SEITIGES TRACKING
          <br class="inline-block" />
          <span class="text-slate-700 inline-block my-3">FÜR DIGITALES WACHSTUM</span>
        </h1>
        <p class="mb-8 text-lg font-medium leading-relaxed">
          Web-Analytics und Online-Marketing-Daten sind die Basis für digitales Wachstum. Nur wer
          die Daten analysiert, kann digitales Marketing effektvoll optimieren. In unserer Agentur
          zählen Fakten statt Bauchgefühl!
        </p>
        <div class="self-start">
          <NuxtLink
            to="/contact"
            class="border-[3px] block rounded-full border-white md:text-xl text-sm font-bold tracking-[2px] px-4 py-3 text-gray-100 hover:bg-green-600 hover:border-green-600 transition duration-300"
          >
            KONTAKT AUFNEHMEN
          </NuxtLink>
        </div>
      </div>
      <div class="lg:max-w-lg self-start lg:w-full md:w-2/5 md:block hidden">
        <img
          class="object-cover object-center rounded"
          alt="hero"
          src="~assets/images/google-data-analytics-banner.png"
        />
      </div>
    </div>
  </section>
</template>

<script setup></script>

<style scoped></style>
