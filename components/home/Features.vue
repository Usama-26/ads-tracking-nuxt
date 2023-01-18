<template>
  <section class="text-gray-600 body-font bg-gray-200">
    <div class="container px-5 py-24 mx-auto">
      <div class="flex flex-col lg:mx-20 mx-5 mb-10">
        <h1 class="text-4xl font-bold title-font text-gray-900">
          Bringen Sie Ihr Business mit Ads-Tracking auf das nächste Level
        </h1>
        <span class="inline-block h-1 w-20 mt-4 rounded bg-[#34cc81]"></span>
      </div>
      <div class="flex lg:flex-nowrap flex-wrap gap-8 lg:mx-20 mx-5">
        <div class="lg:w-1/3 w-full">
          <div class="flex rounded-xl h-full shadow-lg text-center bg-white p-8 flex-col">
            <CheckCircleIcon class="fill-[#34cc81] w-16 h-16 mx-auto" />

            <h2 class="font-bold text-xl my-4 text-gray-900">
              Messbar mehr Erfolg für Ihre Kunden
            </h2>

            <div class="flex-grow">
              <p class="leading-relaxed lg:w-4/5 sm:w-3/5 w-full mx-auto">
                Mit Serverside-Tracking sehen Sie auf einmal wieder 99% der Daten. KPIs können
                wieder korrekt getrackt und Potenziale zur Verbesserung voll ausgeschöpft werden.
              </p>
            </div>
          </div>
        </div>
        <div class="lg:w-1/3 w-full">
          <div class="flex rounded-xl h-full shadow-lg text-center bg-white p-8 flex-col">
            <CheckCircleIcon class="fill-[#34cc81] w-16 h-16 mx-auto" />

            <h2 class="font-bold text-xl my-4 text-gray-900">
              Deutlich mehr Umsatz für das gleiche Budget
            </h2>

            <div class="flex-grow">
              <p class="leading-relaxed lg:w-4/5 sm:w-3/5 w-full mx-auto">
                Durch eine vollständige Erfassung der Conversions kann der Algorithmus besser lernen
                und optimieren. Im Ergebnis erzielen Sie bessere Umsätze bei gleichem Budget.
              </p>
            </div>
          </div>
        </div>
        <div class="lg:w-1/3 w-full">
          <div class="flex rounded-xl h-full shadow-lg text-center bg-white p-8 flex-col">
            <CheckCircleIcon class="fill-[#34cc81] w-16 h-16 mx-auto" />

            <h2 class="font-bold text-xl my-4 text-gray-900">
              Der Konkurrenz mehr als eine Nasenlänge voraus
            </h2>

            <div class="flex-grow">
              <p class="leading-relaxed lg:w-4/5 sm:w-3/5 w-full mx-auto">
                Serverseitiges Tracking ist noch nicht besonders verbreitet. Wenn Sie jetzt darauf
                setzen, können Sie sich wohlmöglich einen wichtigen Wettbewerbsvorteil erarbeiten.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import { CheckCircleIcon } from "@heroicons/vue/24/solid/index.js";
export default { components: { CheckCircleIcon } };
</script>

<style scoped></style>
