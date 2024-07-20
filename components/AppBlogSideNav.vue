<script setup>
import articles from "/data/articles.js";
</script>
<template>
    <div>
        <nav class="side-nav flex flex-col">
            <NuxtLink
                :to="articles.link"
                class="hover:text-concrete_gray"
                v-for="article in articles"
                :key="article.id"
                >{{ article.title }}
            </NuxtLink>
        </nav>
    </div>
</template>
<style scoped>
.router-link-active {
    font-weight: bold;
    color: #2563eb;
}
</style>
