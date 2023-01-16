<template>
  <div>
    <section class="text-gray-600 hero__background">
      <div
        class="container mx-auto flex px-5 py-20 items-center justify-center flex-col"
      >
        <div class="text-left w-4/5">
          <h1 class="title-font sm:text-4xl text-3xl font-medium text-gray-100">
            Tracking ist unsere Leidenschaft
          </h1>
          <div class="border-b-4 w-24 border-green-500 inline-block"></div>
          <p class="my-10 leading-relaxed text-gray-100">
            Nicht nur das, <span class="text-green-500">was</span> wir tun, ist
            entscheidend für unseren gemeinsamen Erfolg. Entscheidend ist auch,
            <span class="text-green-500">wie</span> wir etwas tun. Lesen Sie
            hier, was uns besonders macht und wofür wir stehen.
          </p>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  setup() {
    return {};
  },
};
</script>

<style scoped>
.hero__background {
  background: url("assets/images/clients-bg.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  background-position: 0;
  background-attachment: scroll;
}
</style>
