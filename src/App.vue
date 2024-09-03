<template>
  <Navbar />

  <router-view />

  <medios-pago />
  <Footer />
</template>

<script>
import NavBar from '@/components/NavBar.vue'
import FooTer from '@/components/FooTer.vue'
import MediosPago from '@/components/MediosPago.vue'

export default {
  name: 'HomeView',
  components: {
    NavBar,
    FooTer,
    MediosPago
  }
}
</script>
