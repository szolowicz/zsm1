<template>
  <div>
    <main-hero />

    <div class="bg-light-bg dark:bg-dark-bg py-8">
      <access-cards />

      <news-grid />
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  beforeCreate() {
    this.$store.commit('setSlide', 0)
  },
})
</script>
