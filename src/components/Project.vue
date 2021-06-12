<template>
  <div
    class="grid grid-cols-12 mt-20 mb-8 justify-around items-center"
    id="project"
  >
    <h1
      class="
        col-span-12
        text-3xl
        md:text-5xl
        text-center
        font-semibold
        color-green
        mb-10
      "
    >
      My Project
    </h1>
    <div class="col-span-12 md:col-span-6 order-1">
      <img
        src="@/assets/ss-abc.png"
        alt="Art By Code Project"
        class="mx-auto image"
      />
    </div>
    <div
      class="
        col-span-12
        md:col-span-6
        flex flex-col
        items-center
        justify-center
        text-xl
        md:text-3xl
        color-dark
        order-2
      "
    >
      <h1 class="font-semibold mb-2">Art By Code</h1>
      <a href="https://github.com/sarunk21/landing-page-art-by-code"
        ><i class="fab fa-github"></i> Github</a
      >
    </div>
    <div class="col-span-12 md:col-span-6 order-3 md:order-4 mt-8">
      <img
        src="@/assets/ss-items-pwa.png"
        alt="Items PWA Project"
        class="mx-auto image"
      />
    </div>
    <div
      class="
        col-span-12
        md:col-span-6
        flex flex-col
        items-center
        justify-center
        text-xl
        md:text-3xl
        color-dark
        order-4
        md:order-3
      "
    >
      <h1 class="font-semibold mt-2 mb-2">Items PWA</h1>
      <a href="https://github.com/sarunk21/items-pwa"
        ><i class="fab fa-github"></i> Github</a
      >
    </div>
    <div class="flex col-span-12 order-last my-10 justify-end">
      <a
        href="https://github.com/sarunk21"
        target="_blank"
        class="text-2xl ml-auto btn-about"
        >Project Lainnya</a
      >
    </div>
  </div>
</template>

<style scoped>
.btn {
  @apply px-4 py-2 border rounded-lg font-medium duration-200;
}

.btn-about {
  background-color: #4eb18d;
  color: white;
  @apply btn;
}

.btn-about:hover {
  background-color: #67dbb1;
}

@media (min-width: 768px) {
  .image {
    height: 360px;
    width: 720px;
  }
}
</style>