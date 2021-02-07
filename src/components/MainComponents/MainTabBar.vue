<template>
   <tab-bar>
      <tab-bar-item path="/home" activeColor="cornflowerblue">
        <img slot="item-icon" src="../../assets/img/tabbar/home.svg" alt="" />
        <img slot="item-icon-active" src="../../assets/img/tabbar/home_active.svg" alt="" />
        <div slot="item-text">首页</div>
      </tab-bar-item>
      <tab-bar-item path="/category" activeColor="cornflowerblue">
        <img slot="item-icon" src="../../assets/img/tabbar/category.svg" alt="" />
        <img slot="item-icon-active" src="../../assets/img/tabbar/category_active.svg" alt="" />
        <div slot="item-text">分类</div>
      </tab-bar-item>
      <tab-bar-item path="/cart" activeColor="cornflowerblue">
        <img slot="item-icon" src="../../assets/img/tabbar/shoppingcart.svg" alt="" />
        <img slot="item-icon-active" src="../../assets/img/tabbar/shoppingcart_active.svg" alt="" />
        <div slot="item-text">购物车</div>
      </tab-bar-item>
      <tab-bar-item path="/profile" activeColor="cornflowerblue">
        <img slot="item-icon" src="../../assets/img/tabbar/profiler.svg" alt="" />
        <img slot="item-icon-active" src="../../assets/img/tabbar/profiler_actie.svg" alt="" />
        <div slot="item-text">我的</div>
      </tab-bar-item>
   </tab-bar>
</template>

<script>
import TabBar from '../tabbar/TabBar.vue'
import TabBarItem from '../tabbar/TabBarItem.vue'

export default {
   name: "MainTabBar",
   components: { 
      TabBar, 
      TabBarItem 
   }
}
</script>

<style>

</style>