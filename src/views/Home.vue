<template>
  <div class="home">
    <HomeSwipe></HomeSwipe>
    <HomeList></HomeList>
  </div>
</template>

<script>
// @ is an alias to /src
import HomeSwipe from '@/components/HomeSwipe.vue'
import HomeList from '@/components/HomeList.vue'

export default {
  name: 'home',
  components: {
    HomeSwipe,
    HomeList
  }
}
</script>


