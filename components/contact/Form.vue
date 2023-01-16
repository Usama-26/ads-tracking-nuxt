<template>
  <div>
    <div
      class="bg-white container w-full mx-auto lg:-translate-y-40 shadow-2xl shadow-gray-300"
    >
      <div class="flex lg:flex-row flex-col gap-4">
        <div class="lg:w-2/3 w-full py-16 px-10">
          <div class="text-left">
            <h1 class="sm:text-2xl text-3xl text-gray-500 font-bold">
              Jetzt Kontakt aufnehmen!
            </h1>
            <div class="border-b-4 w-24 border-[#34cc81] inline-block"></div>
          </div>
          <form class="py-6">
            <div class="w-full flex md:flex-nowrap flex-wrap gap-4 mb-4">
              <input
                type="text"
                placeholder="Name"
                name="name"
                id="name"
                class="p-4 border md:w-1/2 w-full"
              />
              <input
                type="email"
                placeholder="E-Mail Addresse"
                class="p-4 border md:w-1/2 w-full"
                id="email"
                name="email"
              />
            </div>
            <div class="w-full flex md:flex-nowrap flex-wrap gap-4 mb-4">
              <input
                type="text"
                id="phone"
                name="phone"
                placeholder="Telefone"
                class="p-4 border md:w-1/2 w-full"
                pattern="[0-9\s-]*"
              />
              <input
                type="text"
                id="website"
                name="website"
                placeholder="Webseite"
                class="p-4 border md:w-1/2 w-full"
                pattern="[0-9\s-]*"
              />
            </div>
            <textarea
              name="message"
              id="message"
              placeholder="Haben Sie Anregungen oder Fragen zu unseren Leistungen? Haben Sie ein konkretes Projekt in Planung oder brauchen Sie Unterstützung bei einer Problemstellung? Dann kontaktieren Sie uns doch einfach!"
              class="resize-none w-full p-4 h-40 text-sm border mb-4"
            ></textarea>
            <div class="flex justify-end">
              <button
                type="submit"
                class="px-8 py-4 bg-[#34cc81] text-center font-bold text-white hover:bg-green-600"
              >
                SENDEN
              </button>
            </div>
          </form>
        </div>
        <div class="lg:w-1/3 w-full bg-[#212940]">
          <div class="py-12 px-16 text-white">
            <h1 class="text-2xl">Kontaktdetails</h1>
            <h5 class="text-md ml-4 my-8 w-48">
              Wir freuen uns darauf, Sie und Ihr Unternehmen kennenzulernen!
            </h5>
            <div class="my-8">
              <div class="flex gap-4 my-4">
                <DevicePhoneMobileIcon class="w-6 h-6 fill-[#34cc81] my-2" />
                <div class="w-48">
                  <h1 class="text-xl font-bold mb-2">Telefone</h1>
                  <a href="tel:+4970669290181" class="text-green-600"
                    >+497066 929 0181</a
                  >
                  <p>Mo-Fr: 09-17 Uhr</p>
                </div>
              </div>
              <div class="flex gap-4 my-4">
                <MapPinIcon class="w-6 h-6 fill-[#34cc81] my-2" />
                <div class="w-48">
                  <h1 class="text-xl font-bold mb-2">Adresse</h1>
                  <p>Michael-Vehe-Straße 17 74078 Heilbronn</p>
                </div>
              </div>
              <div class="flex gap-4 my-4">
                <EnvelopeIcon class="w-6 h-6 fill-[#34cc81] my-2" />
                <div class="w-48">
                  <h1 class="text-xl font-bold mb-2">E-Mail</h1>
                  <a
                    href="mailto:anfrage@ads-tracking.de"
                    class="text-green-600"
                    >anfrage@ads-tracking.de</a
                  >
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import {
  MapPinIcon,
  EnvelopeIcon,
  DevicePhoneMobileIcon,
} from "@heroicons/vue/24/solid/index.js";
export default {
  components: {
    MapPinIcon,
    EnvelopeIcon,
    DevicePhoneMobileIcon,
  },
};
</script>

<style scoped></style>
