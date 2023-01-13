<template>
  <div class="bg-gray-100">
    <HomeHero />
    <HomeClients />
    <HomeFeatures />
    <!-- Checklist Section --iOS 14 Stuff -->
    <section class="text-gray-600">
      <div class="container py-24 mx-auto">
        <div class="flex flex-col w-full lg:mb-20 mb-10">
          <h1
            class="sm:text-4xl text-3xl lg:mx-20 font-bold title-font text-gray-900"
          >
            Wenn Ihnen das bekannt vorkommt, brauchen Sie Ads-Tracking
          </h1>
          <span
            class="inline-block h-1 w-20 lg:mx-20 mt-4 rounded bg-green-500"
          ></span>
          <div class="flex mx-20 gap-24 mt-20">
            <div class="bg-gray-200 rounded-md p-8 basis-72 -rotate-6">
              <ul class="list-disc font-medium">
                <li class="my-2">
                  Ich muss die Tracking-Qualität aufgrund von iOS 14 und 15
                  verbessern
                </li>
                <li class="my-2">
                  Ich möchte die Conversion-Genauigkeit maximieren
                </li>
                <li class="my-2">
                  Meine Agentur braucht mich, um mein Tracking für Google Ads,
                  Facebook, GA zu korrigieren
                </li>
                <li class="my-2">
                  Meine Datenschicht für den Google Tag Manager ist ein
                  Durcheinander
                </li>
                <li class="my-2">
                  Ich benötige Tracking, das DSGVO-konform ist
                </li>
                <li class="my-2">
                  Ich vertraue meinen Google Analytics-Daten nicht
                </li>
              </ul>
            </div>
            <div class="max-w-2xl flex flex-col gap-4 text-xl">
              <p>
                Exakte Daten aus der Ad-Performance sind seit IOS 14 und durch
                das zunehmende, teils sogar standardmäßig voreingestellte
                Trackingverbot auf den Endgeräten der User kaum noch zu
                bekommen. Die fatale Folge: Das Browser-Tracking bildet nur
                einen kleinen Prozentsatz der Daten ab.
              </p>
              <p>
                Wenn von 10 Verkäufen nur 3 angezeigt werden, werden Budgets von
                Kunden zwangsläufig teils verschleudert, weil es gar keine
                exakte Möglichkeit der Kontrolle, Nachverfolgung und Optimierung
                der Kampagnen gibt. Damit lässt sich keine sinnvolle Planung der
                Werbekampagnen durchführen, weil eben nicht genau gesagt werden
                kann, welche Werbung zu welchem Ergebnis geführt hat.
              </p>
              <p>
                Die Folgen sind teuer: Wenig effektive Werbeschaltungen werden
                nicht erkannt und daher unnötig weitergeführt, während die
                Kampagnen, die wirklich zu Umsätzen führen nicht verfeinert
                werden können, weil sie einfach nicht erkannt werden.
              </p>
              <div>
                <button
                  class="border-2 rounded-full border-green-500 p-4 text-white hover:text-green-600 bg-green-500 hover:bg-white transition duration-300"
                >
                  KONTAKT AUFNEHMEN
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <HomeStats />
  </div>
</template>

<script setup></script>

<style scoped></style>
