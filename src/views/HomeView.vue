<template>
  <HelloWorld />
  <ValueProp />
  <Application />
  <Footer />
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue';
import ValueProp from '@/components/ValueProp.vue';
import CTA from '@/components/CTA.vue';
import Application from '@/components/Application.vue';
import Footer from '@/components/Footer.vue';

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    ValueProp,
    CTA,
    Application,
    Footer
  }
}
</script>

<style>
/* Add styles for your HomeView here */
</style>
