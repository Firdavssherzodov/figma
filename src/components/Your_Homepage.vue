<template>
  <section class="lg:flex md:my-16 my-10 justify-center font-sans">
    <div
      class="2xl:w-[40%] lg:w-[45%] w-10/12 m-auto text-white py-10 md:px-2 px-0"
    >
      <h1 class="pb-10 text-lg">Your Homepage</h1>

      <h1 class="md:text-6xl text-5xl font-semibold md:pb-10 pb-8">
        Your Content. <br />
        All in
        <span class="text-blue-500">One Spot</span>
      </h1>
      <p class="text-white font-sans py-4 text-base">
        <span
          class="md:bg-gray-600 text-white w-5 h-10 rounded-[50%] p-0.5 md:px-2 font-serif"
          >1</span
        >
        Lorem ipsum dolor sit amet consectetur adipisicing elit.
      </p>

      <p class="text-white font-sans text-base md:py-2 py-0">
        <span
          class="md:bg-gray-600 text-white font-serif w-5 h-10 rounded-[50%] p-0.5 md:px-2"
          >2</span
        >
        Lorem ipsum dolor sit amet consectetur adipisicing elit.
      </p>

      <fwb-button size="" class="p-3 mr-2 md:my-20 my-10"
        >Get Staeted Now</fwb-button
      >
      <fwb-button
        size=""
        color=""
        class="border rounded-xl p-3 md:ml-1 border-gray-500 text-gray-500"
        >Get Staeted Now</fwb-button
      >
    </div>
    <div class="2xl:w-[40%] lg:w-1/2 w-[95%]">
      <img src="../images/Screen.png" alt="" class="" />
    </div>
  </section>
</template>

<script setup>
import { FwbButton } from "flowbite-vue";
</script>

<style lang="scss" scoped></style>
