<template>
  <div>
    <Navbar />
    <div>
      <slot />
    </div>
    <Footer />
  </div>
</template>

<script setup>
import Footer from "~~/components/Footer.vue";
</script>

<style lang="scss" scoped></style>
