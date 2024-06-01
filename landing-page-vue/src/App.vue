<template>
  <Header></Header>
  <SectionSatu></SectionSatu>
  <SectionDua></SectionDua>
  <SectionTiga></SectionTiga>
  <SectionEmpat></SectionEmpat>
  <Footer></Footer>
</template>

<script>

import Header from '@/components/Header'
import SectionSatu from '@/components/SectionSatu'
import SectionDua from '@/components/SectionDua.vue'
import SectionTiga from '@/components/SectionTiga.vue'
import SectionEmpat from '@/components/SectionEmpat.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'HomeView',
  components: {
    Header,
    SectionSatu,
    SectionDua,
    SectionTiga,
    SectionEmpat,
    Footer
  }
}
</script>


