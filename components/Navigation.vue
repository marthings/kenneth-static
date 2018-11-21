<template>
  <nav class="navigation">
    <logo/>

    <div class="navigation-menu">
      hej
    </div>
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
    @apply bg-black p-8 text-white flex justify-between;
  }
</style>
