<template>
  <section class="video">
    <div class="container">
      <div class="request__nav">
        <div class="request__nav-items">
          <div class="request__nav-item request__nav-item-done">
            <div class="request__nav-number">
              <span>1</span>
              <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M6.6665 16.0002L13.3332 22.6668L26.6665 9.3335" stroke="white" stroke-width="2.66667" stroke-linecap="round" stroke-linejoin="round"/>
              </svg>
            </div>
            <div class="request__nav-text">
              Personal<br>
              information
            </div>
          </div>
          <div class="request__nav-item request__nav-item-done">
            <div class="request__nav-number">
              <span>2</span>
              <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M6.6665 16.0002L13.3332 22.6668L26.6665 9.3335" stroke="white" stroke-width="2.66667" stroke-linecap="round" stroke-linejoin="round"/>
              </svg>
            </div>
            <div class="request__nav-text">
              Interest rate
            </div>
          </div>
          <div class="request__nav-item request__nav-item-done">
            <div class="request__nav-number">
              <span>3</span>
              <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M6.6665 16.0002L13.3332 22.6668L26.6665 9.3335" stroke="white" stroke-width="2.66667" stroke-linecap="round" stroke-linejoin="round"/>
              </svg>
            </div>
            <div class="request__nav-text">
              Documents<br>
              upload
            </div>
          </div>
          <div class="request__nav-item request__nav-item-done">
            <div class="request__nav-number">
              <span>4</span>
              <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M6.6665 16.0002L13.3332 22.6668L26.6665 9.3335" stroke="white" stroke-width="2.66667" stroke-linecap="round" stroke-linejoin="round"/>
              </svg>
            </div>
            <div class="request__nav-text">
              Document<br>
              verification
            </div>
          </div>
          <div class="request__nav-item request__nav-item-active">
            <div class="request__nav-number">
              <span>5</span>
              <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M6.6665 16.0002L13.3332 22.6668L26.6665 9.3335" stroke="white" stroke-width="2.66667" stroke-linecap="round" stroke-linejoin="round"/>
              </svg>
            </div>
            <div class="request__nav-text">
              Video-identification
            </div>
          </div>
          <div class="request__nav-item">
            <div class="request__nav-number">
              <span>6</span>
              <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M6.6665 16.0002L13.3332 22.6668L26.6665 9.3335" stroke="white" stroke-width="2.66667" stroke-linecap="round" stroke-linejoin="round"/>
              </svg>
            </div>
            <div class="request__nav-text">
              Offer
            </div>
          </div>
        </div>
        <div class="request__nav-arrows">
          <div class="request__nav-arrow"></div>
          <div class="request__nav-arrow"></div>
          <div class="request__nav-arrow"></div>
          <div class="request__nav-arrow"></div>
          <div class="request__nav-arrow"></div>
        </div>
      </div>
      <div class="video__text">
        <h1>
          Video-identification
        </h1>
        <h2>
          The validation was successful. Lorem ipsum dolor sit amet, consectetur adipiscing elit. To continue identification on the GetId service, press the start button.
        </h2>
        <div class="btn">
          <span>
            Start
          </span>
          <div class="btn-bg"></div>
        </div>
      </div>
    </div>
  </section>
</template>
<style lang="sass">
.video
  padding: 33px 0 122px 0
  .container
    flex-direction: column
    .request__nav
      width: 100%
      padding: 0 25px
      position: relative
      z-index: 2
      .request__nav-items
        display: flex
        justify-content: space-between
        .request__nav-item
          display: flex
          align-items: center
          position: relative
          &:first-child
            .request__nav-number
              span
                margin-right: 2px
          .request__nav-number
            display: flex
            align-items: center
            justify-content: center
            background: #1D4772
            border-radius: 70px
            width: 48px
            height: 48px
            span
              font-family: Rubik, sans-serif
              font-style: normal
              font-weight: bold
              font-size: 32px
              line-height: 44px
              color: #FFFFFF
            svg
              display: none
          .request__nav-text
            position: absolute
            left: 50%
            transform: translate(-50%, 100%)
            font-family: Open Sans, sans-serif
            font-style: normal
            font-weight: bold
            font-size: 18px
            line-height: 25px
            text-align: center
            color: #102941
            bottom: -7px
        .request__nav-item-active
          .request__nav-number
            background: #29ABE2
        .request__nav-item-done
          .request__nav-number
            background: #18DD8E
            span
              display: none
            svg
              display: block
      .request__nav-arrows
        display: flex
        position: absolute
        width: 100%
        top: 23px
        .request__nav-arrow
          width: 11.869918699%
          height: 2px
          background: #102941
          &:not(:last-child)
            margin-right: 80px
          &:first-child
            margin-left: 64px
            background: #29ABE2
          &:nth-child(2)
            background: #29ABE2
          &:nth-child(3)
            background: #29ABE2
          &:nth-child(4)
            background: #29ABE2
    .video__text
      display: flex
      flex-direction: column
      margin-top: 116px
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
        margin: 16px 0 32px 0
        max-width: 525px
</style>