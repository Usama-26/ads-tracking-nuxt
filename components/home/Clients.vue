<template>
  <div class="bg-gray-900">
    <Splide :options="{ rewind: true, height: '100px' }">
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
import "@splidejs/vue-splide/css";
export default defineComponent({
  components: { Splide, SplideSlide },
});
</script>

<style scoped></style>
