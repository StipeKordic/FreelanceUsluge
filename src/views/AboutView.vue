<template>
  <div class="home">
    <AboutUs/>
  </div>
</template>

<script>
// @ is an alias to /src
import AboutUs from '@/components/AboutUs.vue'

export default {
  name: 'AboutView',
  components: {
    AboutUs
  }
}
</script>
