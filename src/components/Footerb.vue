<template>
  <!-- Footer -->
  <footer  class="pt-8 pb-6">
    <div
      class="bottom-auto top-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden -mt-20"
      style="height: 80px; transform: translateZ(0px)"
    >
      <svg
        class="absolute bottom-0 overflow-hidden"
        xmlns="http://www.w3.org/2000/svg"
        preserveAspectRatio="none"
        version="1.1"
        viewBox="0 0 2560 100"
        x="0"
        y="0"
      >
        <polygon
          class="text-purple-600 fill-current"
          points="2560 0 2560 100 0 100"
           style="background: linear-gradient(90deg, #c4cffd 0%, #7e00f5 100%)"
        />
      </svg>
    </div>
    <div class="container mx-auto px-4">
      <div class="flex justify-center">
        <div class="w-full lg:w-6/12 px-4">
          <h4 class="text-3xl font-semibold flex justify-center">
            Follow us on social media
          </h4>
          <h5 class="text-lg mt-0 mb-2 text-gray-700 flex justify-center">
            Find us on any of these platforms, we respond 1-2 business days.
          </h5>
          <div class="mt-6 flex justify-center">

           <a href="http://www.instagram.com/j_not_query"><button id="learn"
              class=" bg-white text-blue-600 shadow-lg font-normal h-10 w-10 items-center justify-center align-center rounded-full outline-none focus:outline-none mr-2 p-3"
              type="button"
            >
              <i
                class="flex fab fa-brands fa-instagram text-orange-500"
              />
            </button></a>
            
            <a href="https://www.linkedin.com/in/justin-parker-849356178">
            <button id="learn"
              class="bg-white text-pink-400 shadow-lg font-normal h-10 w-10 items-center justify-center align-center rounded-full outline-none focus:outline-none mr-2 p-3"
              type="button"
            >
              <i class="flex fab fa-linkedin text-orange-500" />
            </button></a>

          </div>
        </div>
      </div>
      <hr class="my-6 border-gray-400">
      <div
        class="flex flex-wrap items-center md:justify-between justify-center"
      >
        <div class="w-full md:w-4/12 px-4 mx-auto text-center">
          <div class="text-sm text-gray-600 font-semibold py-1">
            Copyright © Justin Parker
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script lang="ts">
import { Icon } from '@iconify/vue';

export default {Icon}
</script>

<style>
</style>
