<script setup></script>
<template>
    <div>
        <header
            class="p-4 fixed w-full bg-white flex justify-evenly text-black top-0 items-center z-10 drop-shadow-lg"
        >
            <img
                src="/safetree_logo.png"
                alt="Safetree Services "
                width="100rem"
            />

            <!-- Main Navigation -->
            <nav class="flex w-1/2 justify-evenly font-bold">
                <NuxtLink to="/" class="hover:text-safety_orange"
                    >Home</NuxtLink
                >
                <NuxtLink to="/#services" class="hover:text-safety_orange"
                    >Services</NuxtLink
                >
                <NuxtLink to="/about" class="hover:text-safety_orange"
                    >About</NuxtLink
                >
                <NuxtLink to="/support" class="hover:text-safety_orange"
                    >Contact</NuxtLink
                >
            </nav>
            <NuxtLink
                to="/quote"
                class="hero-quote  hover:bg-safety_orange border-safety_orange border-2 hover:bg-blue-200 hover:shadow-lg hover:text-black p-2 rounded-md"
                >Get A Free Quote</NuxtLink
            >
        </header>
    </div>
</template>
