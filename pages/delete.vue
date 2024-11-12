<template>
  <div class="py-10">
    <div class="container mx-auto px-8">
      <h1 class="text-5xl my-4">Delete Your Account</h1>

      <div
        class="p-4 mb-4 text-sm rounded-lg bg-slate-900 text-red-400"
        role="alert"
      >
        <span class="font-medium">Danger alert!</span> This will remove all your
        tracked shows, episodes, lists and movies from Cloud. You can create a
        new account at any time.
      </div>
      <p class="mb-4">
        To delete your Series Addict account, you will need to delete your
        associated trakt.tv account, as Series Addict relies on trakt.tv to
        store your progress and authenticate your login. Please follow these
        steps to delete your trakt.tv account:
      </p>
      <p class="mb-2">
        1. Sign in to your trakt.tv account by visiting
        <NuxtLink
          class="text-green-500 hover:underline"
          to="https://trakt.tv/auth/signin"
          >https://trakt.tv/auth/signin</NuxtLink
        >.
      </p>
      <p class="mb-2">
        2. Once signed in, go to your account settings by visiting
        <NuxtLink
          class="text-green-500 hover:underline"
          to="https://trakt.tv/settings"
          >https://trakt.tv/settings</NuxtLink
        >.
      </p>
      <p class="mb-2">
        3. In the settings menu, locate the “Delete Account” button and click on
        it.
      </p>
      <p class="mb-2">
        4. A confirmation message will appear. Please review the details and
        follow the instructions provided to complete the account deletion
        process.
      </p>
    </div>
  </div>
</template>
