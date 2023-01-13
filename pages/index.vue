<template>
  <div class="bg-gray-100">
    <HomeHero />
    <HomeClients />
    <HomeFeatures />
    <HomeStats />
    <!-- Checklist Section --iOS 14 Stuff -->
    <section class="text-gray-600">
      <div class="container px-5 py-24 mx-auto">
        <div class="flex flex-col w-full lg:mb-20 mb-10">
          <div class="lg:mx-20 mx-8">
            <h1 class="sm:text-4xl text-3xl font-bold title-font text-gray-900">
              Wenn Ihnen das bekannt vorkommt, brauchen Sie Ads-Tracking
            </h1>
            <span
              class="inline-block h-1 w-20 mt-4 rounded bg-green-500"
            ></span>
          </div>
          <div class="flex lg:flex-row flex-col lg:mx-20 mx-8 gap-24 mt-20">
            <div class="bg-gray-200 rounded-md p-8 lg:w-72 lg:-rotate-3">
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
            <div
              class="max-w-2xl flex flex-col gap-4 lg:text-xl text-md leading-7 font-medium"
            >
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
                  class="border-2 rounded-full border-green-500 p-4 mt-4 text-white hover:text-green-600 bg-green-500 hover:bg-white transition duration-300 tracking-wider font-bold"
                >
                  KONTAKT AUFNEHMEN
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <HomeVideoSection />
    <!-- Inquire Section -->
    <section class="text-gray-600 bg-[#34cc81dd] body-font">
      <div class="container px-5 py-16 mx-auto">
        <div
          class="lg:w-4/5 flex flex-col gap-8 sm:items-center items-start justify-between mx-auto"
        >
          <h1 class="text-3xl text-center mx-auto font-bold text-gray-100">
            Jetzt kostenloses Beratungs­gespräch vereinbaren!
          </h1>
          <button
            class="border-2 rounded-full mx-auto border-white p-4 text-white hover:bg-green-600 hover:border-green-600 transition duration-300"
          >
            JETZT ANFRAGEN
          </button>
        </div>
      </div>
    </section>
    <!-- More Features -->
    <section class="text-gray-600 body-font bg-gray-200">
      <div class="container px-5 py-24 mx-auto">
        <div class="flex flex-col w-full lg:mb-20 mb-10">
          <h1
            class="sm:text-4xl text-3xl lg:mx-20 font-bold title-font text-gray-900"
          >
            Jetzt die Vorteile von Serverside-Tracking nutzen
          </h1>
          <span
            class="inline-block h-1 w-20 lg:mx-20 mt-4 rounded bg-green-500"
          ></span>
        </div>
        <div
          class="flex lg:flex-nowrap flex-wrap gap-8 lg:mx-20 mx-5 justify-evenly"
        >
          <div class="lg:w-1/3 w-full">
            <div
              class="flex rounded-xl h-full shadow-lg text-center bg-white p-8 flex-col"
            >
              <img
                src="~/assets/images/laptop.svg"
                alt="Laptop Icon"
                class="w-24 h-24 mx-auto"
              />

              <h2 class="font-bold text-xl my-4 text-gray-900">
                Beschleunigen Sie die tägliche Berichterstattung
              </h2>

              <div>
                <p class="leading-relaxed lg:w-4/5 sm:w-3/5 w-full mx-auto">
                  Verbringen Sie keine Zeit damit, Formeln zu erstellen und
                  Daten in Excel-Dokumenten zu sammeln. Erhalten Sie Zugriff auf
                  leistungsstarke Dashboards, die alle KPIs über Ihren
                  Medieneinkauf und die Leistung Ihrer Partner in Echtzeit
                  anzeigen.
                </p>
              </div>
            </div>
          </div>
          <div class="lg:w-1/3 w-full">
            <div
              class="flex rounded-xl h-full shadow-lg text-center bg-white p-8 flex-col"
            >
              <img
                src="~/assets/images/money-filter.svg"
                alt="Laptop Icon"
                class="w-24 h-24 mx-auto"
              />

              <h2 class="font-bold text-xl my-4 text-gray-900">
                Messen Sie Ihre Multi-Channel-Werbung
              </h2>

              <div>
                <p class="leading-relaxed lg:w-4/5 sm:w-3/5 w-full mx-auto">
                  Überwachen Sie auf einfache und unkomplizierte Weise, woher
                  der Datenverkehr kommt. Erkennen Sie, welche Besuche zu
                  Conversions werden, weisen Sie das Budget dem zu, was am
                  besten funktioniert, und eliminieren Sie verschwendete
                  Werbeausgaben.
                </p>
              </div>
            </div>
          </div>
          <div class="lg:w-1/3 w-full">
            <div
              class="flex rounded-xl h-full shadow-lg text-center bg-white p-8 flex-col"
            >
              <img
                src="~/assets/images/cookies.svg"
                alt="Laptop Icon"
                class="w-24 h-24 mx-auto"
              />
              <h2 class="font-bold text-xl my-4 text-gray-900">
                Überwinden Sie die Herausforderung der Cookie-Blindheit
              </h2>

              <div>
                <p class="leading-relaxed lg:w-4/5 sm:w-3/5 w-full mx-auto">
                  Der Niedergang von Cookies von Drittanbietern macht eine
                  genaue Verfolgung und Zuordnung schwierig, wenn nicht sogar
                  unmöglich. Mit der cookielosen Tracking-Lösung von
                  Ads-Tracking füllen Sie die Lücken und erhalten die volle
                  Kontrolle über die Leistung jedes Schritts der Reise Ihrer
                  Kunden.
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="mx-20 flex">
          <button
            class="border-2 rounded-full lg:self-start self-center border-green-500 p-4 mt-4 text-white hover:text-green-600 bg-green-500 hover:bg-white transition duration-300 tracking-wider font-bold"
          >
            KONTAKT AUFNEHMEN
          </button>
        </div>
      </div>
    </section>
    <HomeTeam />
  </div>
</template>

<script setup></script>

<style scoped></style>
