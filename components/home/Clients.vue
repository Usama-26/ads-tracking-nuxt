<template>
  <div class="bg-zinc-700">
    <Splide
      :options="{
        rewind: true,
        height: '80px',
        arrows: false,
        pagination: false,
        autoplay: true,
      }"
      :extensions="AutoScroll"
    >
      <SplideSlide>
        <img src="~assets/images/clients/edelweiss.png" alt="Client" />
      </SplideSlide>
      <SplideSlide>
        <img src="~assets/images/clients/helsana.png" alt="Client" />
      </SplideSlide>
    </Splide>
  </div>
</template>

<script>
import { Splide, SplideSlide } from "@splidejs/vue-splide";
import { AutoScroll } from "@splidejs/splide-extension-auto-scroll";
import "@splidejs/vue-splide/css";
export default defineComponent({
  components: { Splide, SplideSlide, AutoScroll },
});
</script>

<style scoped></style>
