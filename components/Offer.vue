<template>
  <div class="h-[300px] sm:h-[333px] w-[347px] sm:w-[397px] rounded-lg flex flex-col border ml-0 border-primary cursor-pointer hover:bg-primary-light hover:shadow-xl group shadow-lg px-5 py-10 justify-center items-center gap-5">
    <span class="px-5 py-6 bg-primary-light group-hover:bg-primary rounded-lg">
      <Icon :name="icon" size="30" class="text-primary group-hover:text-white"/>
    </span>
    <h1 class="text-2xl font-semibold text-center">{{ title }}</h1>
    <p class="w-[30ch] text-center">
      {{ description }}
    </p>
    <div class="flex text-right w-full justify-end items-center pr-10 text-primary font-semibold">
      Login
      <Icon name="mdi:arrow-right" size="24" class="h-5 w-5 ml-2 text-primary"/>
    </div>
  </div>
</template>
<script setup lang="ts">
const props = defineProps({
  title: String,
  description: String,
  icon: String
})
</script>