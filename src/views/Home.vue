<template>
  <div class="home">
    <HeaderPasar/>
    <CarouselPasar/>
    <CatalogPasar/>
    <InstaPasar/>
    <PartnerPasar/>
    <FooterPasar/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderPasar from '@/components/HeaderPasar.vue'
import CarouselPasar from '@/components/CarouselPasar.vue'
import CatalogPasar from '@/components/CatalogPasar.vue'
import InstaPasar from '@/components/InstaPasar.vue'
import PartnerPasar from '@/components/PartnerPasar.vue'
import FooterPasar from '@/components/FooterPasar.vue'

export default {
  name: 'Home',
  components: {
    HeaderPasar,
    CarouselPasar,
    CatalogPasar,
    InstaPasar,
    PartnerPasar,
    FooterPasar
  }
}
</script>
