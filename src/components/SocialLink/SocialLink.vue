<template>
  <div class="social-link">
    <component :is="logoIcon" class="icon"></component>
  </div>
</template>

<script>
import Facebook from '../icons/Facebook.vue';
import Instagram from '../icons/Instagram.vue';
import LinkedIn from '../icons/LinkedIn.vue';
import Twitter from '../icons/Twitter.vue';
export default {
  name: 'SocialLink',
  components: {
    Facebook,
    Instagram,
    Twitter,
    LinkedIn
  },
  props: {
    logoIcon: {
      type: String,
      required: true
    }
  }
}
</script>

<style lang="scss" scoped>
@import './SocialLink.scss'
</style>