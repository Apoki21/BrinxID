<template>
  <div class="home">
    <HeaderBrinxid />
    <HeroBrinxid />
    <ProductBrinxid />
    <ModelBrinxid />
    <LogoBrinxid />
    <FooterBrinxid />

  </div>
</template>

<script>
// @ is an alias to /srcs
import HeaderBrinxid from '@/components/HeaderBrinxid.vue'
import HeroBrinxid from '@/components/HeroBrinxid.vue'
import ProductBrinxid from '@/components/ProductBrinxid.vue'
import ModelBrinxid from '@/components/ModelBrinxid.vue'
import LogoBrinxid from '@/components/LogoBrinxid.vue'
import FooterBrinxid from '@/components/FooterBrinxid.vue'

export default {
  name: 'Home',
  components: {
    HeaderBrinxid,
    HeroBrinxid,
    ProductBrinxid,
    ModelBrinxid,
    LogoBrinxid,
    FooterBrinxid,
  }
}
</script>
