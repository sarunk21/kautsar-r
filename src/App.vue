<template>
  <div class="container px-8 mx-auto">
    <Navbar />
    <Hero />
    <About />
    <Contact />
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Hero from "./components/Hero.vue";
import About from "./components/About.vue";
import Contact from "./components/Contact.vue";

export default {
  components: { Navbar, Hero, About, Contact },
};
</script>

<style>
html {
  scroll-behavior: smooth;
}

#app {
  @apply font-poppins;
}

.color-dark {
  color: #211f20;
}

.color-green {
  color: #4eb18d;
}

.color-brown {
  color: #4b2c2f;
}
</style>
