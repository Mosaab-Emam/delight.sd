<script setup lang="ts">
const apps = [
  {
    name: 'قصي',
  },
  {
    name: 'سمر',
  },
  {
    name: 'حافظ',
  },
  {
    name: 'عطية',
  },
  {
    name: 'عطاء',
  },
  {
    name: 'محسن',
  },
  {
    name: 'بسمة',
  },
]
</script>

<template>
  <DelightApp v-for="app in apps" :key="app.name" :name="app.name" class="inline-flex" />
  <div inline-flex text-2xl font-300 cursor-default>
    <div flex flex-col children:mx-auto>
      <img w-18 h-18 inline-block src="/nuxt.png">
      <span text-green5 mt--2>Nuxt 3</span>
    </div>
    <div flex flex-col children:mx-auto>
      <img w-18 h-18 inline-block src="/vite.png">
      <span text-purple5 mt--2>Vitesse</span>
    </div>
  </div>
</template>
