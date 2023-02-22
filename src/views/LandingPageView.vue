<template>
  <HomeLanding/>
  <AboutLanding/>
  <DisplayProducts/>
  <ContactForm/>
  <FooterComponent/>
</template>

<script>
// @ is an alias to /src
import HomeLanding from '@/components/HomeLanding.vue'
import AboutLanding from '@/components/AboutLanding.vue';
import DisplayProducts from '@/components/DisplayProducts.vue'
import ContactForm from '@/components/ContactForm.vue';
import FooterComponent from '@/components/FooterComponent.vue'

export default {
  name: 'LandingPageView',
  components: {
    HomeLanding, AboutLanding, DisplayProducts, ContactForm, FooterComponent
  }
}
</script>

<style>

</style>
