<script setup></script>
<template>
    <div class="hero grid  pb-32 mt-16 bg-white from-50% text-dark_slate_gray" data-aos="fade-up">
        <div
            class="heading flex flex-col md:flex-row p-8 py-4 items-center justify-center text-dark_slate_gray h-full bg-opacity-85"
        >
      <div class="grid place-items-center w-1/2">


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
                    to="/#services"
                    class="hero-quote animate-bounce  hover:animate-none hover:bg-safety_orange  border-safety_orange border-2 p-2 rounded-md duration-150"
                    >Learn More </NuxtLink
                >
            </div>



      </div>
       <div class="hero-image grid place-items-center w-1/2 pt-18 overflow-hidden rounded-xl bg-[url('/safetree_hero.webp')]" data-aos="fade-up" data-aos-delay="1500">
        <TheQuoteTool/>

        </div>
                   </div>
       
    </div>

</template>

