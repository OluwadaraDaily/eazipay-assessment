<template>
  <Header/>
  <router-view></router-view>
  <Footer/>
</template>


<script>
import Header from '../../components/Header/Header.vue'
import Footer from '../../components/Footer/Footer.vue';
export default {
  components: {
    Header,
    Footer
  }
}
</script>

<style lang="scss" scoped>
  @import './MainLayout.scss'
</style>