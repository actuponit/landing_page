<template>
  <div class="flex relative md:hidden items-center py-6 justify-between w-full bg-primary-light">
    <img src="/bridges-logo.b99221d2.svg" alt="logo" class="h-10">
    <div @click="clicked = !clicked">
      <Icon name="mdi:menu" size="30" class="px-5"/>
    </div>
  </div>
  <div v-if="clicked" class="bg-[#fddfb2] w-full py-3">
    <div class="flex flex-col gap-5 text-lg">
      <a href="#home" class="hover:bg-primary/70 w-full p-2">Home</a>
      <a href="#about" class="hover:bg-primary/70 w-full p-2">About</a>
      <a href="#partners" class="hover:bg-primary/70 w-full p-2">Partners</a>
      <a href="#services" class="hover:bg-primary/70 w-full p-2">Services</a>
      <a href="#" class="flex bg-primary px-14 py-4 ml-5 rounded-full text-sm w-3/4 font-semibold text-white border-0">
        <Icon name="mdi:lock-open" size="20" class="w-5 mr-3 text-white"/>
        Login Management
      </a>
    </div>
  </div>
</template>
<script setup>
const clicked = ref(false)
</script>