<template>
    <div class="bg-white border border-gray-200 p-6 rounded-lg shadow-sm hover:shadow-md transition text-left">
      <h3 class="text-lg font-bold text-blue-700 mb-2">{{ title }}</h3>
      <p class="text-sm text-gray-700">{{ description }}</p>
    </div>
  </template>
  
  <script setup>
  defineProps({
    title: String,
    description: String
  })
  </script>