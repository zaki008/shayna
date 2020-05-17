<template>
<div class="home">
  <Header />
  <HeroShayna />
  <WomanShayna />
  <InstaShayna />
  <PantnerShayna />
  <Footer />
</div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Header from '@/components/Header.vue'
import HeroShayna from '@/components/HeroShayna.vue'
import WomanShayna from '@/components/WomanShayna.vue'
import InstaShayna from '@/components/InstaShayna.vue'
import PantnerShayna from '@/components/PantnerShayna.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'Home',
  components: {
    Header,
    HeroShayna,
    WomanShayna,
    InstaShayna,
    PantnerShayna,
    Footer
  }
}
</script>
