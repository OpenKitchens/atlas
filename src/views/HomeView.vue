<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
  <div class="w-screen h-dvh super-back">
    <div class="background h-4/5">
      <main class="mx-auto px-12" style="max-width: 1280px;">
        <header class="flex justify-between pt-10">
          <RouterLink to="/"><img src="/public/image/logo.svg"></RouterLink>
          <div class="my-auto">
            <RouterLink to="/about" class="px-4">概要</RouterLink>
            <RouterLink to="/docs" class="px-4">ドキュメント</RouterLink>
            <RouterLink to="/artboard" class="px-4">アートボード</RouterLink>
            <RouterLink to="/diary" class="px-4">日記</RouterLink>
            <RouterLink to="/alliance" class="px-4">バナー同盟</RouterLink>
            <RouterLink to="/aboutme" class="px-4">僕について</RouterLink>
          </div>
        </header>

        <div class="text-zinc-950 mincho text-2xl mt-12">
          <p>言の葉の剪定。</p>
          <p>図書館で夢見たニューズグループ</p>
          <p>部屋で俺、思想犯</p>
          <p>部屋で俺、革命犯</p>
          <p>演奏FromJapanでNapster</p>
        </div>

        <RouterLink to="/about" class="mt-12 px-5 py-3 bg-white rounded-md font-black	inline-block">プロトコルの概要
        </RouterLink>

        <div class="mt-7">
          <p class="text-zinc-950 text-xs">興味もったらDMで連絡してね！</p>
          <a class="font-black p-0"
            href="https://www.twitter.com/messages/compose?recipient_id=1619304577899323392">いっしょに作りませんか？></a>
        </div>
      </main>
    </div>

    <container class="flex">
      <div class="grid grid-cols-1 mt-5 mx-auto">
        <RouterLink to="/" class="px-4">ホーム</RouterLink>
        <RouterLink to="/about" class="px-4">概要</RouterLink>
        <RouterLink to="/docs" class="px-4">ドキュメント</RouterLink>
        <RouterLink to="/artboard" class="px-4">アートボード</RouterLink>
        <RouterLink to="/diary" class="px-4">日記</RouterLink>
        <RouterLink to="/alliance" class="px-4">バナー同盟</RouterLink>
        <RouterLink to="/aboutme" class="px-4">僕について</RouterLink>
      </div>

      <img src="/public/image/me.svg" class="mt-5 mx-auto">
    </container>
  </div>
</template>

<style scoped>
.background {
  background-image: url(/public/image/background.png);
  background-repeat: no-repeat;
  background-position: bottom;
  background-size: cover;
  background-color: rgba(255, 255, 255, 0.5);
  background-blend-mode: lighten;
}

.super-back {
  background-color: #fff;
}
</style>