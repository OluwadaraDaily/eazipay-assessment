<template>
  <header class="header">
    <div class="header__div">
      <div class="header__div__menu">
        <div class="header__div__menu-logo">
          <Logo/>
        </div>
        <ul class="header__div__menu-links">
          <li><a href="#">Individial</a></li>
          <li><a href="#">Business</a></li>
          <li><a href="#">Pricing</a></li>
          <li><a href="#">Set your payroll</a></li>
        </ul>
      </div>
      <div class="header__div__cta">
        <AppButton text="Log in" />
        <AppButton text="Register" isPrimary />
      </div>
    </div>
  </header>
</template>

<script setup>
import Logo from '../icons/Logo.vue';
import AppButton from '../AppButton/AppButton.vue';
</script>

<style lang="scss" scoped>
  @import './Header.scss'
</style>