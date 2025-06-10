<template>
  <div class="min-h-screen bg-white">
    <main class="container mx-auto px-4 py-8">
      <!-- Hero Section -->
      <section class="text-center mb-12">
        <h1 class="text-4xl font-bold mb-4">The free resources are available below👍</h1>
        <h2 class="text-2xl mb-8">Feel free to grab as many free downloads as you like!</h2>
      </section>

      <!-- Resources Grid -->
      <section class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 mb-12">
        <div class="resource-card">
          <h3 class="text-xl font-semibold mb-2">Free Example Day Of Eating Meal Plans</h3>
          <button class="bg-blue-600 text-white px-6 py-2 rounded-lg">Download Now</button>
        </div>
        <div class="resource-card">
          <h3 class="text-xl font-semibold mb-2">Free Keto Meal Plans</h3>
          <button class="bg-blue-600 text-white px-6 py-2 rounded-lg">Download Now</button>
        </div>
        <div class="resource-card">
          <h3 class="text-xl font-semibold mb-2">Free Keto Recipe Cookbooks</h3>
          <button class="bg-blue-600 text-white px-6 py-2 rounded-lg">Download Now</button>
        </div>
        <div class="resource-card">
          <h3 class="text-xl font-semibold mb-2">Free Keto Resources</h3>
          <button class="bg-blue-600 text-white px-6 py-2 rounded-lg">Download Now</button>
        </div>
      </section>

      <!-- Keto Bundle Section -->
      <section class="text-center mb-12">
        <h2 class="text-3xl font-bold mb-4">Need More Inspiration? 👇</h2>
        <div class="max-w-2xl mx-auto">
          <p class="text-lg mb-4">
            With <strong>260+ simple recipes</strong> with easy to find ingredients, you'll always have the power to eat healthy, delicious meals, even when the cravings strike.
          </p>
        </div>
      </section>

      <!-- Bundle Features -->
      <section class="bg-gray-100 p-8 rounded-lg mb-12">
        <h2 class="text-3xl font-bold text-center mb-6">Keto Cravings Bundle (50% OFF)</h2>
        <ul class="max-w-2xl mx-auto space-y-4">
          <li>✓ Are you struggling to find recipes that are easy, and don't require hard to find ingredients?</li>
          <li>✓ Are you finding it tough to stay inspired and committed to your health with the same recipes every day?</li>
          <li>✓ Wouldn't you like to learn how to easily cook meals for breakfast, lunch and dinner that aren't just bacon, cheese and butter?</li>
        </ul>
        <div class="text-center mt-8">
          <button class="bg-green-600 text-white px-8 py-3 rounded-lg text-xl">YES! Add to cart now</button>
        </div>
      </section>
    </main>
  </div>
</template>

<script setup lang="ts">
// Component logic will go here
</script>

<style scoped>
.resource-card {
  @apply bg-gray-50 p-6 rounded-lg text-center shadow-md hover:shadow-lg transition-shadow;
}
</style> 