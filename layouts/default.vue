<template>
  <div>
    <base-header />
    <router-view />
    <div id="about-us"></div>
    <base-footer />
  </div>
</template>

<script>
import BaseFooter from '~/components/BaseFooter.vue'
import BaseHeader from '~/components/BaseHeader.vue'
export default {
  components: { BaseHeader, BaseFooter },

}
</script>