<template>
  <div class="max-w-2xl mx-auto">
    <div class="p-4 md:p-10">
      <div class="p-6 border border-gray-300 shadow rounded-lg">
        <div class="space-y-6">
          <div class="flex gap-6">
            <img
              :src="ProfileImg"
              alt="Profile Image"
              class="rounded-full w-24 h-24"
            />
            <div class="flex flex-col justify-center">
              <h4 class="text-xl font-bold">Sodara Sou</h4>
              <p>sodarasou168@gmail.com</p>
            </div>
          </div>
          <p>
            Hi 👋, I'm Dara. I'm currently a fourth-year ITE student at RUPP and
            a very passionate developer.
          </p>
          <div class="flex flex-wrap gap-2">
            <a href="https://web.facebook.com/SodaraSou" target="_blank"
              ><div
                class="flex items-center gap-2 p-2 border border-gray-300 shadow rounded-lg font-medium"
              >
                <img :src="Facebook" alt="facebook" class="w-5 h-5" />
                <p class="font-medium">Facebook</p>
              </div></a
            >
            <a href="https://t.me/SodaraSou" target="_blank"
              ><div
                class="flex items-center gap-2 p-2 border border-gray-300 shadow rounded-lg font-medium"
              >
                <img :src="Telegram" alt="telegram" class="w-5 h-5" />
                <p class="font-medium">Telegram</p>
              </div></a
            >
            <a href="https://github.com/SodaraSou" target="_blank"
              ><div
                class="flex items-center gap-2 p-2 border border-gray-300 shadow rounded-lg font-medium"
              >
                <img :src="Github" alt="github" class="w-5 h-5" />
                <p class="font-medium">Github</p>
              </div></a
            >
          </div>

          <p>
            As a developer it is very important that I have to learn and explore
            different languages and technologies, not just stick to what I'm
            comfortable with. So these are the technologies and languages I have
            experience with:
          </p>
          <div class="flex flex-wrap gap-2">
            <div
              class="flex items-center gap-2 p-2 border border-gray-300 shadow rounded-lg"
            >
              <img :src="Next" alt="nextjs" class="w-5 h-5" />
              <p class="font-medium">Nextjs</p>
            </div>
            <div
              class="flex items-center gap-2 p-2 border border-gray-300 shadow rounded-lg"
            >
              <img :src="Nuxt" alt="nuxtjs" class="w-6 h-6" />
              <p class="font-medium">Nuxtjs</p>
            </div>
            <div
              class="flex items-center gap-2 p-2 border border-gray-300 shadow rounded-lg"
            >
              <img :src="React" alt="react" class="w-6 h-6" />
              <p class="font-medium">React</p>
            </div>
            <div
              class="flex items-center gap-2 p-2 border border-gray-300 shadow rounded-lg"
            >
              <img :src="Vue" alt="vue" class="w-6 h-6" />
              <p class="font-medium">Vue</p>
            </div>
            <div
              class="flex items-center gap-2 p-2 border border-gray-300 shadow rounded-lg"
            >
              <img :src="Laravel" alt="laravel" class="w-5 h-5" />
              <p class="font-medium">Laravel</p>
            </div>
            <div
              class="flex items-center gap-2 p-2 border border-gray-300 shadow rounded-lg"
            >
              <img :src="Expo" alt="expo" class="w-5 h-5" />
              <p class="font-medium">Expo</p>
            </div>
            <div
              class="flex items-center gap-2 p-2 border border-gray-300 shadow rounded-lg"
            >
              <img :src="Tailwind" alt="tailwind" class="w-6 h-6" />
              <p class="font-medium">Tailwind</p>
            </div>
            <div
              class="flex items-center gap-2 p-2 border border-gray-300 shadow rounded-lg"
            >
              <img :src="Postgresql" alt="postgresql" class="w-5 h-5" />
              <p class="font-medium">PostgreSQL</p>
            </div>
            <div
              class="flex items-center gap-2 p-2 border border-gray-300 shadow rounded-lg"
            >
              <img :src="Firebase" alt="firebase" class="w-5 h-5" />
              <p class="font-medium">Firebase</p>
            </div>
            <div
              class="flex items-center gap-2 p-2 border border-gray-300 shadow rounded-lg"
            >
              <img :src="Docker" alt="docker" class="w-5 h-5" />
              <p class="font-medium">Docker</p>
            </div>
            <div
              class="flex items-center gap-2 p-2 border border-gray-300 shadow rounded-lg"
            >
              <img :src="Github" alt="github" class="w-5 h-5" />
              <p class="font-medium">Github</p>
            </div>
          </div>
          <div class="flex border-gray-300">
            <p class="ml-auto text-gray-400">Sodara Sou © 2025</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
import ProfileImg from "@/assets/images/sodara-sou.jpg";
import Next from "@/assets/svg/nextjs.svg";
import Nuxt from "@/assets/svg/nuxtjs.svg";
import React from "@/assets/svg/react.svg";
import Vue from "@/assets/svg/vue.svg";
import Laravel from "@/assets/svg/laravel.svg";
import Expo from "@/assets/svg/expo.svg";
import Github from "@/assets/svg/github.svg";
import Postgresql from "@/assets/svg/postgresql.svg";
import Facebook from "@/assets/svg/facebook.svg";
import Telegram from "@/assets/svg/telegram.svg";
import Tailwind from "@/assets/svg/tailwind.svg";
import Docker from "@/assets/svg/docker.svg";
import Firebase from "@/assets/svg/firebase.svg";

useHead({
  title: "Sodara Sou",
});
</script>
