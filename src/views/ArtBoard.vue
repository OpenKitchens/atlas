<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
  <div>
    <header class="flex justify-between py-10 px-12 mx-auto" style="max-width: 1280px;">
      <RouterLink to="/"><img src="/public/image/logo.svg" class="dark:invert"></RouterLink>
      <div class="my-auto">
        <RouterLink to="/about" class="px-4 text-white">概要</RouterLink>
        <RouterLink to="/docs" class="px-4 text-white">ドキュメント</RouterLink>
        <RouterLink to="/artboard" class="px-4 text-white">アートボード</RouterLink>
        <RouterLink to="/diary" class="px-4 text-white">日記</RouterLink>
        <RouterLink to="/alliance" class="px-4 text-white">バナー同盟</RouterLink>
        <RouterLink to="/aboutme" class="px-4 text-white">僕について</RouterLink>
      </div>
    </header>

    <img src="/public/artboard/1.png" class="w-4/5 mx-auto rounded-xl my-5">
    <img src="/public/artboard/2.png" class="w-4/5 mx-auto rounded-xl my-5">
    <img src="/public/artboard/3.png" class="w-4/5 mx-auto rounded-xl my-5">
    <img src="/public/artboard/4.png" class="w-4/5 mx-auto rounded-xl my-5">

    <container class="flex my-10">
      <div class="grid grid-cols-1 mt-5 mx-auto">
        <RouterLink to="/" class="px-4 text-white">ホーム</RouterLink>
        <RouterLink to="/about" class="px-4 text-white">概要</RouterLink>
        <RouterLink to="/docs" class="px-4 text-white">ドキュメント</RouterLink>
        <RouterLink to="/artboard" class="px-4 text-white">アートボード</RouterLink>
        <RouterLink to="/diary" class="px-4 text-white">日記</RouterLink>
        <RouterLink to="/alliance" class="px-4 text-white">バナー同盟</RouterLink>
        <RouterLink to="/aboutme" class="px-4 text-white">僕について</RouterLink>
      </div>

      <img src="/public/image/me.svg" class="mt-5 mx-auto dark:invert">
    </container>
  </div>
</template>

<style scoped></style>