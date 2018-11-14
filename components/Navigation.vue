<template>
  <nav class="navigation">
    <logo/>
  </nav>
</template>

<script>

import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
  .navigation {
    @apply bg-black;
  }
</style>
