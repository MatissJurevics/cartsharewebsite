<template>
  <main class="bg-[#0F0F21] min-h-[100vh] w-[100vw] text-white/60 text-center">
    <div class="">
      <div
        class="rounded-full aspect-square w-2/3 border border-white/40 absolute left-1/2 -translate-x-[50%] top-0 -translate-y-1/2 mini-fade-in delay-0"
      >
        <span></span>
      </div>
      <div
        class="rounded-full aspect-square w-1/2 border border-white/40 absolute left-1/2 -translate-x-[50%] top-0 -translate-y-1/2 mini-fade-in delay-300 "
      >
        <span></span>
      </div>
      <div
        class="rounded-full aspect-square w-1/3 border-dashed border border-white/40 absolute left-1/2 -translate-x-[50%] top-0 -translate-y-1/2 mini-fade-in delay-500 "
      >
        <span></span>
      </div>
    </div>
    <section>
      <h1 class="mx-auto fade-in text-center text-4xl xl:text-5xl font-bold mt-8 ">
        Let Customers
        <span class="text-[#ff5470]">Buy with <br />their Friends</span>
      </h1>
      <h2 class="text-xl w-3/4 xl:w-1/2 mx-auto xl:text-2xl font-light mt-6 fade-in-second">
        Let your customers buy together in real time by adding items to the same cart
      </h2>
      <div class="flex justify-center mt-8 fade-in-second">
        <form
          class="launchlist-form"
          action="https://getlaunchlist.com/s/Wp1whM"
          method="POST"
        >
          <input
            class="input bg-transparent border-2 border-white/60 focus:border-white/80 mr-4"
            placeholder="Email"
            name="email"
            type="email"
          />
          <button
            class="btn border-none bg-[#ff5470] hover:bg-[#ff5470]/80 text-white"
            type="submit"
          >
            Join The Waitlist
          </button>
        </form>
      </div>
      <div
        class="mockup-window border-base-300 mt-32 border w-3/4 xl:w-1/3 aspect-video mx-auto bg-slate-700/60 fade-in-third"
      >
        <div
          class="border-base-300 flex justify-center border-t px-4 py-16 bg-slate-700 h-full"
        >
          Hello!
        </div>
      </div>
      <div
        class="w-1/3 h-[50px] bg-purple-500/15 blur-2xl mx-auto -z-10 rounded-full fade-in-third"
      >
        <span></span>
      </div>
    </section>
    <section class="fade-in-final mt-32">
      <div>
        <h1 class="mx-auto text-center text-5xl font-bold mt-8 tra">
          What Do <span class="text-[#ff5470]">We Do?</span>
        </h1>
        <h2 class="text-2xl font-light mt-6">
          By letting customers share their cart you:
        </h2>
      </div>
      <div class="py-12">
        <div
          class="max-w-6xl mx-auto grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8 text-center text-white px-4"
        >
          <!-- First Card -->
          <div class="flex flex-col items-center">
            <div class="bg-[#ff5470] rounded-full p-4 mb-4">
              <!-- Up Arrow Icon (SVG or Font Awesome) -->
              <svg
                class="w-10 h-10 md:w-12 md:h-12 text-white"
                fill="currentColor"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 24 24"
              >
                <path
                  d="M4 12l1.41 1.41L11 7.83V20h2V7.83l5.59 5.58L20 12l-8-8-8 8z"
                />
              </svg>
            </div>
            <h3 class="text-lg md:text-xl font-bold">Increase AOV</h3>
            <p class="text-sm md:text-base text-gray-400 mt-2 md:mt-4 w-3/4 xl:w-72">
              By letting customers share their cart with their friends, you can increase the average order value of each purchase.
            </p>
          </div>

          <!-- Second Card -->
          <div class="flex flex-col items-center">
            <div class="bg-[#ff5470] rounded-full p-4 mb-4">
              <!-- Cart Icon (SVG or Font Awesome) -->
               <img class="w-8 h-8 md:w-10 md:h-10 text-white" src="/public/cart.svg" alt="">
              <!-- <svg
                fill="currentColor"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 24 24"
              >
              <path d="M24 0C10.7 0 0 10.7 0 24S10.7 48 24 48l45.5 0c3.8 0 7.1 2.7 7.9 6.5l51.6 271c6.5 34 36.2 58.5 70.7 58.5L488 384c13.3 0 24-10.7 24-24s-10.7-24-24-24l-288.3 0c-11.5 0-21.4-8.2-23.6-19.5L170.7 288l288.5 0c32.6 0 61.1-21.8 69.5-53.3l41-152.3C576.6 57 557.4 32 531.1 32L360 32l0 102.1 23-23c9.4-9.4 24.6-9.4 33.9 0s9.4 24.6 0 33.9l-64 64c-9.4 9.4-24.6 9.4-33.9 0l-64-64c-9.4-9.4-9.4-24.6 0-33.9s24.6-9.4 33.9 0l23 23L312 32 120.1 32C111 12.8 91.6 0 69.5 0L24 0zM176 512a48 48 0 1 0 0-96 48 48 0 1 0 0 96zm336-48a48 48 0 1 0 -96 0 48 48 0 1 0 96 0z"/></svg>
           -->
            </div>
            <h3 class="text-lg md:text-xl font-bold">
              Reduce Cart Abandonment
            </h3>
            <p class="text-sm md:text-base text-gray-400 mt-2 md:mt-4 w-3/4 xl:w-72">
              When a customer shares their cart with a friend, they are more likely to complete the purchase due to social pressures.
            </p>
          </div>

          <!-- Third Card -->
          <div class="flex flex-col items-center">
            <div class="bg-[#ff5470] rounded-full p-4 mb-4">
              <!-- Group Icon (SVG or Font Awesome) -->
              <svg
                class="w-10 h-10 md:w-12 md:h-12 text-white"
                fill="currentColor"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 24 24"
              >
                <path
                  d="M4 12l1.41 1.41L11 7.83V20h2V7.83l5.59 5.58L20 12l-8-8-8 8z"
                />
              </svg>
            </div>
            <h3 class="text-lg md:text-xl font-bold">
              Simplify Group Purchases
            </h3>
            <p class="text-sm md:text-base text-gray-400 mt-2 md:mt-4 w-3/4 xl:w-72">
              Make group ordering go from a messy process of asking each other what they want in group chats to a simple click of a button.
            </p>
          </div>
        </div>
      </div>
    </section>
    <section class="fade-in-final">
      <div class="py-12 px-4">
        <div class="max-w-6xl mx-auto flex flex-col lg:flex-row items-center">
          <!-- Left Section: Text Content -->
          <div
            class="text-white lg:w-1/2 flex flex-col text-center xl:text-left justify-start align-top"
          >
            <h2 class="text-3xl md:text-4xl lg:text-5xl font-bold">
              See CartShare
              <span
                class="text-transparent text-[#ff5470]"
              >
                In Action
              </span>
            </h2>
            <p class="mt-4 text-gray-400 text-base md:text-lg">
              Here you can see a demo of CartShare in action. If you have any questions or would like to learn more, feel free to book a call with us.
            </p>
            <div class="mt-8">
              <a
                href="https://calendly.com/fuller-liam07/cartshare-intro-demo-liam-fuller"
                class="btn border-none bg-[#ff5470] hover:bg-[#ff5470]/80 text-white cursor-pointer"
              >
                Book a Call
              </a>
            </div>
          </div>

          <!-- Right Section: Image Content -->
          <div
            class="bg-gray-200 w-full lg:w-1/2 mt-8 lg:mt-0 flex justify-center items-center"
          >
            <!-- Placeholder for Image -->
            <iframe class="aspect-video" width="100%" height="100%" src="https://www.youtube.com/embed/5zqPnAZSZc8" title="CartShare Demo" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
          </div>
        </div>
      </div>
    </section>
    <section class="fade-in-final">
      <div>
        <h1 class="mx-auto text-center text-5xl font-bold mt-8 tra">
          What Do <span class="text-[#ff5470]">Others Think?</span>
        </h1>
        <h2 class="text-2xl font-light mt-6">
          Here's what other people think about Cartshare
        </h2>
      </div>
      <div class="py-12">
        <div
          class="max-w-6xl mx-auto grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8 text-center text-white px-4"
        >
          <!-- First Card -->
          <div class="flex flex-col items-center">
            <div class=" rounded-full mb-4 overflow-hidden">
              <!-- Up Arrow Icon (SVG or Font Awesome) -->
              <img src="/public/shopifyceo.png" class="w-32" alt="">
            </div>
            <h3 class="text-lg md:text-xl font-bold">Tobias Lütke <br><span class="text-white/60 font-light">CEO, Shopify</span></h3>
            <p class="text-md md:text-base text-gray-400 mt-2 md:mt-4">
              "Love it"
            </p>
          </div>

          <!-- Second Card -->
          <div class="flex flex-col items-center">
            <div class=" rounded-full mb-4 overflow-hidden">
              <!-- Up Arrow Icon (SVG or Font Awesome) -->
              <img src="/public/shopifyceo.png" class="w-32" alt="">
            </div>
            <h3 class="text-lg md:text-xl font-bold">Tobias Lütke <br><span class="text-white/60 font-light">CEO, Shopify</span></h3>
            <p class="text-md md:text-base text-gray-400 mt-2 md:mt-4">
              "Love it"
            </p>
          </div>

          <!-- Third Card -->
          <div class="flex flex-col items-center">
            <div class=" rounded-full mb-4 overflow-hidden">
              <!-- Up Arrow Icon (SVG or Font Awesome) -->
              <img src="/public/shopifyceo.png" class="w-32" alt="">
            </div>
            <h3 class="text-lg md:text-xl font-bold">Tobias Lütke <br><span class="text-white/60 font-light">CEO, Shopify</span></h3>
            <p class="text-md md:text-base text-gray-400 mt-2 md:mt-4">
              "Love it"
            </p>
          </div>
        </div>
      </div>
    </section>
    <section class="my-32 fade-in-final">
        <div class="max-w-6xl w-full mx-auto">
        <div class="flex flex-col md:flex-row items-center justify-between gap-8">
            <div class="w-2/3 md:w-1/2 text-center xl:text-left">
                <h1 class="text-4xl md:text-5xl font-bold mb-4">
                    Sign up To <span class="text-[#ff5470]">Our Waitlist</span>
                </h1>
                <p class="text-gray-400 mb-6 text-lg">
                    Join our waitlist to be the first to receive updates on our journey and be the first to know when we launch!
                </p>
            </div>
            <div class="md:w-1/2 w-full max-w-md">
                <div class="bg-white/10 p-6 rounded-lg w-3/4 lg:w-full mx-auto">
                    <form class="launchlist-form" action="https://getlaunchlist.com/s/Wp1whM" method="POST">
                        
                            <input name="email" type="email" placeholder="Email" class="w-full bg-gray-700 text-white rounded px-3 py-2 mb-4 focus:outline-none focus:bg-gray-600">
                        
                        <button type="submit" class="w-full bg-[#ff5470] text-white rounded py-2 hover:[#ff5470]/80 transition duration-300">
                            Join The Waitlist
                        </button>
                    </form>
                </div>
                
            </div>
        </div>
    </div>
    </section>
  </main>
</template>

<style>
@keyframes fadeIn {
  from {
    transform: translateY(-50px);
    opacity: 0;
  }
  to {
    transform: translateY(0);
    opacity: 1;
  }
}

@keyframes fadeInNoMove {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
    
}

.mini-fade-in {
    opacity: 0;
    animation: fadeInNoMove 800ms ease-in-out forwards;
}

.fade-in {
  opacity: 0;
  animation: fadeIn 500ms ease-in-out 500ms forwards;
}
.fade-in-second {
  opacity: 0;
  animation: fadeIn 500ms ease-in-out 750ms forwards;
}
.fade-in-third {
  opacity: 0;
  animation: fadeIn 700ms ease-in-out 1000ms forwards;
}
.fade-in-final {
    opacity: 0;
    animation: fadeIn 700ms ease-in-out 1700ms forwards;
}
</style>
