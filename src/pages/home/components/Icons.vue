<template>
  <div class="icons">
    <div class="icon">
      <div class="icon-img">
        <img class="icon-img-content" src="http://mp-piao-admincp.qunarzz.com/mp_piao_admin_mp_piao_admin/admin/20209/557ba25df01d7dbf1419b095a11d1319.png" alt="">
      </div>
      <p class="icon-desc">热门景点</p>
    </div>
    <div class="icon">
      <div class="icon-img">
        <img class="icon-img-content" src="http://mp-piao-admincp.qunarzz.com/mp_piao_admin_mp_piao_admin/admin/20209/7c1e26fd490c3b65c2858fe5da96141c.png" alt="">
      </div>
      <p class="icon-desc">滑雪运动</p>
    </div>
    <div class="icon">
      <div class="icon-img">
        <img class="icon-img-content" src="http://mp-piao-admincp.qunarzz.com/mp_piao_admin_mp_piao_admin/admin/20209/a9d33792bd961b1692638d86cf3e6b83.png" alt="">
      </div>
      <p class="icon-desc">万龙滑雪场</p>
    </div>
    <div class="icon">
      <div class="icon-img">
        <img class="icon-img-content" src="http://mp-piao-admincp.qunarzz.com/mp_piao_admin_mp_piao_admin/admin/20209/5ffcd4a916f764f678263b27c1e2e00c.png" alt="">
      </div>
      <p class="icon-desc">天坛公园</p>
    </div>
    <div class="icon">
      <div class="icon-img">
        <img class="icon-img-content" src="http://mp-piao-admincp.qunarzz.com/mp_piao_admin_mp_piao_admin/admin/20209/557ba25df01d7dbf1419b095a11d1319.png" alt="">
      </div>
      <p class="icon-desc">热门景点</p>
    </div>
    <div class="icon">
      <div class="icon-img">
        <img class="icon-img-content" src="http://mp-piao-admincp.qunarzz.com/mp_piao_admin_mp_piao_admin/admin/20209/7c1e26fd490c3b65c2858fe5da96141c.png" alt="">
      </div>
      <p class="icon-desc">滑雪运动</p>
    </div>
    <div class="icon">
      <div class="icon-img">
        <img class="icon-img-content" src="http://mp-piao-admincp.qunarzz.com/mp_piao_admin_mp_piao_admin/admin/20209/a9d33792bd961b1692638d86cf3e6b83.png" alt="">
      </div>
      <p class="icon-desc">万龙滑雪场</p>
    </div>
    <div class="icon">
      <div class="icon-img">
        <img class="icon-img-content" src="http://mp-piao-admincp.qunarzz.com/mp_piao_admin_mp_piao_admin/admin/20209/5ffcd4a916f764f678263b27c1e2e00c.png" alt="">
      </div>
      <p class="icon-desc">天坛公园</p>
    </div>
  </div>
</template>
<script>
export default {
  name: 'HomeIcons'
}
</script>
<style lang="stylus" scoped>
@import "../../../assets/styles/variables.styl"
  .icons
    overflow hidden
    height 0
    padding-bottom 50%
    .icon
      position relative
      float left
      overflow hidden
      height 0
      width 25%
      padding-bottom 25%
      .icon-img
        position absolute
        top 0
        left 0
        right 0
        bottom .44rem
        box-sizing border-box
        padding .1rem
        .icon-img-content
          display block
          margin 0 auto
          height 100%
      .icon-desc
        position absolute
        left 0
        right 0
        bottom 0
        height .44rem
        line-height .44rem
        text-align center
        color $darkTextColor
</style>
