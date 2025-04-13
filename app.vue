<template>
  <div class="flex items-center bg-white dark:bg-gray-900 w-full h-svh overflow-hidden">

    <div class="mx-auto w-full max-w-md h-full overflow-auto">

      <!-- Centered page with backgorund image -->
      <div class="flex flex-col items-center gap-5 bg-cover bg-center bg-fixed p-5"
        style="background-image: url('/img/background.png');">

        <!-- card R5 -->
        <div class="flex flex-col gap-3 bg-white/80 dark:bg-gray-800/80 shadow-md p-6 rounded-3xl w-full max-w-sm">

          <h1 class="font-black text-primary dark:text-white text-6xl text-center">OUR R5</h1>
          <img src="/img/Unclee Bear.png" alt="">
          <h1 class="font-black text-primary dark:text-white text-6xl text-center">Unclee Bear</h1>

        </div>


        <!-- card r4 -->
        <div class="flex flex-col gap-3 bg-white/80 dark:bg-gray-800/80 shadow-md p-6 rounded-3xl w-full max-w-sm">
          <h1 class="font-black text-primary dark:text-white text-6xl text-center">OUR R4</h1>

          <div class="w-full">

            <swiper-container :slides-per-view="1" :autoplay="true" :free-mode="true" :loop="true" css-mode="true">

              <swiper-slide>
                <img src="/img/zzeeeeeeeeee.png" alt="">
                <h1 class="font-black text-primary dark:text-white text-6xl text-center">zzeeeeeeeeee</h1>
              </swiper-slide>
              <swiper-slide>
                <img src="/img/nuya.png" alt="">
                <h1 class="font-black text-primary dark:text-white text-6xl text-center">nuya</h1>
              </swiper-slide>
              <swiper-slide>
                <img src="/img/Kin.png" alt="">
                <h1 class="font-black text-primary dark:text-white text-6xl text-center">Kin</h1>
              </swiper-slide>
              <swiper-slide>
                <img src="/img/Cosmic.png" alt="">
                <h1 class="font-black text-primary dark:text-white text-6xl text-center">Cosmic</h1>
              </swiper-slide>
              <swiper-slide>
                <img src="/img/FHA.png" alt="">
                <h1 class="font-black text-primary dark:text-white text-6xl text-center">FHA | Rider</h1>
              </swiper-slide>
              <swiper-slide>
                <img src="/img/PapaaKilo.png" alt="">
                <h1 class="font-black text-primary dark:text-white text-6xl text-center">PapaaKilo</h1>
              </swiper-slide>
              <swiper-slide>
                <img src="/img/sappi kerre.png" alt="">
                <h1 class="font-black text-primary dark:text-white text-6xl text-center">sappi kerre</h1>
              </swiper-slide>

            </swiper-container>

          </div>

        </div>


        <!-- Jokes Section -->

        <!-- Jokes Section -->
        <div class="flex flex-col gap-3 bg-white/80 dark:bg-gray-800/80 shadow-md p-6 rounded-3xl w-full max-w-sm">
          <div class="flex flex-col gap-4">
            <div class="bg-gray-100 dark:bg-gray-700 shadow p-4 rounded-lg">
              <p class="text-gray-800 dark:text-gray-200 text-lg">
                Why don't skeletons fight each other?
              </p>
              <p class="mt-2 text-gray-600 dark:text-gray-400 text-sm">
                They don't have the guts.
              </p>
            </div>
            <div class="bg-gray-100 dark:bg-gray-700 shadow p-4 rounded-lg">
              <p class="text-gray-800 dark:text-gray-200 text-lg">
                Why did the scarecrow win an award?
              </p>
              <p class="mt-2 text-gray-600 dark:text-gray-400 text-sm">
                Because he was outstanding in his field.
              </p>
            </div>
            <div class="bg-gray-100 dark:bg-gray-700 shadow p-4 rounded-lg">
              <p class="text-gray-800 dark:text-gray-200 text-lg">
                What do you call fake spaghetti?
              </p>
              <p class="mt-2 text-gray-600 dark:text-gray-400 text-sm">
                An impasta.
              </p>
            </div>
          </div>

          <div class="flex flex-col gap-4">
            <h1 class="font-black text-primary dark:text-white text-4xl text-center">
              Made by Love for K1N5 
            </h1>
          </div>
        </div>

        <!-- card -->
        <div class="flex flex-col gap-3 bg-white/80 dark:bg-gray-800/80 shadow-md p-6 rounded-3xl w-full max-w-sm">
          <h2 class="font-bold text-primary dark:text-white text-4xl text-center">WhoIsJul</h2>
            <p class="text-gray-800 dark:text-gray-200 text-lg text-center">
              Hi, I'm Julian, a passionate developer and tech enthusiast. I love building amazing things and sharing
              knowledge with the community.
            </p>
            <div class="flex flex-col gap-2 mt-4 text-center">
              <a href="https://www.instagram.com/deanabnerjul" target="_blank"
              class="text-gray-800 hover:text-primary dark:hover:text-primary dark:text-gray-200 transition">
              Instagram: @deanabnerjul
              </a>
              <a href="https://twitter.com/deanabnerjul" target="_blank"
              class="text-gray-800 hover:text-primary dark:hover:text-primary dark:text-gray-200 transition">
              Twitter: @deanabnerjul
              </a>
              <a href="https://www.linkedin.com/in/deanabner/" target="_blank"
              class="text-gray-800 hover:text-primary dark:hover:text-primary dark:text-gray-200 transition">
              LinkedIn: Dean Abner
              </a>
              <a href="https://deanabnerjul.com" target="_blank"
              class="text-gray-800 hover:text-primary dark:hover:text-primary dark:text-gray-200 transition">
              Website: deanabnerjul.com
              </a>
            </div>
        </div>


      </div>

    </div>

  </div>
</template>

<script setup>

import { register } from 'swiper/element/bundle';
import { onMounted } from 'vue';

onMounted(() => {
  register();
});

</script>
