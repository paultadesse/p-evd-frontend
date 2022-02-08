<template>
  <div class="px-10 ">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <div class="py-7 font-bold text-xl text-gray-500">Dashboard</div>
    <div class="flex space-x-4">
      <!-- card components -->
      <Cards/>
      <!-- recent activity component -->
      <RecentActivity/>
    </div>
    <!-- revenue -->
    <Revenue/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import Cards from '@/components/dashboard-components/Cards.vue'
import RecentActivity from '@/components/dashboard-components/RecentActivity.vue'
import Revenue from '@/components/dashboard-components/Revenue.vue'

export default {
  name: 'Home',
  components: {
    Cards,
    RecentActivity,
    Revenue,
    HelloWorld
  }
}
</script>
