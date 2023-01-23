<template>
  <section class="text-gray-600 testimonials_bg">
    <div class="container px-8 lg:px-20 py-24 mx-auto">
      <h1 class="text-3xl font-medium title-font text-gray-900 mb-8 text-center">
        So denken unsere Kunden über uns
      </h1>
      <div class="mx-auto">
        <span class="block h-1 w-20 mx-auto mt-4 rounded bg-[#34cc81]"></span>
      </div>
      <p class="lg:w-4/5 w-full mx-auto font-bold mt-4 mb-8 text-center">
        So denken unsere Kunden über uns Wie zufrieden unsere Kunden mit unseren Tracking und
        Services sind, zeigen uns die vielen positiven Bewertungen, die uns regelmäßig erreichen.
        Das sind nur drei von mehr als 100 Unternehmen, mit denen wir seit 2017 erfolgreich
        zusammengearbeitet haben.
      </p>
      <div class="flex lg:flex-nowrap py-20 flex-wrap gap-8 justify-around">
        <div class="lg:w-1/3 lg:mb-0 mb-6 p-4 rounded-lg bg-white shadow-md">
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
        <div class="lg:w-1/3 lg:mb-0 mb-6 p-4 rounded-lg bg-white shadow-md">
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
        <div class="lg:w-1/3 lg:mb-0 p-4 rounded-lg bg-white shadow-md">
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
.testimonials_bg {
  background: url("~/assets/images/testimonials_bg.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
}
</style>
