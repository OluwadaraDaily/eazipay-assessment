<script setup>
import SocialLink from '../SocialLink/SocialLink.vue';
import Logo from '../icons/Logo.vue';
import Send from '../icons/Send.vue'
</script>

<template>
  <footer class="footer">
    <div class="footer__div">
      <div class="footer__div__credits">
        <Logo/>
        <div class="copyright">
          <p class="text">Copyright © 2023 Eazipay.</p>
          <p class="text">All rights reserved</p>
        </div>
        <div class="social-links">
          <SocialLink logoIcon="Instagram"/>
          <SocialLink logoIcon="Twitter"/>
          <SocialLink logoIcon="LinkedIn"/>
          <SocialLink logoIcon="Facebook"/>
        </div>
      </div>
      <div class="footer__div__services">
        <div class="service-list">
          <h5 class="title">Product</h5>
          <ul>
            <li>Individual</li>
            <li>Businesses</li>
            <li>Request Demo</li>
            <li>Pricing</li>
          </ul>
        </div>
        <div class="service-list">
          <h5 class="title">Legal</h5>
          <ul>
            <li>Privacy Policy</li>
            <li>Terms of Service</li>
          </ul>
        </div>
        <div class="service-list">
          <h5 class="title">Resources</h5>
          <ul>
            <li>FAQs</li>
            <li>Blog</li>
            <li>Career</li>
            <li>Customer Stories</li>
          </ul>
        </div>
        <div class="service-list">
          <h5 class="title">Contact Us</h5>
          <ul>
            <li>eazipay@gmail.com</li>
            <li>+234 816 878 9518</li>
            <div class="send-email">
              <input type="email" name="" class="email-input" placeholder="Your email address">
              <Send class="send-btn"/>
            </div>
          </ul>
        </div>
      </div>
    </div>
  </footer>  
</template>


<style lang="scss" scoped>
@import './Footer.scss'
</style>