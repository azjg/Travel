<template>
  <ul class="list">
    <li class="item" v-for="(val, key) of cities" :key="key">{{key}}</li>
  </ul>
</template>

<script>
export default {
  name: 'CityAlphabet',
  props: {
    cities: Object
  }
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
