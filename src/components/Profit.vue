<template>
  <section class="profit">
    <div class="container">
      <div class="profit__text">
        <h1>
          Purpose Beyond Profit
        </h1>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec dolor nisi, posuere vitae tincidunt et, molestie sit amet purus. Doloremque et molestiae perspiciatis quis voluptas ut sed. Omnis praesentium doloremque ipsa eveniet.
        </p>
        <div class="profit__btn">
          <span>
            Mortgage estimate
          </span>
          <div class="profit__btn-bg"></div>
        </div>
      </div>
      <div class="profit__img">
        <img src="@/assets/04.png" alt="">
      </div>
    </div>
  </section>
</template>
<style lang="sass">
.profit
  background: #fbfbfb
  padding-bottom: 96px
  .container
    justify-content: space-between
    align-items: center
    .profit__text
      display: flex
      flex-direction: column
      width: 42.6%
      h1
        font-family: Rubik, sans-serif
        font-style: normal
        font-weight: bold
        font-size: 32px
        line-height: 44px
        color: #1D4772
      p
        font-family: Open Sans, sans-serif
        font-style: normal
        font-weight: normal
        font-size: 17px
        line-height: 26px
        color: #102941
        margin: 16px 0 24px
      .profit__btn
        margin-right: auto
        cursor: pointer
        display: flex
        position: relative
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
          padding: 17.5px 40px
          position: relative
          z-index: 2
        .profit__btn-bg
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
    .profit__img
      width: 43.8%
      img
        width: 100%
        height: 100%
        object-fit: contain
</style>












