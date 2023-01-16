<template>
  <section class="text-gray-800 body-font customer__background">
    <div class="mx-auto flex py-20 items-center">
      <div class="flex px-5 py-20 gap-4 bg-white/50 w-full">
        <div class="flex gap-4">
          <img
            src="~/assets/images/testimonials/shop_logo.jpeg"
            alt="Shop Image"
            class="self-start h-12 w-12"
          />
          <div>
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
              class="w-36"
            />
          </div>
        </div>
        <div></div>
      </div>
    </div>
  </section>
</template>

<script>
import { StarIcon } from "@heroicons/vue/24/solid/index.js";
export default {
  components: {
    StarIcon,
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
