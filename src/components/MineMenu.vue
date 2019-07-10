<template>
  <div class="menu">
      <ul>
        <li><div><img src="../assets/timg.jpg" alt=""></div><p>最近播放</p></li>
        <li><div><img src="../assets/timg.jpg" alt=""></div><p>我的歌单</p></li>
        <li><div><img src="../assets/timg.jpg" alt=""></div><p>下载管理</p></li>
        <li><div><img src="../assets/timg.jpg" alt=""></div><p>我的收藏</p></li>
      </ul>
    
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'


export default {
  name: 'minemenu',
}
</script>

<style scoped>
li{
    list-style: none;
    float: left;
    width: 25%;
    background: #ccc;
    padding: 1rem 0;
}
.menu img{
  width: 55%;

}


</style>


