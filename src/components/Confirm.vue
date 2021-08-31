<template>
  <section class="confirm">
    <div class="container">
      <h1>
        Confirm information
      </h1>
      <h2>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec dolor nisi, posuere vitae tincidunt et, molestie sit amet purus.
      </h2>
      <div class="btn">
        <span>
          Accept
        </span>
        <div class="btn-bg"></div>
      </div>
    </div>
  </section>
</template>
<style lang="sass">
.confirm
  padding-bottom: 122px
  .container
    flex-direction: column
    h1
      font-family: Rubik, sans-serif
      font-style: normal
      font-weight: bold
      font-size: 64px
      line-height: 86px
      color: #29ABE2
    h2
      font-family: Open Sans, sans-serif
      font-style: normal
      font-weight: normal
      font-size: 17px
      line-height: 26px
      color: #102941
      max-width: 525px
      margin: 16px 0 32px 0
    .btn
      cursor: pointer
      display: flex
      position: relative
      margin: 0 auto 58px 0
      span
        background: #29ABE2
        border-radius: 10px
        font-family: Open Sans, sans-serif
        font-style: normal
        font-weight: bold
        font-size: 18px
        cursor: pointer
        line-height: 25px
        color: #FFFFFF
        padding: 17.5px 0
        width: 250px
        text-align: center
        position: relative
        z-index: 2
      .btn-bg
        width: 211px
        pointer-events: none
        height: 100%
        left: 50%
        transform: translateX(-50%)
        position: absolute
        bottom: -25px
        z-index: 1
        background: rgba(95, 122, 126, 0.22)
        filter: blur(54px)
        border-radius: 10px
    .fixed-bg
      z-index: 1
      width: 100%
      height: calc(100% + 8px)
      position: absolute
      left: 0
      top: 0
      background: #0D1025
      opacity: 0.06
      filter: blur(114px)
      border-radius: 10px
</style>