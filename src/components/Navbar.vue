<template>
  <div class="grid grid-cols-12 justify-between items-center py-4">
    <img
      src="@/assets/logo.png"
      class="rounded-full col-span-6 w-16"
      alt="Logo Sarunk"
    />
    <button class="p-4 ml-auto col-span-6 md:hidden" @click="open = !open">
      <i class="fa fa-bars"></i>
    </button>
    <ul class="link" :class="[{ hidden: !open }, { flex: open }]">
      <li><a href="#about">About</a></li>
      <li><a href="#findMe">Find Me</a></li>
      <li><a href="#project">Project</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {
      open: false,
    };
  },
};
</script>

<style scoped>
li {
  @apply mr-3 md:mr-0 md:ml-6 border-b-0;
}

li:hover {
  border-color: #4eb18d;
  @apply border-b-2;
}

li a {
  color: #4eb18d;
  @apply text-lg font-semibold md:text-xl;
}

.link {
  @apply col-span-12 justify-start items-center mt-5 md:mt-0 md:justify-end md:col-span-6 md:flex;
}
</style>