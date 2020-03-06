<template>
  <section class="section">
      <Header />
      <Hero />
  </section>
</template>

<script>
import Header from '~/components/Header'
import Hero from '~/components/Hero'


export default {
  name: 'HomePage',

  components: {
    Header,
    Hero
  }
}
</script>

