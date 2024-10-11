<template>
  <div class="flex-1 rounded-md shadow-sm px-5 py-10 border border-gray-100 hover:shadow-md duration-300">
    <div class="flex flex-col md:flex-row gap-x-7 items-start">
      <div class="self-center md:self-start w-20 mb-10 md:w-80">
        <img :src="image" alt="logo" class="h-10">
      </div>
      <div>
        <h1 class="font-semibold text-gray-1 text-xl mb-7">{{ title }}</h1>
        <p class="text-sm">{{ description }}</p>
      </div>
    </div>
  </div>
</template>

<script setup>
const props = defineProps({
  title: String,
  description: String,
  image: String
})
</script>