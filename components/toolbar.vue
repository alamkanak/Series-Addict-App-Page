<template>
  <nav class="border-gray-200 bg-gray-900">
    <div
      class="max-w-screen-xl flex flex-wrap items-center justify-between mx-auto p-4"
    >
      <NuxtLink to="/" class="flex items-center space-x-3 rtl:space-x-reverse">
        <NuxtImg
          src="/launcher_icon_5_adaptive.png"
          class="h-8"
          alt="Series Addict Logo"
        />
        <span
          class="self-center text-2xl font-semibold whitespace-nowrap text-white"
          >Series Addict</span
        >
      </NuxtLink>
      <button
        data-collapse-toggle="navbar-default"
        type="button"
        class="inline-flex items-center p-2 w-10 h-10 justify-center text-sm rounded-lg md:hidden focus:outline-none focus:ring-2 text-gray-400 hover:bg-gray-700 focus:ring-gray-600"
        aria-controls="navbar-default"
        aria-expanded="false"
      >
        <span class="sr-only">Open main menu</span>
        <svg
          class="w-5 h-5"
          aria-hidden="true"
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 17 14"
        >
          <path
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M1 1h15M1 7h15M1 13h15"
          />
        </svg>
      </button>
      <div class="hidden w-full md:block md:w-auto" id="navbar-default">
        <ul
          class="font-medium flex flex-col p-4 md:p-0 mt-4 border rounded-lg md:flex-row md:space-x-8 rtl:space-x-reverse md:mt-0 md:border-0 bg-gray-800 md:bg-gray-900 border-gray-700"
        >
          <li>
            <NuxtLink
              to="/"
              class="block py-2 px-3 rounded md:border-0 md:p-0 text-white md:hover:text-green-500 hover:bg-gray-700 hover:text-white md:hover:bg-transparent"
              aria-current="page"
              >Home</NuxtLink
            >
          </li>
          <li>
            <NuxtLink
              to="/privacy"
              class="block py-2 px-3 rounded md:border-0 md:p-0 text-white md:hover:text-green-500 hover:bg-gray-700 hover:text-white md:hover:bg-transparent"
              >Privacy Policy</NuxtLink
            >
          </li>
          <li>
            <NuxtLink
              to="/delete"
              class="block py-2 px-3 rounded md:border-0 md:p-0 text-white md:hover:text-green-500 hover:bg-gray-700 hover:text-white md:hover:bg-transparent"
              >Delete Account</NuxtLink
            >
          </li>
          <li>
            <NuxtLink
              to="mailto:alam.kanak@gmail.com"
              class="block py-2 px-3 rounded md:border-0 md:p-0 text-white md:hover:text-green-500 hover:bg-gray-700 hover:text-white md:hover:bg-transparent"
              >Contact Us</NuxtLink
            >
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>
<style scoped>
.router-link-active {
  @apply bg-green-700 md:bg-transparent md:text-green-500;
}
</style>
