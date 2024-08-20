<template>

    <div class="drawer bg-[#0F0F21] text-white/60">
  <input id="my-drawer-3" type="checkbox" class="drawer-toggle" />
  <div class="drawer-content flex flex-col">
    <!-- Navbar -->
    <div class="navbar bg-none w-full px-6 md:px-16 z-10">
      <div class="flex-none lg:hidden">
        <label for="my-drawer-3" aria-label="open sidebar" class="btn btn-square btn-ghost">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            class="inline-block h-6 w-6 stroke-current">
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M4 6h16M4 12h16M4 18h16"></path>
          </svg>
        </label>
      </div>
      <nuxt-link to="/" class="mx-2 flex-1 px-2 navbar-center md:navbar-start text-2xl font-bold">CartShare</nuxt-link>
      <div class="hidden flex-none navbar-center lg:block">
        <ul class="menu menu-horizontal translate-x-1/2 z-10">
          <!-- Navbar menu content here -->
          <li class="cursor-pointer"><nuxt-link to="/" class="cursor-pointer z-20">Home</nuxt-link></li>
          <li><nuxt-link to="/about" class="cursor-pointer z-20">About Us</nuxt-link></li>
          <li><nuxt-link to="/pricing" class="cursor-pointer z-20">Pricing</nuxt-link></li>
        </ul>
      </div>
      <div class="navbar-end">
        <a href="https://calendly.com/fuller-liam07/cartshare-intro-demo-liam-fuller" class="btn bg-[#ff5470] hover:bg-[#ff5470]/80 outline-none border-none text-white cursor-pointer hidden md:block">Book a Call</a>
      </div>
    </div>
<slot />
    <footer class="footer mx-32 my-8">
        <nav>
            <h6 class="footer-title">Pages</h6>
            <nuxt-link to="/" class="link link-hover">Home</nuxt-link>
            <nuxt-link to="/about" class="link link-hover">About Us</nuxt-link>
            <nuxt-link to="/pricing" class="link link-hover">Pricing</nuxt-link>
        </nav>
    </footer>
  </div>
  <div class="drawer-side z-30">
    <label for="my-drawer-3" aria-label="close sidebar" class="drawer-overlay"></label>
    <ul class="menu min-h-full w-80 p-4 bg-gray-800">
      <!-- Sidebar content here -->
      <li class="cursor-pointer"><nuxt-link to="/" class="cursor-pointer z-20">Home</nuxt-link></li>
          <li><nuxt-link to="/about" class="cursor-pointer z-20">About Us</nuxt-link></li>
          <li><nuxt-link to="/pricing" class="cursor-pointer z-20">Pricing</nuxt-link></li>
    </ul>
  </div>
</div>
</template>