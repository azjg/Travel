<template>
  <div class="header">
    城市选择
    <router-link tag="div" to="/" class="header-back iconfont">&#xe624;</router-link>
  </div>
</template>

<script>
export default {
  name: 'CityHeader'
}
</script>

<style lang="stylus" scoped>
  @import '~styles/varibles'
  .header
    position relative
    overflow hidden
    height $headerHeight
    line-height $headerHeight
    text-align center
    color #ffffff
    background-color $bgColor
    font-size .32rem
    .header-back
      position absolute
      left 0
      top 0
      width 1.24rem
      font-size .4rem
</style>
