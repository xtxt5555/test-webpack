<template>
  <div class="hello-world">
    <div class="num">{{num}}</div> 
    <div class="ctrl"><button @click="inc">+</button></div>    
  </div>
</template>

<script>
export default {
  data () {
    return {
      num: 0,
    }
  },
  methods: {
    inc () {
      this.num++
    }
  }

}
</script>

<style lang="stylus">
  @color red
  .num
    color @color
</style>