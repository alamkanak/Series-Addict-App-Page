<template>
  <div class="container mx-auto my-10">
    <div class="grid grid-cols-1 md:grid-cols-2">
      <div class="w-full place-content-center mb-30">
        <NuxtImg src="launcher_icon_5_adaptive.png" />
        <h1 class="text-5xl mb-4">Series Addict</h1>
        <h2 class="text-xl mb-6">
          Track your favorite TV shows. Be up to date about new & upcoming TV
          episodes.
        </h2>
        <ul class="mb-8">
          <li>★ Mark episodes as watched</li>
          <li>★ View TV schedules of your favorite shows in calendar</li>
          <li>★ Share what you're watching with your friends</li>
          <li>★ Add widgets to your home screen</li>
          <li>★ Get notified when new episodes air</li>
        </ul>
        <NuxtLink
          to="https://play.google.com/store/apps/details?id=com.alamkanak.seriesaddict"
        >
          <NuxtImg class="w-56" src="google-play-badge.png" />
        </NuxtLink>

      
      </div>
      <NuxtImg class="w-full" src="/screen3.png" />
    </div>
  </div>
</template>
