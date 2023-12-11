<template>
  <Application />
  <Footer />
</template>

<script>
import Application from '@/components/Application.vue';
import Footer from '@/components/Footer.vue';

export default {
  name: 'ApplicationView',
  components: {
    Application,
    Footer
  }
}
</script>

<style>
/* Add styles for your HomeView here */
</style>