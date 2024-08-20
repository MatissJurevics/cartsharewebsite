<template>
  <main class="min-h-[100vh] px-6 md:px-20">
    <h1 class="text-5xl font-bold text-[#ff5470] mt-20">Pricing</h1>
    <p class="text-lg mt-8 w-3/4 xl:w-1/3 font-light">
      The pricing model for cartshare consists of two parts, a monthly
      subscription and a percentage of an invited users order value. We
      currently have 3 tiers.
    </p>
    <div class="flex flex-col gap-8 lg:flex-row justify-around mt-24">
      <div class="card card-compact bg-gray-900 w-full 'g:w-96 shadow-xl">
        
        <div class="card-body">
          <h2 class="card-title">Basic Tier</h2>
          <div class="divider"></div>

          <p class="font-bold">€14.95 per month & 3.5% of invited order*</p>

          <p>Perfect for small store that want to test to see if cartshare works for them.</p>
          
        </div>
      </div>
      <div class="card card-compact bg-gray-900 w-full 'g:w-96 shadow-xl">
        
        <div class="card-body">
          <h2 class="card-title">Plus Tier</h2>
          <div class="divider"></div>

          <p class="font-bold">€24.95 per month & 2.5% of invited order*</p>
          <p>Perfect for most small to medium sized stores.</p>
          
        </div>
      </div>
      <div class="card card-compact bg-gray-900 w-full 'g:w-96 shadow-xl">
        <div class="card-body">
          <h2 class="card-title">Premium</h2>
          <div class="divider"></div>
          <p class="font-bold">€49.95 per month & 2% of invited order</p>
            <p>Perfect for larger stores that have a high volume of orders and low margins.</p>
        </div>
      </div>
    </div>
    <p class="text-md mt-8 w-72 lg:ml-auto font-light">
        * The percentage of the invited order is the value of the cart of all invited users which were brought to the store as a result of cartshare.
    </p>
  </main>
</template>
