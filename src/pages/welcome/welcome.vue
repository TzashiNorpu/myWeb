<template>
  <section>
    <section class="header"></section>
    <div class="joker"></div>
    <p class="textx">陌上花开 可缓缓归矣</p>
  </section>
</template>

<script>
export default {
  name: 'welcome'
}
</script>
<style lang="stylus" scoped>
.header
  height 7rem
  width 100%
  background url('../../assets/images/guitar.png')
  background-size cover
  background-position center center
.joker
  background url('../../assets/images/joker.png')
  height 2rem
  width 2rem
  background-size cover
  box-shadow 0 0 0 0.06rem white
  border-radius 0.06rem
  margin-left auto
  margin-right  auto
  margin-top -1.5rem
.textx
  text-align center
  margin-top 1rem
  color red
</style>
