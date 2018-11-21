<template>
  <div>
    <navigation/>
    <nuxt/>
  </div>
</template>

<script>

import Navigation from '~/components/Navigation.vue'

export default {
  components: {
    Navigation
  }
}

</script>

<style>

  .container {
    @apply max-w-2xl mx-auto;
  }

  .button {
    @apply px-4 py-3 bg-black inline-block text-white;
  }
  
</style>
