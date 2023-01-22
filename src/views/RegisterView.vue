<template>
  <div class="home">
    <RegisterPage/>
  </div>
</template>

<script>
// @ is an alias to /src
import RegisterPage from '@/components/RegisterPage.vue'

export default {
  name: 'RegisterView',
  components: {
    RegisterPage
  }
}
</script>
