<template>
  <section class="text-gray-800 body-font customer__background">
    <div class="mx-auto flex py-20 items-center">
      <div class="flex px-5 py-20 md:flex-nowrap flex-wrap gap-20 bg-white/50 items-center w-full">
        <div class="flex gap-4">
          <img
            src="~/assets/images/testimonials/shop_logo.jpeg"
            alt="Shop"
            class="self-start h-12 w-12"
          />
          <div class="w-full">
            <h4 class="text-sm font-bold">Ads-Tracking</h4>
            <span class="inline-flex">
              <b class="text-xl mr-2 text-[#e7711b]">5.0 </b>
              <StarIcon class="w-6 h-6 fill-[#e7711b]" />
              <StarIcon class="w-6 h-6 fill-[#e7711b]" />
              <StarIcon class="w-6 h-6 fill-[#e7711b]" />
              <StarIcon class="w-6 h-6 fill-[#e7711b]" />
              <StarIcon class="w-6 h-6 fill-[#e7711b]"
            /></span>
            <img
              src="~/assets/images/testimonials/powered_by_google.png"
              alt="Powered BY Google"
              class="w-36 mb-2"
            />
            <a
              href="https://www.google.com/search?hl=en-PK&gl=pk&q=Ads-Tracking,+Michael-Vehe-Stra%C3%9Fe+17,+74078+Heilbronn,+Germany&ludocid=5204919308249708577&lsig=AB86z5Xps6M4ziGODn_tlqDreM2c&_ga=2.105905411.1052110985.1673541013-1225207782.1673541013"
              class="inline-flex gap-2 items-center bg-[#427fed] text-white shadow-md py-2 px-4 rounded-full text-sm"
            >
              <span>bewerten Sie uns auf</span>

              <svg viewBox="0 0 512 512" height="24" width="24" class="bg-white rounded-full p-1">
                <g fill="none" fill-rule="evenodd">
                  <path
                    d="M482.56 261.36c0-16.73-1.5-32.83-4.29-48.27H256v91.29h127.01c-5.47 29.5-22.1 54.49-47.09 71.23v59.21h76.27c44.63-41.09 70.37-101.59 70.37-173.46z"
                    fill="#4285f4"
                  ></path>
                  <path
                    d="M256 492c63.72 0 117.14-21.13 156.19-57.18l-76.27-59.21c-21.13 14.16-48.17 22.53-79.92 22.53-61.47 0-113.49-41.51-132.05-97.3H45.1v61.15c38.83 77.13 118.64 130.01 210.9 130.01z"
                    fill="#34a853"
                  ></path>
                  <path
                    d="M123.95 300.84c-4.72-14.16-7.4-29.29-7.4-44.84s2.68-30.68 7.4-44.84V150.01H45.1C29.12 181.87 20 217.92 20 256c0 38.08 9.12 74.13 25.1 105.99l78.85-61.15z"
                    fill="#fbbc05"
                  ></path>
                  <path
                    d="M256 113.86c34.65 0 65.76 11.91 90.22 35.29l67.69-67.69C373.03 43.39 319.61 20 256 20c-92.25 0-172.07 52.89-210.9 130.01l78.85 61.15c18.56-55.78 70.59-97.3 132.05-97.3z"
                    fill="#ea4335"
                  ></path>
                  <path d="M20 20h472v472H20V20z"></path>
                </g>
              </svg>
            </a>
          </div>
        </div>
        <div class="lg:max-w-4xl md:max-w-md max-w-xs">
          <Splide
            :options="{
              rewind: true,
              perPage: 3,
              perMove: 1,
              interval: 2000,
              gap: 10,
              breakpoints: {
                980: {
                  perPage: 2,
                },
                640: {
                  perPage: 1,
                },
              },
            }"
          >
            <SplideSlide>
              <div id="card" class="bg-white p-4 shadow-smd shadow-gray-500 rounded-md max-w-xs">
                <div class="flex mb-4 gap-2">
                  <img
                    src="~/assets/images/testimonials/larissa.png"
                    alt="larissa"
                    class="drop-shadow-md"
                  />
                  <div>
                    <h4 class="text-[#427fed] font-bold">Larissa Fricke</h4>
                    <p class="text-xs text-gray-600">9 months ago</p>
                  </div>
                </div>
                <div class="flex my-2">
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                </div>
                <div>
                  <p class="text-xs leading-relaxed font-medium h-20 overflow-y-auto">
                    Gute Firma. Sehr kenntnisreich und sehr erfahren in Sachen Web-Analytics und
                    Online-Marketing-Daten. Absolut empfehlenswert!
                  </p>
                </div>
              </div>
            </SplideSlide>

            <SplideSlide>
              <div id="card" class="bg-white p-4 shadow-md shadow-gray-500 rounded-md max-w-xs">
                <div class="flex mb-4 gap-2">
                  <img
                    src="~/assets/images/testimonials/alyena.png"
                    alt="Alyena"
                    class="drop-shadow-md"
                  />
                  <div>
                    <h4 class="text-[#427fed] font-bold">alyena Kzi</h4>
                    <p class="text-xs text-gray-600">10 months ago</p>
                  </div>
                </div>
                <div class="flex my-2">
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                </div>
                <div>
                  <p class="text-xs leading-relaxed font-medium h-20 overflow-y-auto">
                    Uns wurden mittlerweile all unsere Tracking Probleme nachhaltig behoben.
                    Professioneller Service und absolut empfehlenswert!
                  </p>
                </div>
              </div>
            </SplideSlide>
            <SplideSlide>
              <div id="card" class="bg-white p-4 shadow-smd shadow-gray-500 rounded-md max-w-xs">
                <div class="flex mb-4 gap-2">
                  <img
                    src="~/assets/images/testimonials/regina.png"
                    alt="regina"
                    class="drop-shadow-md"
                  />
                  <div>
                    <h4 class="text-[#427fed] font-bold">Regina Radisch</h4>
                    <p class="text-xs text-gray-600">12 months ago</p>
                  </div>
                </div>
                <div class="flex my-2">
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                </div>
                <div>
                  <p class="text-xs leading-relaxed font-medium h-20 overflow-y-auto">
                    Hat super geklappt, vielen lieben Dank, bin sehr zufrieden
                  </p>
                </div>
              </div>
            </SplideSlide>
            <SplideSlide>
              <div id="card" class="bg-white p-4 shadow-md shadow-gray-500 rounded-md max-w-xs">
                <div class="flex mb-4 gap-2">
                  <img
                    src="~/assets/images/testimonials/rene_ostertag.png"
                    alt="rene_ostertag"
                    class="drop-shadow-md"
                  />
                  <div>
                    <h4 class="text-[#427fed] font-bold">Rene Ostertag</h4>
                    <p class="text-xs text-gray-600">12 months ago</p>
                  </div>
                </div>
                <div class="flex my-2">
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                </div>
                <div>
                  <p class="text-xs leading-relaxed font-medium h-20 overflow-y-auto">
                    Mega Service kann ich nur empfehlen der Probleme mit Facebook Tracking hat
                  </p>
                </div>
              </div>
            </SplideSlide>
            <SplideSlide>
              <div id="card" class="bg-white p-4 shadow-smd shadow-gray-500 rounded-md max-w-xs">
                <div class="flex mb-4 gap-2">
                  <img
                    src="~/assets/images/testimonials/joël_irniger.png"
                    alt="Joel_Irniger"
                    class="drop-shadow-md"
                  />
                  <div>
                    <h4 class="text-[#427fed] font-bold">Joël Irniger</h4>
                    <p class="text-xs text-gray-600">12 months ago</p>
                  </div>
                </div>
                <div class="flex my-2">
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                </div>
                <div>
                  <p class="text-xs leading-relaxed font-medium h-20 overflow-y-auto">
                    Ich nutze den Service nun schon bei mittlerweile 3 Shops. Sehr professionelles
                    Auftreten und man bekommt wirklich, was versprochen wird. Seit dem das
                    ADS-Tracking integriert wurde gehen die Verkäufe wieder Bergauf! Kann ich nur
                    jedem der im E-Commerce tätig ist empfehlen - ein absolutes MUSS!
                  </p>
                </div>
              </div>
            </SplideSlide>
            <SplideSlide>
              <div id="card" class="bg-white p-4 shadow-md shadow-gray-500 rounded-md max-w-xs">
                <div class="flex mb-4 gap-2">
                  <img
                    src="~/assets/images/testimonials/eyup_karaver.png"
                    alt="Eyup Karaver"
                    class="drop-shadow-md"
                  />
                  <div>
                    <h4 class="text-[#427fed] font-bold">Eyüp Karavar</h4>
                    <p class="text-xs text-gray-600">12 months ago</p>
                  </div>
                </div>
                <div class="flex my-2">
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                </div>
                <div>
                  <p class="text-xs leading-relaxed font-medium h-20 overflow-y-auto">
                    Einer der Dienstleister die ihr Handwerk verstehen, jetzt ist es egal ob mit iOS
                    14,5 Nutzer oder anderen blockierten Apps, die Daten kommen vollständig und
                    zeigen genau da an wo wir sie brauchen, eine Reduzierung der werbe kosten und
                    Steigerung der Umsätze alle Erwartungen übertroffen!
                  </p>
                </div>
              </div>
            </SplideSlide>
            <SplideSlide>
              <div id="card" class="bg-white p-4 shadow-smd shadow-gray-500 rounded-md max-w-xs">
                <div class="flex mb-4 gap-2">
                  <img
                    src="~/assets/images/testimonials/anton_perl.png"
                    alt="Anton Perl"
                    class="drop-shadow-md"
                  />
                  <div>
                    <h4 class="text-[#427fed] font-bold">Anton Perl</h4>
                    <p class="text-xs text-gray-600">12 months ago</p>
                  </div>
                </div>
                <div class="flex my-2">
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                </div>
                <div>
                  <p class="text-xs leading-relaxed font-medium h-20 overflow-y-auto">
                    Ich muss euch echt danken! Verlässliche Zahlen seiner Ads zu bekommen und das
                    plattformübergreifend ist heute wirklich nichts selbstverständliches mehr!Umso
                    dankbarer waren wir, als wir von dem Service von Ads-Tracking gehört haben.Uns
                    wurden mittlerweile all unsere Tracking Probleme nachhaltig behoben.Ich kann die
                    Jungs von Ads-Tracking wärmstens weiterempfehlen. Sie haben für gefühlt jedes
                    Problem eine schnelle und zuverlässige Lösung parat und sind zu jederzeit sofort
                    erreichbar.Ein bis jetzt rundum perfekter Service - weiter so!
                  </p>
                </div>
              </div>
            </SplideSlide>
            <SplideSlide>
              <div id="card" class="bg-white p-4 shadow-md shadow-gray-500 rounded-md max-w-xs">
                <div class="flex mb-4 gap-2">
                  <img
                    src="~/assets/images/testimonials/boss.png"
                    alt="Boss"
                    class="drop-shadow-md"
                  />
                  <div>
                    <h4 class="text-[#427fed] font-bold">Boss Boss</h4>
                    <p class="text-xs text-gray-600">12 months ago</p>
                  </div>
                </div>
                <div class="flex my-2">
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                  <StarIcon class="w-5 h-5 fill-[#e7711b]" />
                </div>
                <div>
                  <p class="text-xs leading-relaxed font-medium h-20 overflow-y-auto">
                    Super macht weiter so. Top Einrichtung super Daten alles wie erwünscht
                  </p>
                </div>
              </div>
            </SplideSlide>
          </Splide>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import { StarIcon } from "@heroicons/vue/24/solid/index.js";
import { Splide, SplideSlide } from "@splidejs/vue-splide";
export default {
  components: {
    StarIcon,
    Splide,
    SplideSlide,
  },
};
</script>

<style scoped>
.customer__background {
  background: url("~/assets/images/customers_bg.jpg");
  background-attachment: fixed;
  background-size: cover;
}
</style>
