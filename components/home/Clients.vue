<template>
  <div class="bg-zinc-700">
    <div class="max-w-screen-xl mx-auto">
      <Splide
        :options="{
          type: 'loop',
          perPage: 7,
          mediaQuery: 'max',
          breakpoints: {
            640: {
              perPage: 4,
              autoWidth: true,
            },
          },
          perMove: 1,
          pagination: false,
          arrows: false,
          autoplay: true,
          interval: 2000,
          pauseOnFocus: false,
          pauseOnHover: false,
          speed: 4000,
        }"
      >
        <SplideSlide>
          <img src="~/assets/images/clients/banknow_weiss.png" alt="Banknow Weiss" class="h-24" />
        </SplideSlide>

        <SplideSlide>
          <img src="~/assets/images/clients/dieci.png" alt="Dieci" class="h-24" />
        </SplideSlide>

        <SplideSlide>
          <img src="~/assets/images/clients/edelweiss.png" alt="EdelWeiss" class="h-24" />
        </SplideSlide>

        <SplideSlide>
          <img
            src="~/assets/images/clients/feldschloesschen.png"
            alt="Feldschloesschen"
            class="h-24"
          />
        </SplideSlide>
        <SplideSlide>
          <img
            src="~/assets/images/clients/flughafen_zuerich.png"
            alt="Feldschloesschen"
            class="h-24"
          />
        </SplideSlide>
        <SplideSlide>
          <img src="~/assets/images/clients/helsana.png" alt="Feldschloesschen" class="h-24" />
        </SplideSlide>
        <SplideSlide>
          <img
            src="~/assets/images/clients/hilding_anders.png"
            alt="Feldschloesschen"
            class="h-24"
          />
        </SplideSlide>
        <SplideSlide>
          <img
            src="~/assets/images/clients/hornbach_weiss.png"
            alt="Feldschloesschen"
            class="h-24"
          />
        </SplideSlide>
        <SplideSlide>
          <img src="~/assets/images/clients/mobiliar.png" alt="Feldschloesschen" class="h-24" />
        </SplideSlide>
        <SplideSlide>
          <img src="~/assets/images/clients/newhome.png" alt="Feldschloesschen" class="h-24" />
        </SplideSlide>
        <SplideSlide>
          <img src="~/assets/images/clients/ramseier.png" alt="Feldschloesschen" class="h-24" />
        </SplideSlide>
        <SplideSlide>
          <img src="~/assets/images/clients/sanitas.png" alt="Feldschloesschen" class="h-24" />
        </SplideSlide>
        <SplideSlide>
          <img src="~/assets/images/clients/starbucks.png" alt="Feldschloesschen" class="h-24" />
        </SplideSlide>
        <SplideSlide>
          <img src="~/assets/images/clients/swisscom.png" alt="Feldschloesschen" class="h-24" />
        </SplideSlide>
        <SplideSlide>
          <img src="~/assets/images/clients/wallis.png" alt="Feldschloesschen" class="h-24" />
        </SplideSlide>
        <SplideSlide>
          <img src="~/assets/images/clients/wingo.png" alt="Feldschloesschen" class="h-24" />
        </SplideSlide>
      </Splide>
    </div>
  </div>
</template>

<script>
import { Splide, SplideSlide } from "@splidejs/vue-splide";

import "@splidejs/vue-splide/css";
export default defineComponent({
  components: {
    Splide,
    SplideSlide,
  },
});
</script>

<style scoped></style>
