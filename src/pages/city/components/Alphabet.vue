<template>
  <ul class="list">
    <li class="item">A</li>
    <li class="item">A</li>
    <li class="item">A</li>
    <li class="item">A</li>
    <li class="item">A</li>
  </ul>
</template>

<script>
export default {
  name: 'CityAlphabet'
}
</script>

<style lang="stylus" scoped>
  @import '~styles/varibles'
  .list
    position absolute
    top 1.58rem
    right 0
    bottom 0
    display flex
    flex-direction column
    justify-content center
    width .4rem
    .item
      text-align center
      line-height .44rem
      color $bgColor
</style>
