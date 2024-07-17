<script setup></script>
<template>
    <div class="hero grid grid-cols-2 bg-gradient-to-b from-white to-blue-400 from-70% h-screen  text-dark_slate_gray">
        <div
            class="heading flex flex-col p-8 items-center justify-center text-dark_slate_gray h-full bg-opacity-85"
        >
            <h1 class="text-5xl text-center mb-8 md:px-12 ">
                Your Trusted Partner in Expert
                <strong class="text-safety_orange">Tree Care</strong>
            </h1>
            <p class="subheading text-center text-2xl md:px-32 ">
                Ensuring the Health, Safety, and Beauty of Your Trees
            </p>
            <div
                class="button-container bg-opacity-85 px-4 rounded-lg py-4 mt-16 flex flex-col self-center md:flex-row"
            >
                <NuxtLink
                    to="/quote"
                    class="hero-quote hover:bg-safety_orange  border-safety_orange border-2 p-2 rounded-md duration-150"
                    >Get A Free Quote</NuxtLink
                >
            </div>
        </div>
        <div class="hero-image grid place-items-center overflow-hidden rounded-xl">
          <img src="/safeetree_hero.webp" alt="Image of workers doing maintenance service on a tree" />
        </div>
    </div>
</template>

