<template>
  <div class="homelist">
    <ul>
        <li><div><img src="" alt=""></div>随心FM</li>
        <li><div><img src="" alt=""></div>分区</li>
        <li><div><img src="" alt=""></div>排行榜</li>
        <li><div><img src="" alt=""></div>活动</li>
    </ul>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'


export default {
  name: 'homeList',
}
</script>

<style scoped>
.homelist{
    height: 6rem;
    margin-top: 1rem;
}
ul,li{
    margin: 0;padding: 0;
    height: 100%;
    width: 100%;
}
.homelist li{
    list-style: none;
    width: 25%;
    float: left;
    background: #ccc
}
/* .homelist div{
    display: inline-block;
    width: 100%;
} */
.homelist img{
    height: 100%;
    width: 100%;
    background: red
}
</style>


