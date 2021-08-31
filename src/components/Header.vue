<template>
  <header class="header">
    <div class="container">
      <router-link to="/home" class="header__logo">
        <img src="@/assets/01.png" alt="">
      </router-link>
      <div class="header__menu">
        <router-link active-class="active" to="/home" class="header-link">
          Homepage
        </router-link>
        <router-link active-class="active" to="/mortgage" class="header-link">
          Mortgages in Switzerland
        </router-link>
        <router-link active-class="active" to="/calculator" class="header-link">
          Mortgage calculator
        </router-link>
        <router-link active-class="active" to="/about" class="header-link">
          About us
        </router-link>
        <router-link active-class="active" to="/faq" class="header-link">
          FAQ
        </router-link>
      </div>
      <div class="header__buttons">
        <router-link to="/register" class="header__button">
          <span>
            Sign Up
          </span>
          <div class="header__button-bg"></div>
        </router-link>
        <router-link to="/login" class="header__button">
          <span>
            Log in
          </span>
          <div class="header__button-bg"></div>
        </router-link>
      </div>
    </div>
  </header>
</template>

<style lang="sass">
  .header
    background: #FFFFFF
    position: relative
    z-index: 5
    .container
      align-items: center
      justify-content: space-between
      padding: 39px 0
      .header__menu
        .header-link
          font-family: Open Sans, sans-serif
          font-style: normal
          font-weight: normal
          font-size: 17px
          line-height: 26px
          color: #102941
          &:not(:last-child)
            margin-right: 24px
        .active
          color: #29ABE2
          position: relative
          &:after
            content: ''
            position: absolute
            left: 0
            bottom: -6.5px
            width: 100%
            height: 4px
            background: #8CC5F9
    .header__buttons
      display: flex
      .header__button
        display: flex
        position: relative
        &:not(:last-child)
          margin-right: 32px
        span
          background: #29ABE2
          border-radius: 10px
          cursor: pointer
          font-family: Open Sans, sans-serif
          font-style: normal
          font-weight: bold
          font-size: 18px
          line-height: 25px
          color: #FFFFFF
          padding: 20px 0
          width: 134px
          text-align: center
          position: relative
          z-index: 2
        .header__button-bg
          width: 94px
          pointer-events: none
          height: 47px
          left: 50%
          transform: translateX(-50%)
          position: absolute
          bottom: -3px
          z-index: 1
          background: rgba(95, 122, 126, 0.22)
          filter: blur(54px)
          border-radius: 10px
</style>












