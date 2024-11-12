<template>
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
</template>
<style scoped>
.router-link-active {
  @apply bg-green-700 md:bg-transparent md:text-green-500;
}
</style>
