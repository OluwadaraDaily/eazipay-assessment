<script setup>
import AppButton from "../../components/AppButton/AppButton.vue";
import Intro from '../../components/icons/Intro.vue'
import DownloadCard from "../../components/DownloadCard/DownloadCard.vue";
import CustomerCard from "../../components/CustomerCard/CustomerCard.vue";
</script>

<template>
  <main>
    <section class="intro">
      <div class="intro__div">
        <div class="intro__div-left">
          <div class="intro__div-left__text-section">
            <h2 class="header-text">
              Run your 
              <span class="green">payroll</span>  
               <span class="yellow"> easily</span> 
              in <span class="red">seconds</span>
            </h2>
            <p class="text">
              We’ve built an all-inclusive simple solution for individual and businesses to manage staff, 
              pay salaries, bills, and relevant taxes all at once.
            </p>
            <AppButton text="Start Using Free, Forever" isPrimary/>
          </div>
          <div class="intro__div-left__download-options">
            <h6 class="header-text">Download the Eazipay App</h6>
            <div class="download-cards">
              <DownloadCard iconName="Apple" topText="Download on the" bottomText="Appstore"/>
              <DownloadCard iconName="Google" topText="Get on" bottomText="Google Play"/>
            </div>
          </div>
        </div>
        <div class="intro__div-right">
          <Intro/>
        </div>
      </div>
    </section>
    <section class="customers">
      <div class="customers__header-text-section">
        <h2 class="header-text">For Individuals and Businesses</h2>
        <p class="text">Join 200+ businesses using Eazipay's easy solution.</p>
      </div>
      <div class="customers__cards-section">
        <CustomerCard
          class="card card-1"
          headerText="Tamper-proof Payroll for Life"
          textL1="Your staff payroll history is kept in one place forever."
          textL2="No more excel sheet or manual records."
          textL3="Download your payroll history anytime you need it."
        />
        <CustomerCard
          class="card card-2"
          headerText="All Payroll, Anytime Anywhere"
          textL1="Wherever you are Eazipay has got you covered on ALL your Payroll tasks."
          textL2="Whether it is Taxes, Pension insurances HMOs, trustfunds, Eazipay handle all your compliamces in one place and easily, in seconds!"
        />
        <CustomerCard
          class="card card-3"
          headerText="Payroll in Seconds"
          textL1="Never again wil you spend more than 2 minutes on payroll."
          textL2="Just click on your staff annd bulk-pay them at once."
          textL3="Payment is done permanently."
        />
      </div>
      <div class="customers__contact">
        <p class="text">
          We are happy to answer your queries. Please, reach us at <span class="email-text">hello@myeazipay.com</span> and expect our response shortly after.
        </p>
      </div>
    </section>
    <section class="how-it-works">
      <div class="how-it-works__header-text-section">
        <h2 class="header-text">How Eazipay Works</h2>
        <p class="text">Get started in 3 simple steps.</p>
      </div>
      <div class="how-it-works__picture">
        <img src="../../assets/images/how-it-works.svg" alt="">
        <img src="../../assets//images/green-bg.svg" class="absolute-bg" alt="">
      </div>
    </section>
    <section class="salary-payment">
      <img src="../../assets/images/salary-bg-1.svg" alt="" class="absolute-bg-top">
      <div class="salary-payment__div">
        <div class="salary-payment__div-left">
          <div class="text-section">
            <h2 class="header-text">
              Free forever for your
              <span class="red">salary payment</span>
            </h2>
            <div class="subscribe">
              <h6 class="text">
                Subscribe to the Eazilife today
              </h6>
              <div class="download-cards">
                <DownloadCard iconName="Apple" topText="Download on the" bottomText="Appstore"/>
                <DownloadCard iconName="Google" topText="Get on" bottomText="Google Play"/>
              </div>
            </div>
          </div>
        </div>
        <div class="salary-payment__div-right">
          <img src="../../assets/images/salary-img.svg" alt="">
        </div>
      </div>
    </section>
    <section class="demo">
      <img src="../../assets/images/demo-bg.svg" class="absolute-bg" alt="">
      <img src="../../assets/images/demo-bg-1.svg" class="absolute-bg-left" alt="">
      <div class="demo__div">
        <div class="demo__div-left">
          <h2 class="header-text">Get an Exclusive Demo of Eazipay</h2>
          <p class="text">
            Our greatest priority is to put you and your business first. Let’s show you how we can help.
          </p>
        </div>
        <div class="demo__div-right">
          <img src="../../assets/images/demo-img.svg" alt="" height="650">
        </div>
      </div>
    </section>
  </main>
</template>


<style lang="scss" scoped>
@import './HomeView.scss'
</style>
