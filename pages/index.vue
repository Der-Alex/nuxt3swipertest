<template>
  <div>
    <h1>Home</h1>
    <div>
      <swiper :slides-per-view="3" :auto-height="true" :centered-slides="true">
        <swiper-slide>
          <div class="blub">
            <p>1</p>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="blub">
            <p>2</p>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="blub">
            <p>3</p>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="blub">
            <p>4</p>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="blub">
            <p>5</p>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="blub">
            <p>6</p>
          </div>
        </swiper-slide>
      </swiper>
    </div>
  </div>
</template>
<script>
import { Swiper, SwiperSlide } from 'swiper/vue';
import 'swiper/css';

export default {
  components: {
    Swiper,
    SwiperSlide,
  },
};
</script>
<style scoped>
.blub {
  height: 100px;
  background: #999;
}
</style>
