<template>
  <div class="grid grid-cols-12 justify-between md:my-14">
    <div class="col-span-12 md:col-span-6 mb-12">
      <div class="mt-6">
        <h1 class="font-semibold color-green text-3xl md:text-5xl mb-4 md:mb-8">
          Selamat Datang
        </h1>
        <span class="color-brown text-2xl md:text-4xl">
          <span id="title"></span> Code
        </span>
      </div>
      <div class="mt-6 md:mt-12">
        <a href="#about" class="btn-about">About Me</a>
        <a href="" class="btn-project ml-6">My Project</a>
      </div>
    </div>
    <div class="col-span-12 md:col-span-6 order-1">
      <img src="@/assets/hero.svg" alt="Hero Image" />
    </div>
  </div>
</template>

<script>
import Typed from "typed.js";

export default {
  mounted() {
    const title = document.getElementById("title");
    let type = new Typed(title, {
      strings: ["Create ^1000", "Read ^1200", "Update ^1400", "Delete ^1600"],
      typeSpeed: 50,
      backSpeed: 50,
      loop: true,
    });
  },
};
</script>

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

.btn-project {
  border-color: #4eb18d;
  color: #4eb18d;
  @apply btn;
}

.btn-project:hover {
  border-color: #67dbb1;
  color: #67dbb1;
}
</style>