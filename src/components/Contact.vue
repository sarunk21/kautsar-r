<template>
  <div class="grid grid-cols-12 my-10" id="findMe">
    <h1
      class="
        col-span-12
        color-green
        font-semibold
        text-3xl
        md:text-5xl
        text-center
        mb-6
      "
    >
      Find Me At
    </h1>
    <div class="col-span-12">
      <ul class="flex justify-between overflow-x-auto">
        <li>
          <a target="_blank" href="https://www.instagram.com/kautsar_r/"
            ><i class="fab fa-instagram"></i>
            <span class="hidden md:inline"> Instagram</span></a
          >
        </li>
        <li>
          <a target="_blank" href="https://web.facebook.com/kautsar.mkp/"
            ><i class="fab fa-facebook"></i>
            <span class="hidden md:inline"> Facebook</span></a
          >
        </li>
        <li>
          <a target="_blank" href="https://github.com/sarunk21"
            ><i class="fab fa-github"></i>
            <span class="hidden md:inline"> Github</span></a
          >
        </li>
        <li>
          <a target="_blank" href="https://www.linkedin.com/in/kautsar-r/"
            ><i class="fab fa-linkedin"></i>
            <span class="hidden md:inline"> LinkedIn</span></a
          >
        </li>
        <li>
          <a
            target="_blank"
            href="https://www.youtube.com/channel/UCdN6WZVN55MYcH-fg0jTxFg"
            ><i class="fab fa-youtube"></i>
            <span class="hidden md:inline"> Youtube</span></a
          >
        </li>
      </ul>
    </div>
  </div>
</template>

<style scoped>
.color-dark {
  color: #211f20;
}

li a {
  @apply text-xl md:text-2xl color-dark;
}
</style>