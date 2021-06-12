<template>
  <div class="container px-8 mx-auto">
    <Navbar />
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";

export default {
  components: { Navbar },
};
</script>

<style>
#app {
  @apply font-poppins;
}
</style>
