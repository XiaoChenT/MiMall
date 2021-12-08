<!-- home.vue 为主页面 -->
<template>
  <div>
    <nav-header></nav-header>
    <!-- detall.vue index.vue product.vue 分别嵌入到router-view里面去 -->
    <router-view></router-view>
    <nav-footer></nav-footer>
  </div>
</template>
<script>
import NavFooter from '../components/NavFooter.vue';
import NavHeader from '../components/NavHeader.vue';
export default {
  name: "nav-order",
  components: { 
    NavHeader, 
    NavFooter 
    }
};
</script>