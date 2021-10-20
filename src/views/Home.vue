<template>
  <div class="home">
    <Header />
    <Hero />
    <Subhero />
    <InstaPhotos />
    <PartnerLogos />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue'
import Hero from '@/components/Hero.vue'
import Subhero from '@/components/Subhero.vue'
import InstaPhotos from '@/components/InstaPhotos.vue'
import PartnerLogos from '@/components/PartnerLogos.vue'
import Footer from '@/components/Footer.vue'


export default {
  name: 'Home',
  components: {
    Header,
    Hero,
    Subhero,
    InstaPhotos,
    PartnerLogos,
    Footer
  }
}
</script>
