<template>
  <div class="header">
    <div class="header-left">
      <div class="iconfont back-icon">&#xe682;</div>
    </div>
    <div class="header-input">
      <span class="iconfont">&#xe63f;</span>
      输入城市景点游玩主题
    </div>
    <router-link to="/city">
      <div class="header-right">{{this.city}}</div>
    </router-link>
    <div class="iconfont arrow-icon">&#xe6a2;</div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeader',
  props: {
    city: String
  }
}
</script>

<style lang="stylus" scoped>
@import "../../../assets/styles/variables.styl"
  .header
    display flex
    line-height $headerHeight
    background $bgColor
    color #fff
    .header-left
      width .64rem
      float left
      .back-icon
        text-align center
        font-size .4rem
    .header-input
      flex 1
      height .64rem
      line-height .64rem
      margin-top .12rem
      margin-left .2rem
      padding-left .2rem
      background #fff
      border-radius .1rem
      color #ccc
    .header-right
      width 1.24rem
      float left
      text-align center
      color #ffffff
      .arrow-icon
        font-size .24rem
</style>
