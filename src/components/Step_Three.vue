<template>
  <section class="text-white">
    <p class="text-center text-blue-500 font-semibold md:pt-20 pt-10">STEP 3</p>

    <h1 class="md:text-6xl text-4xl text-center py-2 font-semibold">
      Connect Your Content
    </h1>
    <p class="text-center py-6 text-gray-500 md:text-lg">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex quas corporis
      accusamus ipsum hic non, <br />
      error voluptas porro officia cum autem neque iste quod nesciunt
      necessitatibus pariatur odio unde. Similique.
    </p>
    <!-- section -->
    <section class="lg:flex my-16 justify-center font-sans">
      <div class="2xl:w-[40%] lg:w-1/2 w-10/12 m-auto text-white py-10 px-2">
        <h1 class="pb-10 text-lg">Create & Share</h1>

        <h1 class="text-6xl font-semibold pb-10">
          Reach Your <br />
          Audience
          <span class="text-blue-500"> Directly</span>
        </h1>
        <p class="text-white font-sans py-4 text-base">
          <span
            class="bg-gray-600 text-white w-5 h-10 rounded-[50%] p-0.5 px-2 font-serif"
            >1</span
          >
          Lorem ipsum dolor sit amet consectetur adipisicing elit.
        </p>

        <p class="text-white font-sans text-base py-2">
          <span
            class="bg-gray-600 text-white font-serif w-5 h-10 rounded-[50%] p-0.5 px-2"
            >2</span
          >
          Lorem ipsum dolor sit amet consectetur adipisicing elit.
        </p>
        <fwb-button size="lg" class="mr-2 md:my-20 my-10">Get Staeted Now</fwb-button>
        <fwb-button
          size="lg"
          color=""
          class="border rounded-xl ml-1 border-gray-500 text-gray-500"
          >Get Staeted Now</fwb-button
        >
      </div>
      <div class="2xl:w-[40%] lg:w-1/2 w-10/12 m-auto">
        <img src="../images/Screen2.png" alt="" class="h-[93%]" />
      </div>
    </section>
  </section>
</template>

<script setup>
import { FwbButton } from "flowbite-vue";
</script>

<style lang="scss" scoped></style>
