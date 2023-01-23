<template>
  <div>
    <AboutHero />
    <section class="text-gray-600 overflow-hidden">
      <div class="container px-5 lg:px-20 py-20 mx-auto">
        <div class="mx-auto flex flex-wrap justify-between">
          <img
            alt="image_2"
            class="lg:w-1/2 w-full h-2/4 self-center object-cover object-center rounded"
            src="~/assets/images/about-img_2.jpg"
          />
          <div class="lg:w-1/2 w-full lg:pl-10 lg:py-6 mt-6 lg:mt-0">
            <div class="flex flex-col w-full mb-10">
              <h1 class="sm:text-4xl text-3xl font-bold title-font text-gray-900">
                Begeisterung macht glücklich
              </h1>
              <span class="inline-block h-1 w-20 mt-4 rounded bg-green-500"></span>
            </div>

            <p class="leading-relaxed text-lg p-4">
              Wir machen Sie glücklich, versprochen: Wir sind
              <span class="text-green-500">Dienstleister aus Leidenschaft</span>
              und lieben, was wir tun. Als Spezialisten sind wir stolz auf unser Know-how und unsere
              langjährige Erfahrung in der äußerst speziellen Materie rund um serverseitiges
              Tracking. Dabei stets im Mittelpunkt: Unsere Kunden. Das garantieren wir Ihnen.
            </p>
            <p class="leading-relaxed text-lg p-4">
              Wir sind <span class="text-green-500">ehrlich:</span> Wir wollen mit Ihnen nicht nur
              „ein Projekt abwickeln“. Sondern wir möchten verstehen, was Sie und Ihr Unternehmen
              tun und dann gemeinsam mit Ihnen das Beste aus Ihrem Marketing herausholen.
              <span class="text-green-500"> Als Partner und dauerhaft.</span>
            </p>
            <p class="leading-relaxed text-lg p-4">
              Viele unserer Kunden arbeiten seit mehreren Jahren mit uns zusammen. Sie sind die
              <NuxtLink to="/customers" class="text-green-500">
                beste Referenz, die wir uns wünschen können</NuxtLink
              >.
            </p>
          </div>
        </div>
      </div>
    </section>
    <AboutTeam />
    <AboutVision />
    <!-- CTA Section -->
    <section class="text-gray-600 bg-[#34cc81dd] body-font">
      <div class="container px-5 py-16 mx-auto">
        <div
          class="lg:w-4/5 flex flex-col gap-8 sm:items-center items-start justify-between mx-auto"
        >
          <h1 class="text-3xl text-center mx-auto font-bold text-gray-100">
            Wir freuen uns, Sie kennenzulernen!
          </h1>
          <NuxtLink
            to="/contact"
            class="border-2 rounded-full mx-auto border-white p-4 text-white hover:bg-green-600 hover:border-green-600 transition duration-300"
          >
            SCHREIBEN SIE UNS
          </NuxtLink>
        </div>
      </div>
    </section>
    <!-- Success Section -->
    <section id="successSection" class="text-gray-600 bg-white body-font overflow-hidden">
      <div class="container px-5 lg:px-20 py-20 lg:py-24 mx-auto">
        <div class="mx-auto flex items-center lg:flex-nowrap flex-wrap gap-12">
          <div class="lg:w-1/2 w-full">
            <img
              alt="image_1"
              class="object-center object-contain rounded"
              src="~/assets/images/about-img_1.jpg"
            />
          </div>
          <div class="lg:w-1/2 w-full lg:pr-10 lg:py-6 lg:mb-0">
            <h2 class="text-md text-green-500 font-bold tracking-widest">UNSERE FÄHIGKEITEN</h2>
            <h1 class="text-gray-900 text-4xl title-font font-bold my-6">
              Erfahrung in allen wichtigen Marketing-Disziplinen
            </h1>

            <div>
              <label for="tagManager">Google Tag Manager</label>
              <div class="relative">
                <span class="inline-block w-full bg-gray-200 py-1 px-2 h-6"></span>
                <span
                  class="inline-block overlay-green w-full py-1 px-2 h-6 bg-[#34cc81] text-end text-sm text-white absolute top-0 left-0 transition-all duration-300"
                >
                  100%
                </span>
              </div>
              <label for="googleAds">Google Ads</label>
              <div class="relative">
                <span class="inline-block w-full bg-gray-200 py-1 px-2 h-6"></span>
                <span
                  class="inline-block overlay-green w-full py-1 px-2 h-6 bg-[#34cc81] text-end text-sm text-white absolute top-0 left-0 transition-all duration-300"
                >
                  100%
                </span>
              </div>
              <label for="Facebook">Facebook</label>
              <div class="relative">
                <span class="inline-block w-full bg-gray-200 py-1 px-2 h-6"></span>
                <span
                  class="inline-block overlay-green w-[95%] py-1 px-2 h-6 bg-[#34cc81] text-end text-sm text-white absolute top-0 left-0 transition-all duration-300"
                >
                  95%
                </span>
              </div>
              <label for="Tracking">Tracking, analysis and controlling</label>
              <div class="relative">
                <span class="inline-block w-full bg-gray-200 py-1 px-2 h-6"></span>
                <span
                  class="inline-block overlay-green w-full py-1 px-2 h-6 bg-[#34cc81] text-end text-sm text-white absolute top-0 left-0 transition-all duration-300"
                >
                  100%
                </span>
              </div>
              <label for="Conversion">Conversion Optimization</label>
              <div class="relative">
                <span class="inline-block w-full bg-gray-200 py-1 px-2 h-6"></span>
                <span
                  class="inline-block overlay-green w-[90%] py-1 px-2 h-6 bg-[#34cc81] text-end text-sm text-white absolute top-0 left-0 transition-all duration-300"
                >
                  90%
                </span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {};
</script>

<style scoped></style>
