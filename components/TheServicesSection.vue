<script setup></script>

<template>
    <section
        id="services"
        class="grid md:grid-cols-2 place-items-center dark:text-white dark:bg-dark_slate_gray"
    >
        <div
            class="grid place-items-center rounded-lg w-full overflow-hidden h-full bg-[url('/safetree_3.webp')] bg-center bg-no-repeat"
            data-aos="fade-right"
        ></div>
        <div class="p-8" data-aos="fade-left">
            <h2 class="text-4xl mb-6">Our Services</h2>
            <p class="text-2xl">
                Before sealing, proper cleaning and preparation of the concrete
                surface are crucial. Our team ensures that every surface is
                thoroughly cleaned and prepped, providing a solid foundation for
                the sealing process.
            </p>
            <div class="mt-8 grid md:grid-cols-2 gap-4">
                <div
                    class="hover:shadow-lg rounded-lg p-4 duration-150 hover:border-2 hover:border-safety_orange"
                >
                    <strong class="text-2xl">Tree Trimming and Pruning</strong>
                    <p class="p-2">Small Trees (up to 30 feet): $75 - $400</p>
                    <p class="p-2">Medium Trees (30 to 60 feet): $150 - $800</p>
                    <p class="p-2">
                        Large Trees (60 feet and taller): $400 - $1,500
                    </p>
                </div>
                <div
                    class="hover:shadow-lg rounded-lg p-4 duration-150 hover:border-2 hover:border-safety_orange"
                >
                    <strong class="text-2xl">Tree Removal</strong>
                    <p class="p-2">Small Trees (up to 30 feet): $200 - $800</p>
                    <p class="p-2">
                        Medium Trees (30 to 60 feet): $600 - $1,500
                    </p>
                    <p class="p-2">
                        Large Trees (60 feet and taller): $1,500 - $3,000
                    </p>
                </div>
                <div
                    class="hover:shadow-lg rounded-lg p-4 duration-150 hover:border-2 hover:border-safety_orange"
                >
                    <strong class="text-2xl">Stump Grinding and Removal</strong>
                    <p class="p-2">Per Stump: $100 - $400</p>
                    <p class="p-2">Per Inch of Stump Diameter: $2 - $5</p>
                </div>
                <div
                    class="hover:shadow-lg rounded-lg p-4 duration-150 hover:border-2 hover:border-safety_orange"
                >
                    <strong class="text-2xl">Emergency Tree Services</strong>
                    <p class="p-2">
                        After Hours or Storm Damage: $250 - $1,000 (additional
                        to regular service rates)
                    </p>
                </div>
                <div
                    class="hover:shadow-lg rounded-lg p-4 duration-150 hover:border-2 hover:border-safety_orange"
                >
                    <strong class="text-2xl"
                        >Tree Health Assessments and Treatment</strong
                    >
                    <p class="p-2">Consultation and Diagnosis: $75 - $200</p>
                    <p class="p-2">
                        Treatment (e.g., pest control, disease management): $50
                        - $500 per treatment
                    </p>
                </div>
                <div
                    class="hover:shadow-lg rounded-lg p-4 duration-150 hover:border-2 hover:border-safety_orange"
                >
                    <strong class="text-2xl">Tree Cabling and Bracing</strong>
                    <p class="p-2">Installation: $200 - $800 per tree</p>
                    <p class="p-2">
                        Maintenance and Adjustment: $100 - $300 per visit
                    </p>
                </div>
                <div
                    class="hover:shadow-lg rounded-lg p-4 duration-150 hover:border-2 hover:border-safety_orange"
                >
                    <strong class="text-2xl">Tree Planting</strong>
                    <p class="p-2">Young Trees (saplings): $150 - $500</p>
                    <p class="p-2">Mature Trees: $500 - $2,000</p>
                </div>
                <div
                    class="hover:shadow-lg rounded-lg p-4 duration-150 hover:border-2 hover:border-safety_orange"
                >
                    <strong class="text-2xl">Land and Lot Clearing</strong>
                    <p class="p-2">
                        Per Acre: $2,000 - $6,000 (depending on density and
                        terrain)
                    </p>
                </div>
            </div>
            <div class="button-container justify-between py-8 flex md:w-3/4">
                <NuxtLink
                    to="quote"
                    class="hero-quote border-safety_orange border-2 p-2 rounded-md hover:bg-safety_orange hover:text-white duration-150"
                    >Book Your Tree Service</NuxtLink
                >
            </div>
        </div>
    </section>
</template>
