<template>
  <section class="val">
    <div class="container">
      <h1>
        Our values stem from the following four roots:
      </h1>
      <div class="val__all">
        <div class="val__item">
          <div class="val__img">
            <img src="@/assets/24.png" alt="">
          </div>
          <div class="val__text">
            <div class="val-title">
              Convenient online mode
            </div>
            <div class="val-sub">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec dolor nisi, posuere vitae tincidunt et, molestie sit amet purus.
            </div>
          </div>
        </div>
        <div class="val__item">
          <div class="val__img">
            <img src="@/assets/25.png" alt="">
          </div>
          <div class="val__text">
            <div class="val-title">
              Personal approach to the customers
            </div>
            <div class="val-sub">
              Our team lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec dolor nisi, posuere vitae tincidunt et, molestie sit amet purus.
            </div>
          </div>
        </div>
        <div class="val__item">
          <div class="val__img">
            <img src="@/assets/26.png" alt="">
          </div>
          <div class="val__text">
            <div class="val-title">
              Powerfull online protection
            </div>
            <div class="val-sub">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec dolor nisi, posuere vitae tincidunt et, molestie sit amet purus.
            </div>
          </div>
        </div>
        <div class="val__item">
          <div class="val__img">
            <img src="@/assets/27.png" alt="">
          </div>
          <div class="val__text">
            <div class="val-title">
              Completing your financing easily and digitally
            </div>
            <div class="val-sub">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec dolor nisi, posuere vitae tincidunt et, molestie sit amet purus.
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<style lang="sass">
.val
  .container
    flex-direction: column
    padding: 96px 0
    h1
      font-family: Rubik, sans-serif
      font-style: normal
      font-weight: 500
      font-size: 35px
      line-height: 41px
      text-align: center
      color: #102941
      margin-bottom: 75px
    .val__all
      display: flex
      flex-direction: column
      .val__item
        display: flex
        align-items: center
        justify-content: space-between
        &:not(:last-child)
          margin-bottom: 64px
        &:nth-child(2n)
          flex-direction: row-reverse
          .val__text
            margin-left: 80px
            margin-right: 0
        .val__img
          width: 49.2%
          img
            width: 100%
            height: 100%
            object-fit: contain
        .val__text
          width: 42.6%
          margin-right: 80px
          .val-title
            font-family: Rubik, sans-serif
            font-style: normal
            font-weight: bold
            font-size: 22px
            line-height: 28px
            color: #102941
          .val-sub
            font-family: Open Sans, sans-serif
            font-style: normal
            font-weight: normal
            font-size: 17px
            line-height: 26px
            color: #102941
            margin-top: 8px
</style>