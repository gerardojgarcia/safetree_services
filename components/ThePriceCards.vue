<script setup>
const cards = ref([
  {
    id: 1,
    pretitle: "Adequate Protection",
    title: "Basic Care Package",
    description:
      "Essential services for maintaining the health and appearance of smaller trees.",
    pricing: ["starting at $400"],
    features: ["Tree Trimming and Pruning (up to 2 small trees)", "Acrylic Sealing", "10 Year Guarantee"],
  },
  {
    id: 2,
    pretitle: "Long-lasting Coverage",
    title: "Standard Care Package",
    description:
      "Comprehensive care for medium-sized properties with a mix of tree types.",
    pricing: ["starting at $1200"],
    features: [
      "Tree Trimming and Pruning (up to 3 medium trees)",
      "Tree Health Assessment (2 trees)",
      "Stump Grinding (2 stumps, up to 15 inches in diameter each)",
      "Tree Removal (1 small tree)",
    ],
  },
  {
    id: 3,
    pretitle: "Full Protection",
    title: "Premium Care Package",
    description:
      "Extensive services for large properties or those with significant tree care needs.",
    pricing: ["starting at $2,500"],
    features: [
      "Tree Trimming and Pruning (up to 5 large trees)",
      "Tree Health Assessment (3 trees)",
      "Stump Grinding (3 stumps, up to 15 inches in diameter each)",
      "Tree Removal (1 medium tree)",
      "Tree Cabling and Bracing (1 tree)",
    ],
  },
  {
    id: 4,
    pretitle: "Coverage for Life's Surprises",
    title: "Emergency and Storm Protection Package",
    description:
      "Emergency response and preventive care for storm-prone areas.",
    pricing: ["starting at $1,500"],
    features: [
      "24/7 Emergency Tree Services (priority response)",
      "Tree Trimming and Pruning (up to 2 large trees)",
      "Tree Cabling and Bracing (2 trees)",
      "Tree Health Assessment (1 tree)",

    ],
  },
  {
    id: 5,
    pretitle: "Coverage for Life's Surprises",
    title: "Tree Health and Beautification Package",
    description:
      "Focused on enhancing the aesthetic and health of your trees.",
    pricing: ["starting at $1,800"],
    features: [
      "Tree Trimming and Pruning (up to 4 medium trees)",
      "Tree Health Assessment and Treatment (3 trees)",
      "Tree Planting (1 mature tree)",
      "Stump Grinding (1 stump, up to 15 inches in diameter)",

    ],
  },
]);
</script>
<template>
  <section
    class="price-card-container grid grid-cols-1 py-16 place-items-center dark:text-white dark:bg-dark_slate_gray"
    data-aos="fade-up"
  >
    <div class="px-4 md:px-60 flex justify-center flex-col items-center">
      <h3 class="pb-4 text-4xl">SafeTree Services Packages</h3>
      <p class="price-cards-subheading text-2xl">
        At SealTech Pro, we offer a comprehensive range of concrete sealing services
        tailored to meet the needs of residential, commercial, and industrial clients.
        From surface preparation and crack repair to applying various types of sealants,
        our expert team ensures your concrete surfaces are protected, durable, and
        visually appealing. Explore our service packages to find the perfect solution for
        your project.
      </p>
    </div>

    <div class="grid md:grid-cols-3 gap-4 mt-24 px-4 md:px-16">
      <!-- Price Card -->
      <div
        class="price-card p-8 md:px-10 rounded-lg dark:bg-steel_blue border-2 hover:border-blue-600 dark:hover:border-blue-200 duration-150 ease-in dark:hover:border-3 border-steel_blue hover:shadow-lg flex flex-col"
        v-for="card in cards"
        :key="card.id"
        data-aos="fade-up"
      >
        <div class="mb-auto">
          <p class="pre-title text-lg">{{ card.pretitle }}</p>
          <p class="card-title text-4xl font-bold py-2">{{ card.title }}</p>
          <ul class="card-pricing flex flex-col py-8 text-xl">
            <li v-for="price in card.pricing" :key="card.pricing">
              {{ price }}
            </li>
          </ul>
          <ul class="card-features list-outside space-y-2 mb-8">
            <li v-for="feature in card.features" :key="card.features" class="font-bold"><Icon name="ph:check-circle-bold" color="black" class="mr-2 " />
              {{ feature }}
            </li>
          </ul>
          <p class="card-description text-xl">{{ card.description }}</p>
        </div>

        <button
          class="border-2 border-safety_orange rounded-md p-2 md:w-1/4 self-end mt-16 hover:shadow-lg hover:bg-safety_orange hover:text-white duration-150"
        >
          Book now
        </button>
      </div>

      
    </div>
    <div class="mt-16">
      <div class="price-card-add-ons p-4  space-y-2">
        <strong class="text-4xl" >Add-On Services</strong>
        <p class="text-lg">Additional Tree Trimming and Pruning: $100 - $500 per tree (based on size)</p>
        <p class="text-lg">Additional Stump Grinding: $75 - $200 per stump (based on diameter)</p>
        <p class="text-lg">Additional Tree Health Assessment: $50 per tree</p>
        <p class="text-lg">Additional Tree Removal: $200 - $1,500 per tree (based on size)</p>
      
        </div>
        <div class="price-card-benefits p-4 space-y-2">
        <strong class="text-4xl">Package Benefits</strong>
        <p class="text-lg">Cost Savings: Bundled services offer significant savings compared to a la carte pricing.</p>
        <p class="text-lg">Priority Scheduling: Package customers receive priority scheduling for services.</p>
        <p class="text-lg">Customizable Options: Packages can be customized to meet specific customer needs.</p>
      
        </div>
    </div>
  </section>
</template>
