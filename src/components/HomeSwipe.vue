<template>
  <div class="home">
    <mt-swipe :auto="3000">
      <mt-swipe-item>
        <img src="../assets/logo1.jpg">
      </mt-swipe-item>
      <mt-swipe-item>
        <img src="../assets/logo2.jpg">
      </mt-swipe-item>
      <mt-swipe-item>
        <img src="../assets/logo3.jpg">
      </mt-swipe-item>
      <mt-swipe-item>
        <img src="../assets/logo4.jpg">
      </mt-swipe-item>
    </mt-swipe>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'


export default {
  name: 'homeSwipe',
}
</script>
<style>
.mint-swipe-items-wrap{
  height: 12rem!important
}
.mint-swipe-item{
  height: 12rem;
}
.mint-swipe-item img{
  width: 100%;
  height: 100%
}
</style>

