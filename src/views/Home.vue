<template>
  <div class="home">
    <HomeSwipe></HomeSwipe>
    <HomeList></HomeList>
    <HomeRecommend></HomeRecommend>
  </div>
</template>

<script>
// @ is an alias to /src
import HomeSwipe from '@/components/HomeSwipe.vue'
import HomeList from '@/components/HomeList.vue'
import HomeRecommend from '@/components/HomeRecommend'

export default {
  name: 'home',
  components: {
    HomeSwipe,
    HomeList,
    HomeRecommend
  }
}
</script>


