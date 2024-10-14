<script setup>
import About from "./components/About.vue";
import Footer from "./components/Ui/Footer.vue";
import Header from "./components/Ui/Header.vue";

const isiPesan = "Kanjut";
</script>

<template>
  <main>
    <section class="min-h-svh">
      <h1>Hello World</h1>
    </section>
  </main>
  <footer>
    <Footer />
  </footer>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
