<template>
  <div class="header">
    <div class="header-left">
      <div class="iconfont back-icon">&#xe624;</div>
    </div>
    <div class="header-input">
      <span class="iconfont">&#xe632;</span>
      城市/景点/游玩主题
    </div>
    <div class="header-right">
      {{city}}
      <span class="iconfont arrow-icon">&#xe64a;</span>
    </div>
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
  @import '~styles/varibles'
  .header
    display flex
    height .86rem
    line-height $headerHeight
    background $bgColor
    color #fff
    .header-left
      width .64rem
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
      background #ffffff
      border-radius .1rem
      color #cccccc
    .header-right
      min-width 1.04rem
      padding 0 .1rem
      text-align center
      color #fff
      .arrow-icon
        font-size .24rem
        margin-left -.04rem
</style>
