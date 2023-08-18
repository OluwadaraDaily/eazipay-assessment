<template>
  <div class="customer-card">
    <h5 class="header-text">{{ headerText }}</h5>
    <p class="text">{{ textL1 }}</p>
    <p class="text">{{ textL2 }}</p>
    <p class="text">{{ textL3 }}</p>
  </div>
</template>

<script>
export default {
  name: 'CustomerCard',
  props: {
    headerText: {
      type: String,
      required: true
    },
    textL1: {
      type: String
    },
    textL2: {
      type: String
    },
    textL3: {
      type: String
    },
  }
}
</script>

<style lang="scss" scoped>
@import './CustomerCard.scss'
</style>