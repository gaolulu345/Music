<template>
  <div class="footer">
      <!-- tabcontainer -->
      <mt-tab-container class="page-tabbar-container" v-model="selected">
        <mt-tab-container-item id="tab1">
         <Home></Home>
        </mt-tab-container-item>
        <mt-tab-container-item id="tab2">
          <mt-cell v-for="n in 5" :title="'订单 ' + n" />
        </mt-tab-container-item>
        <mt-tab-container-item id="tab3">
          <mt-cell v-for="n in 7" :title="'发现 ' + n" />
        </mt-tab-container-item>
        <mt-tab-container-item id="tab4">
          <div class="page-part">
		   <!-- cell -->
            <mt-cell v-for="n in 12" :title="'我的 ' + n" />
          </div>
          <router-link to="/">
		   <!-- button -->
            <mt-button type="danger" size="large">退出</mt-button>
          </router-link>
        </mt-tab-container-item>
      </mt-tab-container>


    <mt-tabbar v-model="selected">
        <mt-tab-item id="tab1">
            <img slot="icon" src="../assets/logo.png">
            tab1
        </mt-tab-item>
        <mt-tab-item id="tab2">
            <img slot="icon" src="../assets/logo.png">
            tab2
        </mt-tab-item>
        <mt-tab-item id="tab3">
            <img slot="icon" src="../assets/logo.png">
            tab3
        </mt-tab-item>
        <mt-tab-item id="tab4">
            <img slot="icon" src="../assets/logo.png">
            我的
        </mt-tab-item>
    </mt-tabbar>
  </div>
</template>

<script>
// @ is an alias to /src
import Home from '@/views/Home.vue'


export default {
  name: 'footer',
  components: {
    Home
  },
data() {
    return {
      selected: 'tab1'
    };
  }

}
</script>
<style>
.mint-tabbar{
  position: fixed!important;
}
</style>

