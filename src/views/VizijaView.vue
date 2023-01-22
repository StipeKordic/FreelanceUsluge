<template>
    <div class="vizija">
      <VizijaFrame/>
    </div>
  </template>
  
  <script>
  // @ is an alias to /src
  import VizijaFrame from '@/components/VizijaFrame.vue'
  
  export default {
    name: 'VizijaView',
    components: {
      VizijaFrame
    }
  }
  </script>