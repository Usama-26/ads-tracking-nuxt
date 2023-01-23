<template>
  <div>
    <section class="text-gray-600 bg-white">
      <div class="container px-5 py-24 mx-auto">
        <div class="mx-5 lg:mx-20 mb-10">
          <h1 class="sm:text-4xl text-3xl font-bold title-font text-gray-900">
            Ihr Schritt zu erfolgreichem Marketing: Rufen Sie uns an
          </h1>
          <span class="inline-block h-1 w-20 mt-4 rounded bg-green-500"></span>
          <h3 class="font-medium text-xl text-gray-600 mt-10">
            Nur ein <b>Anruf</b> oder Klick genügt und Sie sind der
            <b>Lösung</b>
            eines der scheinbar unlösbaren <b>Marketingprobleme</b> bereits ein <b>gutes</b> Stück
            näher.
          </h3>
        </div>

        <div class="flex lg:flex-nowrap flex-wrap mx-5 lg:mx-20 gap-4">
          <div class="p-4 lg:w-1/4 sm:w-1/2 w-full">
            <div id="teamMember" class="relative flex flex-col items-center text-center">
              <img
                alt="Bünyamin Alirkilicarslan"
                class="flex-shrink-0 w-full h-60 object-cover object-center"
                src="~/assets/images/team-1.jpg"
              />
              <div class="overlay bg-[#34cc81aa] transition duration-300">
                <div class="overlay-text text-white">
                  <h2 class="title-font font-medium text-lg">Bünyamin Alirkilicarslan</h2>
                  <h3 class="mb-3 text-sm">CEO & Gründer</h3>
                </div>
              </div>
            </div>
          </div>
          <div class="p-4 lg:w-1/4 sm:w-1/2 w-full">
            <div id="teamMember" class="relative flex flex-col items-center text-center">
              <img
                alt="Sophia Becker"
                class="flex-shrink-0 w-full h-60 object-cover object-center"
                src="~/assets/images/team-2.jpg"
              />
              <div class="overlay bg-[#34cc81aa] transition duration-300">
                <div class="overlay-text text-white">
                  <h2 class="title-font font-medium text-lg">Sophia Becker</h2>
                  <h3 class="mb-3 text-sm">CRO</h3>
                </div>
              </div>
            </div>
          </div>
          <div class="p-4 lg:w-1/4 sm:w-1/2 w-full">
            <div id="teamMember" class="relative flex flex-col items-center text-center">
              <img
                alt="Ben Simon"
                class="flex-shrink-0 w-full h-60 object-cover object-center"
                src="~/assets/images/team-3.png"
              />
              <div class="overlay bg-[#34cc81aa] transition duration-300">
                <div class="overlay-text text-white">
                  <h2 class="title-font font-medium text-lg">Ben Simon</h2>
                  <h3 class="mb-3 text-sm">Technischer Projektleiter</h3>
                </div>
              </div>
            </div>
          </div>
          <div class="p-4 lg:w-1/4 sm:w-1/2 w-full">
            <div id="teamMember" class="relative flex flex-col items-center text-center">
              <img
                alt="Emilia Voigt"
                class="flex-shrink-0 w-full h-60 object-cover object-center"
                src="~/assets/images/team-4.png"
              />
              <div class="overlay bg-[#34cc81aa] transition duration-300">
                <div class="overlay-text text-white">
                  <h2 class="title-font font-medium text-lg">Emilia Voigt</h2>
                  <h3 class="mb-3 text-sm">Web-Tracking-Ingenieur</h3>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script></script>

<style scoped>
.overlay {
  position: absolute;
  top: 0%;
  left: 0%;
  width: 100%;
  height: 100%;
  text-align: center;
}

.overlay-text {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

#teamMember .overlay {
  opacity: 0;
}
#teamMember:hover .overlay {
  opacity: 1;
}
</style>
