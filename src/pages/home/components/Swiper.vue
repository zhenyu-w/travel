<template>
  <div class="wrapper clearfix">
    <van-swipe class="my-swipe" :autoplay="3000" indicator-color="white">
      <van-swipe-item>
        <img class="swiper-img" src="../../../assets/img/01.jpg" alt="">
      </van-swipe-item>
      <van-swipe-item>
        <img class="swiper-img" src="../../../assets/img/02.jpg" alt="">
      </van-swipe-item>
      <van-swipe-item>
        <img class="swiper-img" src="../../../assets/img/03.jpg" alt="">
      </van-swipe-item>
      <van-swipe-item>
        <img class="swiper-img" src="../../../assets/img/04.jpg" alt="">
      </van-swipe-item>
      <van-swipe-item>
        <img class="swiper-img" src="../../../assets/img/05.jpg" alt="">
      </van-swipe-item>
    </van-swipe>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="stylus" scoped>
  .wrapper
    width: 100%
  .my-swipe
    width: 100%
    height: 0
    padding-bottom 56%
  .my-swipe >>> .swiper-img
    width 100%
  .clearfix:after
    content: "";
    display: block;
    height: 0;
    clear:both;
    visibility: hidden;
</style>