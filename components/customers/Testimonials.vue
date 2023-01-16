<template>
  <section class="text-gray-600 body-font customer__background">
    <div class="mx-auto flex py-20 items-center">
      <div class="flex px-5 py-20 bg-white/50 w-full">
        <img
          src="~/assets/images/testimonials/shop_logo.jpeg"
          alt="Shop Image"
          class="self-start h-16 w-16 object-cover"
        />
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.customer__background {
  background: url("~/assets/images/customers_bg.jpg");
  background-position: fixed;
  background-size: cover;
}
</style>
