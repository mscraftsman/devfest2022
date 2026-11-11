<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <header class="shadow-md bg-white sticky top-0 z-50 header--top">
    <nav class="max-w-6xl mx-auto py-4 px-4 lg:px-0">
      <div class="flex justify-between items-center">
        <!-- <RouterLink to="/"> -->
        <router-link :to="{ name: 'home' }" rel="noreferrer" class="text-sm"
          ><img src="/images/gdg-mauritius-logo.svg" alt="GDG Mauritius" class="h-3.5 md:h-5"
        /></router-link>
        <!-- </RouterLink> -->

        <div class="hidden md:block">
          <ul class="flex flex-row gap-4 text-sm">
            <li
              class="py-2 border-b-4 border-white hover:border-b-4 hover:border-green-600 hover:transition hover:ease-in-out duration-300"
            >
              <RouterLink to="/">HOME</RouterLink>
            </li>
            <li
              class="py-2 border-b-4 border-white hover:border-b-4 hover:border-green-600 hover:transition hover:ease-in-out duration-300"
            >
              <RouterLink to="/agenda">AGENDA</RouterLink>
            </li>
            <li
              class="py-2 border-b-4 border-white hover:border-b-4 hover:border-green-600 hover:transition hover:ease-in-out duration-300"
            >
              <RouterLink to="/speakers">SPEAKERS</RouterLink>
            </li>
            <li
              class="py-2 border-b-4 border-white hover:border-b-4 hover:border-green-600 hover:transition hover:ease-in-out duration-300"
            >
              <a
                href="https://devfest-mauritius-2022.sessionize.com/"
                target="_blank"
                rel="noreferrer"
                >PWA</a
              >
            </li>
            <li
              class="py-2 border-b-4 border-white hover:border-b-4 hover:border-green-600 hover:transition hover:ease-in-out duration-300"
            >
              <a
                href="https://devfest2022.myboothpic.co/virtual/capture/VyGKV"
                target="_blank"
                rel="noreferrer"
                >PHOTOBOOTH</a
              >
            </li>
            
            <li
              class="py-2 border-b-4 border-white hover:border-b-4 hover:border-green-600 hover:transition hover:ease-in-out duration-300"
            >
              <a
                href="https://gdg.community.dev/events/details/google-gdg-mauritius-presents-devfest-mauritius-2022/"
                target="_blank"
                rel="noreferrer"
                >REGISTER</a
              >
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>

  <RouterView />

  <footer class="bg-gray-100">
    <div class="max-w-6xl mx-auto">
      <nav
        class="py-6 lg:py-12 mx-4 lg:mx-0 flex flex-col md:flex-row gap-4 md:gap-0 justify-between border-b border-gray-300"
      >
        <!-- Quick Links -->
        <div class="flex flex-col gap-1 text-gray-500">
          <h3 class="mb-2 text-xl text-gray-600 font-bold">Quick Links</h3>
          <a
            href="https://gdg.community.dev/gdg-mauritius"
            target="_blank"
            rel="noreferrer"
            class="text-sm"
            >GDG Mauritius</a
          >
          <a
            href="https://developers.google.com/community/gdg"
            target="_blank"
            rel="noreferrer"
            class="text-sm"
            >About GDG</a
          >
          <a
            href="https://developers.google.com/community-guidelines"
            target="_blank"
            rel="noreferrer"
            class="text-sm"
            >Community Guidelines</a
          >
        </div>
        <!-- Past DevFests -->
        <div class="flex flex-col gap-1 text-gray-500">
          <h3 class="mb-2 text-xl text-gray-600 font-bold">
            Explore Past DevFests
          </h3>
          <a
            href="https://www.mscc.mu/devfest-mauritius-2020/"
            target="_blank"
            rel="noreferrer"
            class="text-sm"
            >DevFest Mauritius 2020</a
          >
          <a
            href="https://www.mscc.mu/devfest-mauritius-2019/"
            target="_blank"
            rel="noreferrer"
            class="text-sm"
            >DevFest Mauritius 2019</a
          >
          <a
            href="https://www.mscc.mu/devfest-mauritius-2018/"
            target="_blank"
            rel="noreferrer"
            class="text-sm"
            >DevFest Mauritius 2018</a
          >
        </div>
        <!-- Event Resources -->
        <div class="flex flex-col gap-1 text-gray-500">
          <h3 class="mb-2 text-xl text-gray-600 font-bold">Event Resources</h3>
          <a
            href="https://docs.google.com/presentation/d/1vyrgK43NUdWNe8A_sYwuJOwD-gBvLxyIvxIVrhNdxpA/edit?usp=sharing"
            target="_blank"
            rel="noreferrer"
            class="text-sm"
            >Partnership Proposition</a
          >
          <a
            href="https://sessionize.com/google-devfest-2022-mauritius/"
            target="_blank"
            rel="noreferrer"
            class="text-sm"
            >Call for Papers</a
          >
          <a
            href="https://docs.google.com/presentation/d/1LBo5xogj1FZOhpECjU1pxPOvCgTKVT7mUP8ngV95Xgg/edit?usp=sharing"
            target="_blank"
            rel="noreferrer"
            class="text-sm"
            >Speaker Presentation Template</a
          >
        </div>
      </nav>

      <div class="py-4 mx-4 lg:mx-0 flex flex-row justify-between items-center">
        <a
          href="https://gdg.community.dev/gdg-mauritius"
          target="_blank"
          rel="noreferrer"
          class="text-sm"
          ><img class="h-12" src="/images/logo-dark.png" alt="GDG Mauritius"
        /></a>
        <a
          href="https://www.mscc.mu/code-of-conduct/"
          target="_blank"
          rel="noreferrer"
          class="text-sm text-gray-500"
          >Code of Conduct</a
        >
      </div>
    </div>
  </footer>
</template>

<style scoped>
.header--top {
  z-index: 500;
}
</style>
