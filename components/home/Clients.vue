<template>
  <div class="bg-zinc-700">
    <div class="container lg:px-20 px-5 mx-auto">
      <Splide
        :options="{
          type: 'loop',
          perPage: 7,
          perMove: 7,
          speed: 2000,
          interval: 1,
          breakpoints: {
            640: {
              perPage: 2,
              perMove: 2,
              speed: 2000,
              autoWidth: true,
            },
          },
          pagination: false,
          arrows: false,
          autoplay: true,
          pauseOnFocus: false,
          pauseOnHover: false,
          easing: 'ease-in-out',
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
            alt="flughafen_zuerich"
            class="h-24"
          />
        </SplideSlide>
        <SplideSlide>
          <img src="~/assets/images/clients/helsana.png" alt="helsana" class="h-24" />
        </SplideSlide>
        <SplideSlide>
          <img src="~/assets/images/clients/hilding_anders.png" alt="hilding_anders" class="h-24" />
        </SplideSlide>
        <SplideSlide>
          <img src="~/assets/images/clients/hornbach_weiss.png" alt="hornbach_weiss" class="h-24" />
        </SplideSlide>
        <SplideSlide>
          <img src="~/assets/images/clients/mobiliar.png" alt="mobiliar" class="h-24" />
        </SplideSlide>
        <SplideSlide>
          <img src="~/assets/images/clients/newhome.png" alt="newhome" class="h-24" />
        </SplideSlide>
        <SplideSlide>
          <img src="~/assets/images/clients/ramseier.png" alt="ramseier" class="h-24" />
        </SplideSlide>
        <SplideSlide>
          <img src="~/assets/images/clients/sanitas.png" alt="sanitas" class="h-24" />
        </SplideSlide>
        <SplideSlide>
          <img src="~/assets/images/clients/starbucks.png" alt="starbucks" class="h-24" />
        </SplideSlide>
        <SplideSlide>
          <img src="~/assets/images/clients/swisscom.png" alt="swisscom" class="h-24" />
        </SplideSlide>
        <SplideSlide>
          <img src="~/assets/images/clients/wallis.png" alt="wallis" class="h-24" />
        </SplideSlide>
        <SplideSlide>
          <img src="~/assets/images/clients/wingo.png" alt="wingo" class="h-24" />
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
