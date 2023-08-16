<template>
  <button 
    :type="type"
    @click="onClick"
    :style="isPrimary ? 'background-color: #11453B; color: #ffffff;' : 'background-color: #ffffff;'"
  >{{ text }}</button>
</template>

<script>
export default {
  name: 'AppButton',
  props: {
    text: {
      type: String,
      required: true
    },
    type: {
      type: String,
      default: "button"
    },
    onClick: {
      type: Function,
      default: () => {}
    },
    isPrimary: {
      type: Boolean,
      default: false
    }
  }
}
</script>

<style lang="scss" scoped>
@import './AppButton.scss'
</style>