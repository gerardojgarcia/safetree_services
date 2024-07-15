<script setup></script>
<template>
  <div class="hero grid h-screen bg-dark_slate_gray">
    <div
      class="heading md:w-1/2 flex flex-col items-center justify-center bg-dark_slate_gray h-full bg-opacity-85"
    >
      <h1 class="text-5xl text-center mb-8 md:px-12 text-white">
        Your Trusted Partner in Expert
        <strong class="text-safety_orange">Tree Care</strong>
      </h1>
      <p class="subheading text-center text-2xl md:px-32 text-white">
        Ensuring the Health, Safety, and Beauty of Your Trees
      </p>
      <div
        class="button-container w-3/4 bg-opacity-85 px-4 rounded-lg justify-between py-4 mt-16 flex flex-col md:flex-row"
      >
        <NuxtLink
          to="quote"
          class="hero-quote hover:bg-safety_orange text-white border-safety_orange border-2 p-2 rounded-md duration-150"
          >Get A Free Quote</NuxtLink
        >
      </div>
    </div>
  </div>
</template>
<style scoped>
.hero {
  background-image: url("/safeetree_hero.webp");
  background-repeat: no-repeat;
  background-position: right;
  background-size: cover;
}
</style>
