<script setup>
import Header from './components/Header.vue'
import Home from './components/Home.vue'
import Footer from './components/Footer.vue'

</script>

<template>
<div>
  <Header />
    <Home/>
    <Footer/>
  </div>
</template>

<style scoped>
/* header {
  line-height: 1.5;
} */

.logo {
  display: block;
  margin: 0 auto 2rem;
}

/* @media (min-width: px) {
  header {
    display:contents;
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
} */

</style>
