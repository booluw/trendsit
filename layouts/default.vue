<template>
  <div>
    <base-header />
    <router-view />
  </div>
</template>

<script>
import BaseHeader from '~/components/BaseHeader.vue'
export default {
  components: { BaseHeader },

}
</script>