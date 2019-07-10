<template>
  <div class="homerecommend">
      <h2>推荐歌单</h2>
    <ul>
        <li><div><img src="../assets/timg.jpg" alt=""></div><p>上半年度最热新歌TOP50</p></li>
        <li><div><img src="../assets/timg.jpg" alt=""></div><p>耳朵存在的理由，200首必听欧美歌曲</p></li>
        <li><div><img src="../assets/timg.jpg" alt=""></div><p>那些好听到爆了的歌</p></li>
        <li><div><img src="../assets/timg.jpg" alt=""></div><p>耳朵存在的理由，200首必听欧美歌曲</p></li>
    </ul>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'


export default {
  name: 'homeRecommend',
}
</script>

<style scoped>
ul,li{
    margin: 0;padding: 0;
    height: 100%;
    width: 100%;
}
li{
    list-style: none;
    float: left;
    width: 50%;
    background: #ccc;
}

.homerecommend h2{
    text-align: left;
    margin-top: 1.2rem;
    margin-bottom: .5rem;
}
.homerecommend img{
    width: 100%
}
.homerecommend p{
    height: 3rem;
}

</style>


