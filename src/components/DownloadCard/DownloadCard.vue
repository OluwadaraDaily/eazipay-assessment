<template>
  <div class="download-card">
    <div class="icon-box">
      <component :is=iconName class="icon"/>
    </div>
    <div class="text-box">
      <p class="top-text">{{ topText }}</p>
      <p class="bottom-text">{{ bottomText }}</p>
    </div>
  </div>
</template>

<script>
import Apple from '../icons/Apple.vue';
import Google from '../icons/Google.vue'
export default {
  name: 'DownloadCard',
  components: {
    Apple,
    Google
  },
  props: {
    iconName: {
      type: String,
      required: true
    },
    topText: {
      type: String,
      required: true
    },
    bottomText: {
      type: String,
      required: true
    }
  }
}
</script>

<style lang="scss" scoped>
@import './DownloadCard.scss'
</style>