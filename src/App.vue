<template>
  <div class="container px-8 mx-auto">
    <Navbar />
    <Hero />
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Hero from "./components/Hero.vue";

export default {
  components: { Navbar, Hero },
};
</script>

<style>
#app {
  @apply font-poppins;
}
</style>
