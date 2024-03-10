<template>
  <section
    class="bg-black text-white flex items-center justify-center py-5 font-sans"
  >
    <!-- div 1 -->
    <div class="lg:w-[30%] md:w-1/2 w-[40%] flex items-center">
      <img src="../images/logo.png" alt="" class="w-11" />
      <h1 class="font-extrabold md:text-2xl text-xl px-2">Marico</h1>
    </div>
    <!-- div 2 -->

    <ul
      class="xl:w-[20%] w-[30%] lg:flex hidden items-center justify-evenly text-gray-500 text-base"
    >
      <li class="hover:cursor-pointer hover:text-blue-500">
        Use Cases
        <i class="fa-solid fa-chevron-down pl-2 text-[0.700rem]"></i>
      </li>
      <li class="hover:cursor-pointer hover:text-blue-500">About</li>
      <li class="text-blue-500">Pricing</li>
      <li class="hover:cursor-pointer hover:text-blue-500">Blog</li>
    </ul>
    <!-- div 3 -->

    <div class="lg:w-[30%] md:w-[40%] w-1/2 items-center">
      <fwb-button color="default" class="float-end"> Sign Up</fwb-button>

      <fwb-button color="none" class="float-end mx-2">Login</fwb-button>
    </div>
  </section>
</template>

<script setup>
import { FwbButton } from "flowbite-vue";
</script>

<style lang="scss" scoped></style>
