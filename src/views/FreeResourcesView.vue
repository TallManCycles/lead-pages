<!-- This page is to emulate my leadpages free resources page found here https://fatforweightloss.lpages.co/free-resources-thank-you/ -->
<template>
  <div class="bg-white">
    <main class="py-8">
      <!-- Hero Section -->
      <section class="container-width text-center mb-12">
        <h1 class="heading-primary text-green-500">The free resources are available below 👍</h1>
        <h2 class="heading-primary">Feel free to grab as many free downloads as you like!</h2>
      </section>

      <!-- Resources Grid -->
      <div class="container-width">
        <div class="flex flex-col space-y-4 mb-12 max-w-[800px] mx-auto">
          <a href="#" class="btn-primary">Free Example Day Of Eating Meal Plans</a>
          <a href="#" class="btn-primary">Free Keto Meal Plans</a>
          <a href="#" class="btn-primary">Free Keto Recipe Cookbooks</a>
          <a href="#" class="btn-primary">Free Keto Resources</a>
        </div>
      </div>

      <!-- Inspiration Section -->
      <section class="container-width text-center">
        <h2 class="heading-primary">Need More Inspiration? 👇</h2>
      </section>

      <!-- Bundle Features Section -->
      <div class="container-width section-spacing">
        <div class="grid md:grid-cols-2 gap-8 items-center">
          <div class="relative">
            <img :src="ebooks" alt="Keto Recipe Books Bundle" class="w-full">
            <p class="text-center mt-4 italic text-highlight">
              With <span class="font-semibold">260+ simple recipes</span> with easy to find ingredients, you'll always have the power to eat healthy, delicious meals, even when the cravings strike.
            </p>
          </div>
          <div class="space-y-6">
            <h2 class="heading-primary text-left mb-6">
              Keto Cravings Bundle <span class="text-green-500">(50% OFF)</span>
            </h2>
            <ul class="space-y-4 text-lg">
              <li class="flex items-start gap-2">
                <span class="checkmark">✓</span>
                Are you struggling to find recipes that are easy, and don't require hard to find ingredients?
              </li>
              <li class="flex items-start gap-2">
                <span class="checkmark">✓</span>
                Are you finding it tough to stay inspired and committed to your health with the same recipes every day?
              </li>
              <li class="flex items-start gap-2">
                <span class="checkmark">✓</span>
                Wouldn't you like to learn how to easily cook meals fo breakfast, lunch and dinner that aren't just bacon, cheese and butter?
              </li>
            </ul>
            <div class="text-green-500 font-semibold">
              Then getting your copy of Keto Cavings bundle is a great next step!
            </div>
            <button @click="navigateTo('https://fatforweightloss.thrivecart.com/cravings-ebook-bundle/')" class="btn-primary">
              YES! Add to cart now
            </button>
            <p class="text-sm text-highlight italic">
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
      <div class="section-spacing bg-[rgba(235,239,244,1)] py-16">
        <div class="container-width">
          <div class="grid md:grid-cols-3 gap-8">
            <div class="text-center">
              <div class="relative mb-4">
                <img :src="scones" alt="Keto Friendly Scones with Jam" class="w-full h-auto rounded-lg transform hover:scale-105 transition-transform">
              </div>
              <h3 class="text-xl font-bold mb-2">Keto Friendly Scones with Jam</h3>
              <p class="text-highlight">Delicious scones with whipped cream and keto blueberry jam. Perfect for cravings.</p>
            </div>

            <div class="text-center">
              <div class="relative mb-4">
                <img :src="chicken" alt="Keto Takeaway Sesame Chicken" class="w-full h-auto rounded-lg transform hover:scale-105 transition-transform">
              </div>
              <h3 class="text-xl font-bold mb-2">Keto Takeaway Sesame Chicken</h3>
              <p class="text-highlight">Skip the chinese takeout and have this sesame seed chicken instead. The whole family will love it.</p>
            </div>

            <div class="text-center">
              <div class="relative mb-4">
                <img :src="bread" alt="Keto Garlic Bread" class="w-full h-auto rounded-lg transform hover:scale-105 transition-transform">
              </div>
              <h3 class="text-xl font-bold mb-2">Keto Garlic Bread</h3>
              <p class="text-highlight">Freshly baked garlic bread for an entree, or a sneaky netflix and chill.</p>
            </div>
          </div>
        </div>
      </div>

      <!-- What's Included Section -->
      <div class="section-spacing container-width">
        <h2 class="heading-primary">What's Included</h2>
        
        <div class="space-y-8">
          <!-- The Beginners Ketogenic Cookbook -->
          <div class="grid md:grid-cols-2 gap-6">
            <div>
              <div class="flex items-center gap-2 mb-1">
                <span class="checkmark">✓</span>
                <h3 class="text-2xl font-bold">The Beginners Ketogenic Cookbook</h3>
              </div>
              <p class="price-tag">(RRP $14.99)</p>
              <p><span class="font-semibold">50+ Keto recipes for beginners</span> to the ketogenic diet, including all the staple recipes for making the transition into low carb as easy as possible.</p>
            </div>

            <div>
              <div class="flex items-center gap-2 mb-1">
                <span class="checkmark">✓</span>
                <h3 class="text-2xl font-bold">Keto Bread Recipe eBook</h3>
              </div>
              <p class="price-tag">(RRP $9.99)</p>
              <p>This cookbook is a combination of all of my favourite keto bread recipes including naan bread, super flexible wraps, garlic bread (my favourite), nut free keto bread, and <span class="text-highlight">20+ other recipes</span> I know you're going to enjoy.</p>
            </div>
          </div>

          <!-- Keto Recipes Everyone Will Actually Eat -->
          <div class="grid md:grid-cols-2 gap-6">
            <div>
              <div class="flex items-center gap-2 mb-1">
                <span class="checkmark">✓</span>
                <h3 class="text-2xl font-bold">Keto Recipes Everyone Will Actually Eat</h3>
              </div>
              <p class="price-tag">(RRP $14.99)</p>
              <p><span class="font-semibold">100+ Keto Recipes</span> including breakfasts, main meals, desserts and snacks that are super easy, and <span class="text-highlight">made in under 30 minutes</span>.</p>
            </div>

            <div>
              <div class="flex items-center gap-2 mb-1">
                <span class="checkmark">✓</span>
                <h3 class="text-2xl font-bold">Keto Christmas eCookbook</h3>
              </div>
              <p class="price-tag">(RRP $9.99)</p>
              <p>This cookbook was my guideline to creating a keto Christmas last year, but it's been upgraded and made <span class="font-bold">EVEN BETTER</span>. Even if you're not planning on sticking to keto this Christmas, you'll still find recipes that you can take along to your family dinner that will <span class="text-highlight">BLOW THEIR MINDS!</span></p>
            </div>
          </div>

          <!-- 3 Ingredient Keto eCookbook -->
          <div class="grid md:grid-cols-2 gap-6">
            <div>
              <div class="flex items-center gap-2 mb-1">
                <span class="checkmark">✓</span>
                <h3 class="text-2xl font-bold">3 Ingredient Keto eCookbook</h3>
              </div>
              <p class="price-tag">(RRP $9.99)</p>
              <p>That's right, 3 ingredients. Sounds crazy right? In this book I teach you how to create delicious, <span class="text-highlight">creative meals using only 3 ingredients</span>. Honestly, this is how I eat almost every day. You can make this with ANY ingredients. I'll show you how easy it is!</p>
            </div>
          </div>
        </div>

        <div class="mt-8 text-center">
          <button @click="navigateTo('https://fatforweightloss.thrivecart.com/cravings-ebook-bundle/')" class="btn-primary max-w-[800px] mx-auto">Add to cart now</button>
        </div>
        
      </div>
        <!-- Testimonial Section -->
        <div class="section-spacing bg-[rgba(235,239,244,1)] py-16">
          <div class="container-width">
            <h2 class="text-4xl font-bold text-center mb-12 text-gray-700">What Others Are Saying</h2>
            <div class="grid md:grid-cols-3 gap-8">
              <!-- Testimonial 1 -->
              <div class="bg-white rounded shadow p-8 flex flex-col items-start">
                <div class="flex mb-4">
                  <span class="text-yellow-400 text-2xl mr-1" v-for="i in 5" :key="i">★</span>
                </div>
                <h3 class="font-bold text-xl mb-4">Genuinely meals that a family could eat</h3>
                <p class="mb-6 text-gray-700">
                  I purchased this set... and not only is it great value... but the recipies are easy to make, and delicious. And genuinely meals that a family could eat (without knowing it's keto ;).<br>
                  I hate cooking at the best of times... but these books make it enjoyable and rewarding
                </p>
                <span class="font-bold text-gray-800 mt-auto">- Jodie Daniel</span>
              </div>
              <!-- Testimonial 2 -->
              <div class="bg-white rounded shadow p-8 flex flex-col items-start">
                <div class="flex mb-4">
                  <span class="text-yellow-400 text-2xl mr-1" v-for="i in 5" :key="i">★</span>
                </div>
                <h3 class="font-bold text-xl mb-4">Thank you FatForWeightLoss, you've nailed it!</h3>
                <p class="mb-6 text-gray-700">
                  Had been looking for a keto recipe book that was affordable, easy to follow and had the science embedded. Thank you FatForWeightLoss, you've nailed it!
                </p>
                <span class="font-bold text-gray-800 mt-auto">- Selina Miler</span>
              </div>
              <!-- Testimonial 3 -->
              <div class="bg-white rounded shadow p-8 flex flex-col items-start">
                <div class="flex mb-4">
                  <span class="text-yellow-400 text-2xl mr-1" v-for="i in 5" :key="i">★</span>
                </div>
                <h3 class="font-bold text-xl mb-4">The best cookbook I have seen for a while.</h3>
                <p class="mb-6 text-gray-700">
                  All the portions you need are shown with the before and after cooking photos, and the ingredients are really simple. After a long day at work this book is your number 1 friend if your interested in keto. Two thumbs up
                </p>
                <span class="font-bold text-gray-800 mt-auto">- Silvana Chudleigh</span>
              </div>
            </div>
          </div>
        </div>

        <!-- Products Included Section -->
        <div class="w-full bg-[#f3f6fa] py-16">
          <div class="max-w-7xl mx-auto px-4">
            <h2 class="text-4xl font-bold text-center mb-12 text-gray-800">Products Included In The Bundle</h2>
            <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-8 justify-items-center">
              <!-- 3 Ingredient Keto Cookbook -->
              <div class="flex flex-col items-center">
                <div class="w-48 h-56 rounded-xl shadow mb-4 overflow-hidden bg-white flex items-center justify-center">
                  <img src="@/assets/images/receipe-books/keto-receipe-book-1.png" alt="3 Ingredient Keto Cookbook" class="object-cover w-full h-full" />
                </div>
                <div class="font-bold text-lg text-center mb-2">3 Ingredient Keto<br />Cookbook</div>
                <div class="text-green-500 font-bold text-xl inline-block align-middle">$4.99</div>
                <span class="text-gray-400 font-semibold text-lg line-through ml-2 align-middle">$9.99</span>
              </div>
              <!-- Keto Recipes Everyone Will Actually Eat -->
              <div class="flex flex-col items-center">
                <div class="w-48 h-56 rounded-xl shadow mb-4 overflow-hidden bg-white flex items-center justify-center">
                  <img src="@/assets/images/receipe-books/keto-receipe-book-2.png" alt="Keto Recipes Everyone Will Actually Eat" class="object-cover w-full h-full" />
                </div>
                <div class="font-bold text-lg text-center mb-2">Keto Recipes<br />Everyone Will<br />Actually Eat</div>
                <div class="text-green-500 font-bold text-xl inline-block align-middle">$7.49</div>
                <span class="text-gray-400 font-semibold text-lg line-through ml-2 align-middle">$14.99</span>
              </div>
              <!-- Keto Bread Cookbook -->
              <div class="flex flex-col items-center">
                <div class="w-48 h-56 rounded-xl shadow mb-4 overflow-hidden bg-white flex items-center justify-center">
                  <img src="@/assets/images/receipe-books/keto-receipe-book-3.png" alt="Keto Bread Cookbook" class="object-cover w-full h-full" />
                </div>
                <div class="font-bold text-lg text-center mb-2">Keto Bread<br />Cookbook</div>
                <div class="text-green-500 font-bold text-xl inline-block align-middle">$4.99</div>
                <span class="text-gray-400 font-semibold text-lg line-through ml-2 align-middle">$9.99</span>
              </div>
              <!-- The Beginners Ketogenic Cookbook -->
              <div class="flex flex-col items-center">
                <div class="w-48 h-56 rounded-xl shadow mb-4 overflow-hidden bg-white flex items-center justify-center">
                  <img src="@/assets/images/receipe-books/keto-receipe-book-4.png" alt="The Beginners Ketogenic Cookbook" class="object-cover w-full h-full" />
                </div>
                <div class="font-bold text-lg text-center mb-2">The Beginners<br />Ketogenic Cookbook</div>
                <div class="text-green-500 font-bold text-xl inline-block align-middle">$7.49</div>
                <span class="text-gray-400 font-semibold text-lg line-through ml-2 align-middle">$14.99</span>
              </div>
              <!-- Keto Holiday Cookbook -->
              <div class="flex flex-col items-center">
                <div class="w-48 h-56 rounded-xl shadow mb-4 overflow-hidden bg-white flex items-center justify-center">
                  <img src="@/assets/images/receipe-books/keto-receipe-book-5.png" alt="Keto Holiday Cookbook" class="object-cover w-full h-full" />
                </div>
                <div class="font-bold text-lg text-center mb-2">Keto Holiday<br />Cookbook</div>
                <div class="text-green-500 font-bold text-xl inline-block align-middle">$4.99</div>
                <span class="text-gray-400 font-semibold text-lg line-through ml-2 align-middle">$9.99</span>
              </div>
            </div>
            <div class="flex justify-center mt-10">
              <button
                @click="navigateTo('https://fatforweightloss.thrivecart.com/cravings-ebook-bundle/')"
                class="bg-green-500 hover:bg-green-600 text-white font-bold text-xl px-10 py-4 rounded-full shadow transition-colors"
              >
                $30 Saving! Add To Cart Now
              </button>
            </div>
          </div>
        </div>

        <!-- expert section -->

        
    </main>
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