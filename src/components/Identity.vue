<template>
  <section class="identity">
    <div class="container">
      <div class="identity__wrapper">
        <div class="identity__cont">
          <div class="identity__item">
            <div class="identity-title">
              Identity document (ID)
            </div>
            <div class="identity__inputs">
              <div class="identity__input">
                <label for="document-number">
                  Document number
                </label>
                <div class="identity__input-wrapper">
                  <input id="document-number" type="text" placeholder="123-456-789">
                </div>
              </div>
              <div class="identity__input">
                <label for="nationality">
                  Nationality
                </label>
                <div class="identity__input-wrapper">
                  <input id="nationality" type="text" placeholder="Swiss">
                </div>
              </div>
            </div>
            <div class="identity__images">
              <div class="identity__img">
                <img src="@/assets/36.png" alt="">
              </div>
              <div class="identity__img">
                <img src="@/assets/36.png" alt="">
              </div>
            </div>
          </div>
          <div class="identity__item">
            <div class="identity-title">
              Lorem ipsum
            </div>
            <div class="identity__images">
              <div class="identity__img">
                <img src="@/assets/37.png" alt="">
              </div>
              <div class="identity__img">
                <img src="@/assets/37.png" alt="">
              </div>
            </div>
          </div>
        </div>
        <div class="identity-bg"></div>
      </div>
      <div class="identity__btn">
        <span>
          Edit documents
        </span>
        <div class="identity__btn-bg"></div>
      </div>
    </div>
  </section>
</template>
<style lang="sass">
.identity
  .container
    flex-direction: column
    .identity__wrapper
      position: relative
      .identity__cont
        background: #FFFFFF
        border-radius: 24px
        position: relative
        z-index: 2
        padding: 24px
        .identity__item
          display: flex
          flex-direction: column
          &:not(:first-child)
            .identity-title
              margin-top: 48px
          .identity-title
            font-family: Rubik, sans-serif
            font-style: normal
            font-weight: bold
            font-size: 24px
            line-height: 25px
            color: #102941
            margin-bottom: 32px
          .identity__inputs
            width: 100%
            display: grid
            grid-template-columns: 1fr 1fr 1fr
            margin-bottom: 32px
            grid-gap: 67px
            .identity__input
              display: flex
              flex-direction: column
              label
                font-family: Open Sans, sans-serif
                font-style: normal
                font-weight: normal
                font-size: 17px
                line-height: 26px
                color: #102941
                margin-bottom: 8px
              .identity__input-wrapper
                display: flex
                width: 100%
                max-width: 350px
                input
                  width: 100%
                  border: 1px solid #102941
                  border-radius: 10px
                  font-family: Open Sans, sans-serif
                  font-style: normal
                  font-weight: normal
                  font-size: 17px
                  line-height: 26px
                  color: #102941
                  padding: 17px
          .identity__images
            display: flex
            .identity__img
              width: 100%
              max-width: 470px
              max-height: 300px
              &:not(:last-child)
                margin-right: 24px
              img
                width: 100%
                height: 100%
                object-fit: contain
    .identity__btn
      cursor: pointer
      display: flex
      position: relative
      margin: 32px auto 90px 0
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
      .identity__btn-bg
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
    .identity-bg
        background: #0D1025
        opacity: 0.06
        filter: blur(114px)
        border-radius: 10px
        width: 100%
        height: calc(100% + 8px)
        position: absolute
        left: 0
        top: 0
        z-index: 1
</style>