<template>
  <section class="team">
    <div class="container">
      <h1>
        Meet  the team
      </h1>
      <div class="team__all">
        <div class="team__item">
          <div class="team__img">
            <img src="@/assets/16.png" alt="">
          </div>
          <div class="team__text">
            <div class="team__name">
              Vicky Russ
            </div>
            <div class="team__position">
              CEO, Founder
            </div>
          </div>
          <div class="team-btn">
            View profile
          </div>
        </div>
        <div class="team__item">
          <div class="team__img">
            <img src="@/assets/17.png" alt="">
          </div>
          <div class="team__text">
            <div class="team__name">
              Vicky Russ
            </div>
            <div class="team__position">
              CEO, Founder
            </div>
          </div>
          <div class="team-btn">
            View profile
          </div>
        </div>
        <div class="team__item">
          <div class="team__img">
            <img src="@/assets/18.png" alt="">
          </div>
          <div class="team__text">
            <div class="team__name">
              Vicky Russ
            </div>
            <div class="team__position">
              CEO, Founder
            </div>
          </div>
          <div class="team-btn">
            View profile
          </div>
        </div>
        <div class="team__item">
          <div class="team__img">
            <img src="@/assets/19.png" alt="">
          </div>
          <div class="team__text">
            <div class="team__name">
              Vicky Russ
            </div>
            <div class="team__position">
              CEO, Founder
            </div>
          </div>
          <div class="team-btn">
            View profile
          </div>
        </div>
        <div class="team__item">
          <div class="team__img">
            <img src="@/assets/20.png" alt="">
          </div>
          <div class="team__text">
            <div class="team__name">
              Vicky Russ
            </div>
            <div class="team__position">
              CEO, Founder
            </div>
          </div>
          <div class="team-btn">
            View profile
          </div>
        </div>
        <div class="team__item">
          <div class="team__img">
            <img src="@/assets/21.png" alt="">
          </div>
          <div class="team__text">
            <div class="team__name">
              Vicky Russ
            </div>
            <div class="team__position">
              CEO, Founder
            </div>
          </div>
          <div class="team-btn">
            View profile
          </div>
        </div>
        <div class="team__item">
          <div class="team__img">
            <img src="@/assets/22.png" alt="">
          </div>
          <div class="team__text">
            <div class="team__name">
              Vicky Russ
            </div>
            <div class="team__position">
              CEO, Founder
            </div>
          </div>
          <div class="team-btn">
            View profile
          </div>
        </div>
        <div class="team__item">
          <div class="team__img">
            <img src="@/assets/23.png" alt="">
          </div>
          <div class="team__text">
            <div class="team__name">
              Vicky Russ
            </div>
            <div class="team__position">
              CEO, Founder
            </div>
          </div>
          <div class="team-btn">
            View profile
          </div>
        </div>
      </div>
      <div class="team-load">
        Load more
      </div>
    </div>
  </section>
</template>
<style lang="sass">
.team
  background: #ffffff
  padding-bottom: 96px
  .container
    flex-direction: column
    max-width: 1130px
    h1
      font-family: Rubik, sans-serif
      font-style: normal
      font-weight: 500
      font-size: 35px
      line-height: 50px
      text-align: center
      color: #0B132A
      margin-bottom: 48px
    .team__all
      display: grid
      grid-template-columns: 1fr 1fr 1fr 1fr
      grid-gap: 30px
      .team__item
        display: flex
        flex-direction: column
        align-items: center
        border-radius: 3px
        padding: 24px
        position: relative
        z-index: 1
        &:before
          content: ''
          width: 100%
          height: 100%
          position: absolute
          top: 0
          left: 0
          background: #FFFFFF
          border-radius: 3px
          z-index: -1
        &:after
          content: ''
          position: absolute
          bottom: -20px
          left: 0
          width: 100%
          height: 104.5%
          opacity: 0.06
          background: #29ABE2
          filter: blur(50px)
          border-radius: 10px
          z-index: -2
        .team__img
          width: 119px
          height: 119px
          overflow: hidden
          border-radius: 50%
          img
            width: 100%
            height: 100%
            object-fit: cover
        .team__text
          display: flex
          align-items: center
          flex-direction: column
          margin: 20px 0 49px 0
          .team__name
            font-family: Rubik, sans-serif
            font-style: italic
            font-weight: bold
            font-size: 22px
            line-height: 26px
            text-align: center
            color: #29ABE2
          .team__position
            font-family: Rubik, sans-serif
            font-style: italic
            font-weight: bold
            font-size: 14px
            line-height: 17px
            text-align: center
            color: #102941
            margin-top: 12px
        .team-btn
          font-family: Rubik, sans-serif
          font-style: normal
          font-weight: 300
          font-size: 14px
          line-height: 17px
          text-align: center
          color: #102941
          cursor: pointer
    .team-load
      font-family: Rubik, sans-serif
      font-style: normal
      font-weight: normal
      font-size: 22px
      line-height: 50px
      text-align: center
      color: #29ABE2
      cursor: pointer
      margin: 32px auto 0 auto









</style>