<template lang="pug">
  div
    pm-header
    nuxt
    pm-footer
</template>

<script>
import PmFooter from '@/components/Footer.vue'
import PmHeader from '@/components/Header.vue'

export default {
  components: { PmFooter, PmHeader },
}
</script>
