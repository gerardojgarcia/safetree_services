<script setup>
const pages = ref([
    {
        id: 1,
        title: "Benefits of Professional Tree Trimming",
        date: "05-23-2024",
        description:
            "Explore the advantages of hiring professionals for tree trimming in residential areas.",
        link: "/blog/benefits-professional-residential-tree-trimming",
    },
    {
        id: 2,
        title: "Signs Your Trees Need Trimming",
        date: "06-19-2024",
        description:
            "Learn how to identify when your trees need trimming to maintain their health and safety.",
        link: "/blog/signs-trees-need-trimming",
    },
    {
        id: 3,
        title: "Best Time of Year for Tree Trimming in San Bernardino",
        date: "06-23-2024",
        description:
            "Discover the optimal times for tree trimming in San Bernardino County to ensure tree health.",
        link: "/blog/best-time-tree-trimming-san-bernardino",
    },
    {
        id: 4,
        title: "DIY Tree Trimming Tips",
        date: "06-23-2024",
        description:
            "Practical tips for safely trimming your trees at home.Practical tips for safely trimming your trees at home.",
        link: "/blog/diy-tree-trimming-tips",
    },
]);
</script>
<template>
  <div>
    <nav class="side-nav flex flex-col">
      <NuxtLink
        :to="page.link"
        class="hover:text-blue-400"
        v-for="page in pages"
        :key="page.id"
        >{{ page.title }}
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
