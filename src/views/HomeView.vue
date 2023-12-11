<template>
  <HelloWorld />
  <ValueProp />
  <CTA />
  <Footer />
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue';
import ValueProp from '@/components/ValueProp.vue';
import CTA from '@/components/CTA.vue';
import Footer from '@/components/Footer.vue';

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    ValueProp,
    CTA,
    Footer
  }
}
</script>

<style>
/* Add styles for your HomeView here */
</style>
