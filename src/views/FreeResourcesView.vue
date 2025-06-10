<!-- This page is to emulate my leadpages free resources page found here https://fatforweightloss.lpages.co/free-resources-thank-you/ -->
<template>
  <div class="bg-white free-resources-view font-sourceSansPro">
    <div class="max-w-[1200px] mx-auto">
      <main class="px-4 py-8">
        <!-- Hero Section -->
        <section class="text-center mb-12">
          <h1 class="text-4xl text-green-500 font-bold mb-4">The free resources are available below 👍</h1>
          <h2 class="text-4xl font-bold mb-8">Feel free to grab as many free downloads as you like!</h2>
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
          <h2 class="text-4xl font-bold">Need More Inspiration? 👇</h2>
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
              <h2 class="text-4xl font-bold">
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
              <button class="resource-button" @click="navigateTo('https://fatforweightloss.thrivecart.com/cravings-ebook-bundle/')">
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
          <h3 class="text-3xl font-bold mb-8">As Featured On</h3>
          <div class="flex justify-center items-center gap-8 flex-wrap">
            <img :src="health" alt="Health Magazine" class="h-12">
            <img :src="womensHealth" alt="Women's Health" class="h-12">
            <img :src="shape" alt="Shape Magazine" class="h-12">
            <img :src="buzzfeed" alt="BuzzFeed" class="h-12">
          </div>
        </div>

        <!-- Recipe Section -->
        <div class="mt-16 bg-[rgba(235,239,244,1)] py-16">
          <div class="max-w-[1200px] mx-auto px-4">
            <div class="grid md:grid-cols-3 gap-8">
              <div class="text-center">
                <div class="relative mb-4">
                  <img :src="scones" alt="Keto Friendly Scones with Jam" class="w-full h-auto rounded-lg transform hover:scale-105 transition-transform">
                </div>
                <h3 class="text-xl font-bold mb-2">Keto Friendly Scones with Jam</h3>
                <p class="text-gray-600">Delicious scones with whipped cream and keto blueberry jam. Perfect for cravings.</p>
              </div>

              <div class="text-center">
                <div class="relative mb-4">
                  <img :src="chicken" alt="Keto Takeaway Sesame Chicken" class="w-full h-auto rounded-lg transform hover:scale-105 transition-transform">
                </div>
                <h3 class="text-xl font-bold mb-2">Keto Takeaway Sesame Chicken</h3>
                <p class="text-gray-600">Skip the chinese takeout and have this sesame seed chicken instead. The whole family will love it.</p>
              </div>

              <div class="text-center">
                <div class="relative mb-4">
                  <img :src="bread" alt="Keto Garlic Bread" class="w-full h-auto rounded-lg transform hover:scale-105 transition-transform">
                </div>
                <h3 class="text-xl font-bold mb-2">Keto Garlic Bread</h3>
                <p class="text-gray-600">Freshly baked garlic bread for an entree, or a sneaky netflix and chill.</p>
              </div>
            </div>
          </div>
        </div>

        <!-- What's Included Section -->
        <div class="mt-12 max-w-[1200px] mx-auto px-4">
          <h2 class="text-4xl font-bold text-center mb-8">What's Included</h2>
          
          <div class="space-y-8">
            <!-- The Beginners Ketogenic Cookbook -->
            <div class="grid md:grid-cols-2 gap-6">
              <div>
                <div class="flex items-center gap-2 mb-1">
                  <span class="text-blue-500">✓</span>
                  <h3 class="text-2xl font-bold">The Beginners Ketogenic Cookbook</h3>
                </div>
                <p class="text-blue-500 mb-2">(RRP $14.99)</p>
                <p><span class="font-semibold">50+ Keto recipes for beginners</span> to the ketogenic diet, including all the staple recipes for making the transition into low carb as easy as possible.</p>
              </div>

              <div>
                <div class="flex items-center gap-2 mb-1">
                  <span class="text-blue-500">✓</span>
                  <h3 class="text-2xl font-bold">Keto Bread Recipe eBook</h3>
                </div>
                <p class="text-blue-500 mb-2">(RRP $9.99)</p>
                <p>This cookbook is a combination of all of my favourite keto bread recipes including naan bread, super flexible wraps, garlic bread (my favourite), nut free keto bread, and <span class="text-gray-600">20+ other recipes</span> I know you're going to enjoy.</p>
              </div>
            </div>

            <!-- Keto Recipes Everyone Will Actually Eat -->
            <div class="grid md:grid-cols-2 gap-6">
              <div>
                <div class="flex items-center gap-2 mb-1">
                  <span class="text-blue-500">✓</span>
                  <h3 class="text-2xl font-bold">Keto Recipes Everyone Will Actually Eat</h3>
                </div>
                <p class="text-blue-500 mb-2">(RRP $14.99)</p>
                <p><span class="font-semibold">100+ Keto Recipes</span> including breakfasts, main meals, desserts and snacks that are super easy, and <span class="text-gray-600">made in under 30 minutes</span>.</p>
              </div>

              <div>
                <div class="flex items-center gap-2 mb-1">
                  <span class="text-blue-500">✓</span>
                  <h3 class="text-2xl font-bold">Keto Christmas eCookbook</h3>
                </div>
                <p class="text-blue-500 mb-2">(RRP $9.99)</p>
                <p>This cookbook was my guideline to creating a keto Christmas last year, but it's been upgraded and made <span class="font-bold">EVEN BETTER</span>. Even if you're not planning on sticking to keto this Christmas, you'll still find recipes that you can take along to your family dinner that will <span class="text-gray-600">BLOW THEIR MINDS!</span></p>
              </div>
            </div>

            <!-- 3 Ingredient Keto eCookbook -->
            <div class="grid md:grid-cols-2 gap-6">
              <div>
                <div class="flex items-center gap-2 mb-1">
                  <span class="text-blue-500">✓</span>
                  <h3 class="text-2xl font-bold">3 Ingredient Keto eCookbook</h3>
                </div>
                <p class="text-blue-500 mb-2">(RRP $9.99)</p>
                <p>That's right, 3 ingredients. Sounds crazy right? In this book I teach you how to create delicious, <span class="text-gray-600">creative meals using only 3 ingredients</span>. Honestly, this is how I eat almost every day. You can make this with ANY ingredients. I'll show you how easy it is!</p>
              </div>
            </div>
          </div>

          <div class="mt-8 text-center">
            <button class="resource-button max-w-[800px] mx-auto">Add to cart now</button>
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
import scones from '@/assets/images/scones.png'
import chicken from '@/assets/images/chicken.png'
import bread from '@/assets/images/breadsticks.png'

const navigateTo = (url: string) => {
  window.location.href = url
}
</script>

<style>
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
  @apply bg-green-500 text-white text-xl font-bold py-4 px-6 rounded-lg text-center hover:bg-green-600 transition-colors block w-full;
}

.free-resources-view {
  width: 100%;
  max-width: 100%;
}
</style> 