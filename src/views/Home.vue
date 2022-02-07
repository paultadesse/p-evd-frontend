<template>
  <div class="px-10 ">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <div class="py-7 font-bold text-xl text-gray-500">Dashboard</div>
    <div class="flex space-x-4">
      <div>
        <div class="flex space-x-4">
        <div class="bg-white w-96 py-10 space-y-4 p-4 shadow-xl"> 
        <div class="flex justify-between">
          <div class="text-gray-500 tracking-wider">Customers</div>
          <div class="bg-gray-800 p-3 rounded">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z" />
            </svg>
          </div>
        </div>
        <div class="text-3xl font-bold">
          37,000
        </div>
        <div class="flex space-x-4">
          <span class="flex space-x-2 text-green-500">
            <span>
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7h8m0 0v8m0-8l-8 8-4-4-6 6" />
              </svg>
          </span>
          <span>
            
           7.9 % 
          </span>
          </span>
          <span class="text-gray-400 tracking-wider">
            since last month
          </span>
        </div>
      </div>
      <div class="bg-white w-72 py-10 space-y-4 p-4 shadow-xl"> 
        <div class="flex justify-between">
          <div class="text-gray-500 tracking-wider">Orders</div>
          <div class="bg-gray-800 p-3 rounded">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z" />
            </svg>
          </div>
        </div>
        <div class="text-3xl font-bold">
          5,543
        </div>
        <div class="flex space-x-4">
          <span class="flex space-x-2 text-red-500">
            <span>
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 17h8m0 0V9m0 8l-8-8-4 4-6-6" />
              </svg>
          </span>
          <span>
            
           5.4 % 
          </span>
          </span>
          <span class="text-gray-400 tracking-wider">
            since last month
          </span>
        </div>
      </div>
    </div>
    <!-- another one -->
    <div class="flex space-x-4 mt-4">
        <div class="bg-white w-96 py-10 space-y-4 p-4 shadow-xl"> 
        <div class="flex justify-between">
          <div class="text-gray-500 tracking-wider">Revenue</div>
          <div class="bg-gray-800 p-3 rounded">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z" />
            </svg>
          </div>
        </div>
        <div class="text-3xl font-bold">
          $37,000
        </div>
        <div class="flex space-x-4">
          <span class="flex space-x-2 text-green-500">
            <span>
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7h8m0 0v8m0-8l-8 8-4-4-6 6" />
              </svg>
          </span>
          <span>
            
           7.9 % 
          </span>
          </span>
          <span class="text-gray-400 tracking-wider">
            since last month
          </span>
        </div>
      </div>
      <div class="bg-white w-72 py-10 space-y-4 p-4 shadow-xl"> 
        <div class="flex justify-between">
          <div class="text-gray-500 tracking-wider">Growth</div>
          <div class="bg-gray-800 p-3 rounded">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z" />
            </svg>
          </div>
        </div>
        <div class="text-3xl font-bold">
          + 5,543
        </div>
        <div class="flex space-x-4">
          <span class="flex space-x-2 text-red-500">
            <span>
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 17h8m0 0V9m0 8l-8-8-4 4-6-6" />
              </svg>
          </span>
          <span>
            
           5.4 % 
          </span>
          </span>
          <span class="text-gray-400 tracking-wider">
            since last month
          </span>
        </div>
      </div>
    </div>
      </div>
      <div class="w-full ">
        
        <div class="bg-white py-10 space-y-4 p-4 shadow-xl"> 
        <div class="flex justify-between">
          <div class="text-gray-500 tracking-wider uppercase">Recent Activity</div>
          <div class="bg-gray-800 p-3 rounded">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 11c0 3.517-1.009 6.799-2.753 9.571m-3.44-2.04l.054-.09A13.916 13.916 0 008 11a4 4 0 118 0c0 1.017-.07 2.019-.203 3m-2.118 6.844A21.88 21.88 0 0015.171 17m3.839 1.132c.645-2.266.99-4.659.99-7.132A8 8 0 008 4.07M3 15.364c.64-1.319 1-2.8 1-4.364 0-1.457.39-2.823 1.07-4" />
            </svg>
          </div>
        </div>
        <div class="flex flex-col space-y-5">
          <span class="flex items-center space-x-2"> 
            <div class="flex justify-between w-full px-16">
              <span class="space-x-2 flex"> 
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-green-500" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                </svg>
                <span>
                  You Export Vouchers 
                </span>
              </span>
              <div class="text-gray-400 flex items-center space-x-2">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
                </svg>
              <span>7 sec ago</span> 
            </div>
            </div> 
          </span>
          <hr>
          <span class="flex items-center space-x-2"> 
            <div class="flex justify-between w-full px-16">
              <span class="space-x-2 flex"> 
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-green-500" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                </svg>
                <span>
                  You Export Vouchers 
                </span>
              </span>
              <div class="text-gray-400 flex items-center space-x-2">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
                </svg>
              <span>30 sec ago</span> 
            </div>
            </div> 
          </span>
          <hr>
          <span class="flex items-center space-x-2"> 
            <div class="flex justify-between w-full px-16">
              <span class="space-x-2 flex"> 
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-green-500" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                </svg>
                <span>
                  You Export Vouchers 
                </span>
              </span>
              <div class="text-gray-400 flex items-center space-x-2">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
                </svg>
              <span>47 sec ago</span> 
            </div>
            </div> 
          </span>
          <hr>
          <span class="flex items-center space-x-2"> 
            <div class="flex justify-between w-full px-16">
              <span class="space-x-2 flex"> 
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-green-500" viewBox="0 0 20 20" fill="currentColor">
                    <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                </svg>
                <span>
                  You Export Vouchers 
                </span>
              </span>
              <div class="text-gray-400 flex items-center space-x-2">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
                </svg>
              <span>1 min ago</span> 
            </div>
            </div> 
          </span>
          <hr>
          <span class="flex items-center space-x-2"> 
            <div class="flex justify-between w-full px-16">
              <span class="space-x-2 flex"> 
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-green-500" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
              </svg>
                <span>
                  You Export Vouchers 
                </span>
              </span>
              <div class="text-gray-400 flex items-center space-x-2">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
                </svg>
              <span>5 min ago</span> 
            </div>
            </div> 
          </span>
          <hr>
          
        </div>
      </div>
      </div>
    </div>
    <!-- revenue -->
    <div class="mt-4">
      <div class="bg-white py-10 space-y-4 p-4 shadow-xl"> 
        <div class="flex justify-between">
          <div class="text-gray-500 tracking-wider uppercase">Revenue</div>
          <div class="bg-gray-800 p-3 rounded">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 13v-1m4 1v-3m4 3V8M8 21l4-4 4 4M3 4h18M4 4h16v12a1 1 0 01-1 1H5a1 1 0 01-1-1V4z" />
            </svg>
          </div>
        </div>
        
        <div class="flex justify-around text-center bg-gray-100 max-w-7xl mx-auto py-7">
          <div class="space-y-2">
            <div>Current Week</div>
            <div>12,000</div>
          </div>
          <div class="space-y-2">
            <div>Previous Week</div>
            <div>12,000</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
