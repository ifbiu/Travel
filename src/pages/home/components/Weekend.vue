<template>
  <div>
    <div class="title">周末去哪儿</div>
    <ul>
      <li class="item border-bottom" v-for="(item,index) in recommendList" :key="index">
        <div class="item-img-wrapper">
          <img :src="item.imgUrl" alt="" class="item-img">
        </div>
        <div class="item-info">
          <p class="item-title">{{item.title}}</p>
          <p class="item-desc">{{item.desc}}</p>
        </div>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HomeWeekend',
  data () {
    return {
      recommendList: [
        {
          id: '0001',
          imgUrl: 'http://img1.qunarzz.com/sight/p0/1511/d2/d2aec2dfc5aa771290.water.jpg_200x200_69e4a80d.jpg',
          title: '南山滑雪场',
          desc: '北京南山滑雪场--日场全天含雪具'
        },
        {
          id: '0001',
          imgUrl: 'http://img1.qunarzz.com/sight/p0/1511/d2/d2aec2dfc5aa771290.water.jpg_200x200_69e4a80d.jpg',
          title: '南山滑雪场',
          desc: '北京南山滑雪场--日场全天含雪具'
        },
        {
          id: '0001',
          imgUrl: 'http://img1.qunarzz.com/sight/p0/1511/d2/d2aec2dfc5aa771290.water.jpg_200x200_69e4a80d.jpg',
          title: '南山滑雪场',
          desc: '北京南山滑雪场--日场全天含雪具'
        },
        {
          id: '0001',
          imgUrl: 'http://img1.qunarzz.com/sight/p0/1511/d2/d2aec2dfc5aa771290.water.jpg_200x200_69e4a80d.jpg',
          title: '南山滑雪场',
          desc: '北京南山滑雪场--日场全天含雪具'
        },
        {
          id: '0001',
          imgUrl: 'http://img1.qunarzz.com/sight/p0/1511/d2/d2aec2dfc5aa771290.water.jpg_200x200_69e4a80d.jpg',
          title: '南山滑雪场',
          desc: '北京南山滑雪场--日场全天含雪具'
        }
      ]
    }
  }
}
</script>

<style lang="stylus" scoped>
@import "../../../assets/styles/mixins.styl"
.title
  margin-top .2rem
  line-height .8rem
  background #eee
  text-indent .2rem
.item-img-wrapper
  overflow hidden
  height 0
  padding-bottom 33.9%
  .item-img
    width 100%
.item-info
  padding .1rem
  .item-title
    line-height .54rem
    font-size .32rem
    ellipsis()
  .item-desc
    line-height .4rem
    color #ccc
    ellipsis()

</style>
