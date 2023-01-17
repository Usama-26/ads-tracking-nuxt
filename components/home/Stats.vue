<template>
  <section class="text-gray-600 bg-[#34cc81dd] body-font">
    <div class="container lg:px-24 px-5 py-16 mx-auto">
      <div class="flex flex-col lg:gap-24 md:flex-row sm:items-center items-start justify-between">
        <div>
          <h1 class="text-2xl font-bold mb-4 text-gray-100">
            KUNDEN TROTZ ADBLOCKER ODER IOS 14 TRACKEN UND MEHR ERKENNTNISSE ERHALTEN
          </h1>
          <p class="text-white font-medium leading-7">
            Seit langer Zeit besteht das Problem, dass User die einen Ad Blocker nutzen, nicht
            trackbar waren. Mit serverseitigem Tracking ist es nun wieder möglich, bis zu 100% der
            Conversions in Facebook & Co zu messen.
          </p>
        </div>
        <div class="text-center font-bold text-white mx-auto lg:mt-0 mt-10">
          <h2>Zusätzliche</h2>
          <h1 class="text-4xl font-normal my-2">60%</h1>
          <h4>erfassbare Daten</h4>
        </div>
        <div class="text-center font-bold text-white mx-auto lg:mt-0 mt-10">
          <h2>Bis zu</h2>
          <h1 class="text-4xl font-normal my-2">100%</h1>
          <h4>der Daten trackbar</h4>
        </div>
      </div>
    </div>
  </section>
</template>

<script></script>

<style scoped>
@property --num {
  syntax: "<integer>";
  initial-value: 0;
}

div {
  transition: --num 1s;
  counter-reset: num var(--num);
}
div:hover {
  --num: 10000;
}
div::after {
  content: counter(num);
}
</style>
