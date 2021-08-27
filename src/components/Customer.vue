<template>
  <section class="customer">
    <div class="container">
      <h1>
        Happy Customers
      </h1>
      <h2>
        A happy customer isn’t just someone who makes a purchase with you today. A truly happy customer is one who will be loyal to you and your business for a long time to come.
      </h2>
      <swiper />
    </div>
  </section>
</template>
<style lang="sass">
  .customer
    .container
      flex-direction: column
      h1
        font-family: Rubik, sans-serif
        font-style: normal
        font-weight: bold
        font-size: 32px
        line-height: 44px
        text-align: center
        color: #1D4772
      h2
        font-family: Open Sans, sans-serif
        font-style: normal
        font-weight: normal
        font-size: 17px
        line-height: 26px
        text-align: center
        color: #102941
        margin: 16px auto 64px auto
        max-width: 776px
</style>
<script>
import Swiper from "@/components/Swiper";
export default {
  components: {Swiper}
}
</script>