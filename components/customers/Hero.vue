<template>
  <section class="text-gray-600 body-font hero__background">
    <div class="container mx-auto flex px-5 py-28 items-center justify-center flex-col">
      <div class="text-left w-4/5">
        <h1 class="title-font sm:text-4xl text-3xl font-bold text-gray-100">Referenzen</h1>
        <div class="border-b-4 w-24 border-green-500 inline-block"></div>
        <p class="my-12 leading-relaxed text-lg font-medium text-gray-100">
          Wie zufrieden unsere Kunden mit unseren Tracking und Services sind, zeigen uns die vielen
          positiven Bewertungen, die uns regelmäßig erreichen. Auf dieser Seite stellen wir Ihnen
          einige der mehr als 100 Unternehmen vor, mit denen wir seit 2017 erfolgreich
          zusammengearbeitet haben.
        </p>
      </div>
      <div class="flex flex-wrap justify-around">
        <div
          class="lg:w-1/4 lg:mb-0 mb-6 p-4 rounded-lg bg-white shadow-[10px_10px_0px_rgba(255,255,255)] shadow-gray-400"
        >
          <div class="h-full text-center">
            <img
              alt="testimonial_1"
              class="w-40 h-20 mb-8 object-cover object-center rounded-full inline-block border-2 border-gray-200 bg-gray-100"
              src="~/assets/images/testimonial-1.png"
            />
            <p class="leading-relaxed">
              Dies ist ein Analyse-Kraftpaket eines Dienstes. Erstaunliche Menschen, die alles
              überliefern. Die beste Investition, die wir in das Verständnis der Leistung unserer
              Geschäfte getätigt haben.
            </p>
            <span class="inline-block h-1 w-10 rounded bg-green-500 mt-6 mb-4"></span>
            <h2 class="text-gray-900 font-medium capitalize tracking-wider text-sm">jessica doe</h2>
            <p class="text-gray-500">
              IT Department,
              <span class="text-green-500">Airport Zurich AG</span>
            </p>
          </div>
        </div>
        <div
          class="lg:w-1/4 lg:mb-0 mb-6 p-4 rounded-lg bg-white shadow-[10px_10px_0px_rgba(255,255,255)] shadow-gray-400"
        >
          <div class="h-full text-center">
            <img
              alt="testimonial_2"
              class="w-40 h-20 mb-8 object-cover object-center rounded-full inline-block border-2 border-gray-200 bg-gray-100"
              src="~/assets/images/testimonial-2.jpg"
            />
            <p class="leading-relaxed">
              Unser Shop hat ein komplexes Setup mit einigen externen Domains. Das Ads-Tracking hat
              mit Google Tag Manager und Analytics 4 super funktioniert. Auch beim
              Cross-Domain-Tracking hat uns der Support sehr geholfen.
            </p>
            <span class="inline-block h-1 w-10 rounded bg-green-500 mt-6 mb-4"></span>
            <h2 class="text-gray-900 font-medium capitalize tracking-wider text-sm">Anne Spies</h2>
            <p class="text-gray-500">
              Investor Relations Manager
              <span class="text-green-500">Hornbach</span>
            </p>
          </div>
        </div>
        <div
          class="lg:w-1/4 lg:mb-0 p-4 rounded-lg bg-white shadow-[10px_10px_0px_rgba(255,255,255)] shadow-gray-400"
        >
          <div class="h-full text-center">
            <img
              alt="testimonial_3"
              class="w-40 h-20 mb-8 object-cover object-center rounded-full inline-block border-2 border-gray-200 bg-gray-100"
              src="~/assets/images/testimonial-3.png"
            />
            <p class="leading-relaxed">
              Diese Jungs sind das einzig Wahre; Wir hatten alles zur Verfügung gestellt, um unsere
              Google Analytics-Tracking-Probleme mit unserem Shopify-Shop zu beheben, aber nichts
              funktionierte. Sie haben nicht nur das GA-Tracking behoben, sondern auch GA4
              eingerichtet. Einfach unglaublich.
            </p>
            <span class="inline-block h-1 w-10 rounded bg-green-500 mt-6 mb-4"></span>
            <h2 class="text-gray-900 font-medium capitalize tracking-wider text-sm">
              Mathias Tier
            </h2>
            <p class="text-gray-500">
              Marketing,
              <span class="text-green-500">Starbucks</span>
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup></script>

<style scoped>
.hero__background {
  background: url("assets/images/bg-hero.webp");
  background-size: cover;
}
</style>
