<template>
  <section class="register">
    <div class="container">
      <div class="register__cont">
        <div class="register-title">
          Registration
        </div>
        <form action="" class="register__form">
          <div class="register__inputs">
            <div class="register__input">
              <label for="email">Email</label>
              <input id="email" type="text" placeholder="Enter your email adress">
            </div>
            <div class="register__input">
              <label for="name">Name</label>
              <input id="name" type="text" placeholder="Darrell ">
            </div>
            <div class="register__input">
              <label for="surname">Surname</label>
              <input id="surname" type="text" placeholder="Steward">
            </div>
            <div class="register__input">
              <label for="password">Password</label>
              <input id="password" type="text" placeholder="Enter your password">
            </div>
            <div class="register__input">
              <label for="confirm-password">Confirm password</label>
              <input id="confirm-password" type="text" placeholder="Confirm your password">
            </div>
          </div>
          <button class="register__btn">
            <span>Create account</span>
            <span class="register__btn-bg"></span>
          </button>
        </form>
      </div>
      <div class="register-bg"></div>
    </div>
  </section>
</template>
<style lang="sass">
.register
  padding: 55px 0 129px 0
  position: relative
  z-index: 2
  .container
    max-width: 584px

    position: relative
    z-index: 2
    .register__cont
      background: #FFFFFF
      border-radius: 24px
      padding: 35px 24px 43px 24px
      display: flex
      flex-direction: column
      width: 100%
      z-index: 2
      position: relative
      .register-title
        font-family: Rubik, sans-serif
        font-style: normal
        font-weight: bold
        font-size: 24px
        line-height: 25px
        color: #102941
        margin-bottom: 24px
        text-align: center
      .register__form
        display: flex
        flex-direction: column
        .register__inputs
          display: flex
          flex-direction: column
          width: 100%
          position: relative
          z-index: 2
          .register__input
            display: flex
            flex-direction: column
            &:not(:last-child)
              margin-bottom: 16px
            label
              font-family: Open Sans, sans-serif
              font-style: normal
              font-weight: normal
              font-size: 17px
              line-height: 26px
              color: #102941
              margin-bottom: 8px
            input
              width: 100%
              border: 1px solid #29ABE2
              box-sizing: border-box
              border-radius: 10px
              font-family: Open Sans, sans-serif
              font-style: normal
              font-weight: normal
              font-size: 17px
              line-height: 26px
              color: #102941
              padding: 17px 26.5px
        .register__btn
          margin: 32px auto 0 auto
          cursor: pointer
          position: relative
          display: flex
          span
            &:first-child
              font-family: Open Sans, sans-serif
              font-style: normal
              font-weight: bold
              font-size: 18px
              line-height: 25px
              text-align: center
              color: #FFFFFF
              background: #29ABE2
              border-radius: 10px
              padding: 17.5px 56.5px
              position: relative
              z-index: 2
          .register__btn-bg
            background: rgba(95, 122, 126, 0.22)
            z-index: 1
            pointer-events: none
            filter: blur(54px)
            border-radius: 10px
            width: 211px
            height: 100%
            position: absolute
            top: 0
            left: 50%
            transform: translate(-50%, 50%)
    .register-bg
      background: #0D1025
      opacity: 0.06
      filter: blur(114px)
      border-radius: 10px
      position: absolute
      z-index: 1
      width: calc(100% + 22px)
      height: calc(100% + 20px)
      top: 7px
      left: 50%
      transform: translateX(-50%)
</style>


















