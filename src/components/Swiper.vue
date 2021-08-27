<!--
<template>
    <div>
      <swiper>
        <swiper-slide v-for="image in images" :key="image.id">
          <img :src="image.imageUrl" />
        </swiper-slide>
      </swiper>
    </div>
</template>
<script>
// swiper core
import SwiperCore,{Navigation,Parallax} from "swiper";

//swiper vue
import {Swiper, SwiperSlide} from "swiper/vue"

//import swiper css
import "swiper/swiper.scss"

//import css for components
//navigation
import "swiper/components/navigation.scss"


SwiperCore.use([Navigation, Parallax])

export default {
  data() {
    return {
      parallaxSwiperWidth: 0,
      images:[
        {
          id:1,
          imageUrl:require('../assets/01.png'),
        },
        {
          id:2,
          imageUrl:require('../assets/02.png'),
        },
        {
          id:3,
          imageUrl:require('../assets/03.png'),
        },
      ]
    }
  },
  components: {
    Swiper,
    SwiperSlide,
  },
};
</script>
-->
