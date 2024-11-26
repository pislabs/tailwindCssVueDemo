<script setup lang="ts">
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>
  <div>
    <HelloWorld msg="OK" />

    <div>
      <div class="btn m-2">按钮</div>
      <div class="card m-2">卡片</div>
    </div>
    <div class="p-4 rounded-md m-2 bg-green-100">container mx-auto px-4</div>
    <div class="columns-2 gap-8">
      <div class="w-full bg-slate-100 m-1 break-after-column">xxxx</div>
      <div class="w-full bg-slate-100 m-1">xxxx</div>
      <div class="w-full bg-slate-100 m-1">xxxx</div>
      <div class="w-full bg-slate-100 m-1">xxxx</div>
      <div class="w-full bg-slate-100 m-1">xxxx</div>
      <div class="w-full bg-slate-100 m-1">xxxx</div>
    </div>
  </div>
</template>

<style scoped></style>
