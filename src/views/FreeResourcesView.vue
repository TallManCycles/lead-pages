<template>
  <div class="bg-white free-resources-view">
    <div class="max-w-[1200px] mx-auto">
      <main class="px-4 py-8">
        <!-- Hero Section -->
        <section class="text-center mb-12">
          <h1 class="text-4xl text-green-500 font-bold mb-4 font-sourceSansPro">The free resources are available below 👍</h1>
          <h2 class="text-4xl font-bold mb-8 font-sourceSansPro">Feel free to grab as many free downloads as you like!</h2>
        </section>

        <!-- Resources Grid -->
        <div class="flex flex-col space-y-4 mb-12 max-w-[800px] mx-auto">
          <a href="#" class="resource-button">Free Example Day Of Eating Meal Plans</a>
          <a href="#" class="resource-button">Free Keto Meal Plans</a>
          <a href="#" class="resource-button">Free Keto Recipe Cookbooks</a>
          <a href="#" class="resource-button">Free Keto Resources</a>
        </div>

        <!-- Inspiration Section -->
        <section class="text-center">
          <h2 class="text-4xl font-bold font-sourceSansPro">Need More Inspiration? 👇</h2>
        </section>

        <!-- Bundle Features Section -->
        <div class="max-w-[1000px] mx-auto mt-12">
          <div class="grid md:grid-cols-2 gap-8 items-center">
            <div class="relative">
              <img :src="ebooks" alt="Keto Recipe Books Bundle" class="w-full">
              <p class="text-center mt-4 italic text-gray-600">
                With <span class="font-semibold">260+ simple recipes</span> with easy to find ingredients, you'll always have the power to eat healthy, delicious meals, even when the cravings strike.
              </p>
            </div>
            <div class="space-y-6">
              <h2 class="text-4xl font-bold font-sourceSansPro">
                Keto Cravings Bundle <span class="text-green-500">(50% OFF)</span>
              </h2>
              <ul class="space-y-4 text-lg">
                <li class="flex items-start gap-2">
                  <span class="text-green-500">✓</span>
                  Are you struggling to find recipes that are easy, and don't require hard to find ingredients?
                </li>
                <li class="flex items-start gap-2">
                  <span class="text-green-500">✓</span>
                  Are you finding it tough to stay inspired and committed to your health with the same recipes every day?
                </li>
                <li class="flex items-start gap-2">
                  <span class="text-green-500">✓</span>
                  Wouldn't you like to learn how to easily cook meals fo breakfast, lunch and dinner that aren't just bacon, cheese and butter?
                </li>
              </ul>
              <div class="text-green-500 font-semibold">
                Then getting your copy of Keto Cavings bundle is a great next step!
              </div>
              <button class="resource-button">
                YES! Add to cart now
              </button>
              <p class="text-sm text-gray-600 italic">
                From the moment you download these recipes, you'll feel totally inspired. Just think of how easy it's going to be to stay on track, plan your meals and keep your family happy with The Keto Jumpstart Bundle.
              </p>
            </div>
          </div>
        </div>

        <!-- As Featured On Section -->
        <div class="mt-16 text-center">
          <h3 class="text-3xl font-bold mb-8 font-sourceSansPro">As Featured On</h3>
          <div class="flex justify-center items-center gap-8 flex-wrap">
            <img :src="health" alt="Health Magazine" class="h-12">
            <img :src="womensHealth" alt="Women's Health" class="h-12">
            <img :src="shape" alt="Shape Magazine" class="h-12">
            <img :src="buzzfeed" alt="BuzzFeed" class="h-12">
          </div>
        </div>
      </main>
    </div>
  </div>
</template>

<script setup lang="ts">
import ebooks from '@/assets/images/ebooks.jpg'
import health from '@/assets/images/health.png'
import womensHealth from '@/assets/images/womenshealth.jpg'
import shape from '@/assets/images/shape.png'
import buzzfeed from '@/assets/images/buzzfeed.png'
// Component logic will go here
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Source+Sans+Pro:wght@400;600;700&display=swap');

/* Override the root app grid layout */
@media (min-width: 1200px) {
  #app {
    display: block !important;
    grid-template-columns: none !important;
  }
}
</style>

<style scoped>
.resource-button {
  @apply bg-green-500 text-white text-xl font-semibold py-4 px-6 rounded-lg text-center hover:bg-green-600 transition-colors block w-full;
}

.free-resources-view {
  width: 100%;
  max-width: 100%;
}

.font-sourceSansPro {
  font-family: 'Source Sans Pro', sans-serif;
}
</style> 