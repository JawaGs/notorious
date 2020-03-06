<template>
  <section class="section">
      <Header />
      <Hero />
      <Paises />
      <Footer />
  </section>
</template>

<script>
import Header from '~/components/Header'
import Hero from '~/components/Hero'
import Paises from '~/components/Paises'
import Footer from '~/components/Footer'

export default {
  name: 'HomePage',

  components: {
    Header,
    Hero,
    Paises,
    Footer
  }
}
</script>

