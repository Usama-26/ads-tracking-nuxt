<template>
  <div class="bg-gray-50">
    <HomeHero />
    <HomeClients />
    <HomeFeatures />
    <HomeStats />
    <!-- Checklist Section --iOS 14 Stuff -->
    <section class="text-gray-600">
      <div class="container px-5 py-24 mx-auto">
        <div class="lg:mx-20 mx-5">
          <h1 class="sm:text-4xl text-3xl font-bold title-font text-gray-900">
            Wenn Ihnen das bekannt vorkommt, brauchen Sie Ads-Tracking
          </h1>
          <span class="inline-block h-1 w-20 mt-4 rounded bg-[#34cc81]"></span>
        </div>

        <div class="flex md:flex-row flex-col lg:mx-20 mx-5 gap-16 mt-10">
          <div class="bg-gray-200 rounded-md basis-2/6 -rotate-3">
            <ul class="lg:m-0 mx-4 xl:p-10 p-4 font-medium text-[18px]">
              <li class="my-2 flex gap-2">
                <img src="~/assets/icons/checkbox.svg" alt="check" class="self-start" />
                <span>Ich muss die Tracking-Qualität aufgrund von iOS 14 und 15 verbessern</span>
              </li>
              <li class="my-2 flex gap-2">
                <img src="~/assets/icons/checkbox.svg" alt="check" class="self-start" />
                <span>Ich möchte die Conversion-Genauigkeit maximieren</span>
              </li>
              <li class="my-2 flex gap-2">
                <img src="~/assets/icons/checkbox.svg" alt="check" class="self-start" />
                <span>
                  Meine Agentur braucht mich, um mein Tracking für Google Ads, Facebook, GA zu
                  korrigieren</span
                >
              </li>
              <li class="my-2 flex gap-2">
                <img src="~/assets/icons/checkbox.svg" alt="check" class="self-start" /><span
                  >Meine Datenschicht für den Google Tag Manager ist ein Durcheinander</span
                >
              </li>
              <li class="my-2 flex gap-2">
                <img src="~/assets/icons/checkbox.svg" alt="check" class="self-start" /><span
                  >Ich benötige Tracking, das DSGVO-konform ist</span
                >
              </li>
              <li class="my-2 flex gap-2">
                <img src="~/assets/icons/checkbox.svg" alt="check" class="self-start" /><span
                  >Ich vertraue meinen Google Analytics-Daten nicht</span
                >
              </li>
            </ul>
          </div>
          <div class="basis-4/6 self-start lg:text-xl text-md leading-7 font-medium">
            <p class="mb-8">
              Exakte Daten aus der Ad-Performance sind seit <b>IOS 14</b> und durch das zunehmende,
              teils sogar standardmäßig voreingestellte <b>Trackingverbot</b> auf den Endgeräten der
              User kaum noch zu bekommen. Die fatale Folge: Das <b>Browser-Tracking</b> bildet nur
              einen kleinen Prozentsatz der Daten ab.
            </p>
            <p class="mb-8">
              Wenn von <b>10</b> Verkäufen nur <b>3</b> angezeigt werden, werden Budgets von Kunden
              zwangsläufig teils <b>verschleudert</b>, weil es gar keine exakte Möglichkeit der
              Kontrolle, Nachverfolgung und Optimierung der Kampagnen gibt. Damit lässt sich keine
              <b>sinnvolle</b> Planung der Werbekampagnen durchführen, weil eben nicht genau gesagt
              werden kann, welche Werbung zu welchem <b>Ergebnis </b> geführt hat.
            </p>
            <p>
              Die Folgen sind <b>teuer</b>: Wenig effektive Werbeschaltungen werden nicht erkannt
              und daher unnötig weitergeführt, während die Kampagnen, die wirklich zu
              <b>Umsätzen</b> führen nicht verfeinert werden können, weil sie einfach nicht
              <b>erkannt</b> werden.
            </p>
            <div>
              <NuxtLink
                to="/contact"
                class="border-2 rounded-full border-[#34cc81] px-4 py-3 tracking-[2px] text-sm inline-block mt-4 text-white hover:text-green-600 bg-[#34cc81] hover:bg-white transition duration-300 font-bold"
              >
                KONTAKT AUFNEHMEN
              </NuxtLink>
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
          <NuxtLink
            to="/contact"
            class="border-2 rounded-full mx-auto border-white p-4 text-white font-bold tracking-wider hover:bg-green-600 hover:border-green-600 transition duration-300"
          >
            JETZT ANFRAGEN
          </NuxtLink>
        </div>
      </div>
    </section>
    <!-- More Features -->
    <section class="text-gray-600 body-font bg-gray-200">
      <div class="container px-5 py-24 mx-auto">
        <div class="flex flex-col w-full lg:mb-20 mb-10">
          <h1 class="text-4xl mx-5 lg:mx-20 font-bold title-font text-gray-900">
            Jetzt die Vorteile von Serverside-Tracking nutzen
          </h1>
          <span class="inline-block h-1 w-20 lg:mx-20 mx-5 mt-4 rounded bg-[#34cc81]"></span>
        </div>
        <div class="flex lg:flex-nowrap flex-wrap gap-8 lg:mx-20 mx-5 justify-evenly">
          <div class="lg:w-1/3 w-full">
            <div class="flex rounded-xl h-full shadow-lg text-center bg-white p-8 flex-col">
              <img src="~/assets/images/laptop.svg" alt="Laptop Icon" class="w-24 h-24 mx-auto" />

              <h2 class="font-bold text-xl my-4 text-gray-900">
                Beschleunigen Sie die tägliche Berichterstattung
              </h2>

              <div>
                <p class="leading-relaxed w-full mx-auto">
                  Verbringen Sie
                  <b class="text-"> keine </b> Zeit damit, <b class="text-">Formeln</b> zu erstellen
                  und Daten in Excel-Dokumenten zu <b class="text-">sammeln</b>. Erhalten Sie
                  Zugriff auf <b class="text-">leistungsstarke</b> Dashboards, die alle KPIs über
                  Ihren <b class="text-">Medieneinkauf</b> und die Leistung Ihrer Partner in
                  <b class="text-">Echtzeit</b> anzeigen.
                </p>
              </div>
            </div>
          </div>
          <div class="lg:w-1/3 w-full">
            <div class="flex rounded-xl h-full shadow-lg text-center bg-white p-8 flex-col">
              <img src="~/assets/images/money-filter.svg" alt="Filter" class="w-24 h-24 mx-auto" />

              <h2 class="font-bold text-xl my-4 text-gray-900">
                Messen Sie Ihre Multi-Channel-Werbung
              </h2>

              <div>
                <p class="leading-relaxed w-full mx-auto">
                  Überwachen Sie auf <b class="text-">einfache</b> und
                  <b class="text-">unkomplizierte</b> Weise, woher der Datenverkehr kommt. Erkennen
                  Sie, welche Besuche zu <b class="text-">Conversions</b> werden, weisen Sie das
                  <b class="text-">Budget</b> dem zu, was am besten funktioniert, und
                  <b class="text-">eliminieren</b> Sie
                  <b class="text-">verschwendete</b>
                  Werbeausgaben.
                </p>
              </div>
            </div>
          </div>
          <div class="lg:w-1/3 w-full">
            <div class="flex rounded-xl h-full shadow-lg text-center bg-white p-8 flex-col">
              <img src="~/assets/images/cookies.svg" alt="Cookies Icon" class="w-24 h-24 mx-auto" />
              <h2 class="font-bold text-xl my-4 text-gray-900">
                Überwinden Sie die Herausforderung der Cookie-Blindheit
              </h2>

              <div>
                <p class="leading-relaxed w-full mx-auto">
                  Der Niedergang von <b class="text-">Cookies</b> von Drittanbietern macht eine
                  genaue <b class="text-"> Verfolgung </b> und
                  <b class="text-">Zuordnung</b>
                  schwierig, wenn nicht sogar unmöglich. Mit der
                  <b class="text-">cookielosen</b>
                  <b class="text-">Tracking-Lösung</b> von Ads-Tracking füllen Sie die
                  <b class="text-">Lücken</b> und erhalten die volle
                  <b class="text-">Kontrolle</b> über die
                  <b class="text-">Leistung</b>
                  jedes Schritts der Reise Ihrer Kunden.
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="flex mx-5 lg:mx-20">
          <NuxtLink
            to="/contact"
            class="border-2 inline-block rounded-full lg:self-start self-center border-[#34cc81] p-4 mt-4 text-white hover:text-green-600 bg-[#34cc81] hover:bg-white transition duration-300 tracking-wider font-bold"
          >
            KONTAKT AUFNEHMEN
          </NuxtLink>
        </div>
      </div>
    </section>
    <HomeTeam />

    <section class="text-gray-600 bg-[#34cc81dd] body-font">
      <div class="container px-5 py-16 mx-auto">
        <div
          class="lg:w-4/5 flex flex-col gap-8 sm:items-center items-start justify-between mx-auto"
        >
          <h1 class="text-3xl text-center mx-auto font-bold text-gray-100">
            Jetzt kostenloses Beratungs­gespräch vereinbaren!
          </h1>
          <NuxtLink
            to="/contact"
            class="border-2 rounded-full mx-auto border-white p-4 text-white font-bold tracking-wider hover:bg-green-600 hover:border-green-600 transition duration-300"
          >
            JETZT ANFRAGEN
          </NuxtLink>
        </div>
      </div>
    </section>
  </div>
</template>

<script></script>

<style scoped></style>
