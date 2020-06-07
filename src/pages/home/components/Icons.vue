<template>
  <div>
    <van-grid :border="false">
      <van-grid-item>
        <van-image class="vant-img" src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" />
        <span>景点门票</span>
      </van-grid-item>
      <van-grid-item>
        <van-image class="vant-img" src="http://img1.qunarzz.com/piao/fusion/1804/5a/13ceb38dcf262f02.png" />
        <span>一日游</span>
      </van-grid-item>
      <van-grid-item>
        <van-image class="vant-img" src="http://img1.qunarzz.com/piao/fusion/1803/50/26ffa31b56646402.png" />
        <span>天津海昌</span>
      </van-grid-item>
      <van-grid-item>
        <van-image class="vant-img" src="http://img1.qunarzz.com/piao/fusion/1803/97/02f5043b51b2102.png" />
        <span>梨木台</span>
      </van-grid-item>
      <van-grid-item>
        <van-image class="vant-img" src="http://img1.qunarzz.com/piao/fusion/1803/47/c2b659e048b11602.png" />
        <span>中国马镇</span>
      </van-grid-item>
      <van-grid-item>
        <van-image class="vant-img" src="http://img1.qunarzz.com/piao/fusion/1803/b1/528a9e80403b8c02.png" />
        <span>天津欢乐谷</span>
      </van-grid-item>
      <van-grid-item>
        <van-image class="vant-img" src="http://mp-piao-admincp.qunarzz.com/mp_piao_admin_mp_piao_admin/admin/20191/0334cf5430b9b5505fd79e2b8d7e8670.png" />
        <span>爬长城</span>
      </van-grid-item>
      <van-grid-item>
        <van-image class="vant-img" src="http://img1.qunarzz.com/piao/fusion/1803/b6/37560ece9c62b502.png" />
        <span>张学良故居</span>
      </van-grid-item>
    </van-grid>
    <van-grid clickable :column-num="2">
      <van-grid-item icon="home-o" text="定位失败"/>
      <van-grid-item icon="search" text="必游榜单"/>
    </van-grid>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="stylus" scoped>
  .vant-img
    width: 1.1rem
</style>