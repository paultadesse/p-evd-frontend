<template>
  <div id="">
    <div class="flex bg-gray-100">
      <div>
        <SideBar/>
      </div>
      <div class="w-full">
        <NavBar/>
        <router-view/>
      </div>      
    </div>
    <!-- <router-link to="/">Home</router-link> | -->
    <!-- <router-link to="/about">About</router-link> -->
  </div>
</template>
<script >
  import NavBar from '@/components/layouts/NavBar.vue'
  import SideBar from '@/components/layouts/SideBar.vue'
  export default {
    name: 'App',
    components:{
      NavBar,
      SideBar
    }
  }
</script>
<style>

</style>
