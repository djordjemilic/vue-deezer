<script setup>
// import { RouterView } from 'vue-router'
import Magnify from 'vue-material-design-icons/Magnify.vue'
import Bell from 'vue-material-design-icons/Bell.vue'
</script>

<template>
  <div
    id="TopNav"
    class="fixed right-0 flex items-center justify-between w-[calc(100%-240px)] h-[56px] border-b border-b-[#32323D]"
  >
    <div class="flex items-center w-full h-full">
      <Magnify class="pl-6" fillColor="#7E7E88" :size="22" />
      <input
        class="p-3 bg-transparent outline-none font-[300] placeholder-[#BEBEC7] text-white w-full max-w-xl"
        placeholder="Search"
        type="text"
      />
    </div>
    <div class="flex items-center pr-10">
      <div class="mr-4 p-1 hover:bg-gray-600 rounded-full cursor-pointer">
        <Bell fillColor="#FFFFFF" :size="20" />
      </div>
      <img class="rounded-full w-[33px]" src="./assets/profile.jpg" alt="Image of a person" />
    </div>
  </div>
  <!-- <RouterView /> -->
</template>
