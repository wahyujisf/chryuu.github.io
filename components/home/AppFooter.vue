<template>
  <footer class="fixed bottom-0 bg-white p-4 w-full">
    <div class="flex flex-row gap-4 justify-center">
      <nuxt-link to="/" class="px-4 flex flex-col items-center">
        <svg
          class="h-6 w-6 stroke-2 stroke-current fill"
          fill="none"
          viewBox="0 0 24 24"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"
          />
        </svg>
        <span class="text-sm">Home</span>
      </nuxt-link>
      <nuxt-link to="/blog" class="px-4 flex flex-col items-center">
        <svg
          class="h-6 w-6 stroke-2 stroke-current fill"
          fill="none"
          viewBox="0 0 24 24"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"
          />
        </svg>
        <span class="text-sm">Article</span>
      </nuxt-link>
      <nuxt-link to="/" class="px-4 flex flex-col items-center">
        <svg
          class="h-6 w-6 stroke-2 stroke-current fill"
          fill="none"
          viewBox="0 0 24 24"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M7 21h10a2 2 0 002-2V9.414a1 1 0 00-.293-.707l-5.414-5.414A1 1 0 0012.586 3H7a2 2 0 00-2 2v14a2 2 0 002 2z"
          />
        </svg>
        <span class="text-sm">News</span>
      </nuxt-link>
      <nuxt-link to="/about" class="px-4 flex flex-col items-center">
        <svg
          class="h-6 w-6 stroke-2 stroke-current fill"
          fill="none"
          viewBox="0 0 24 24"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z"
          />
        </svg>
        <span class="text-sm">About</span>
      </nuxt-link>
    </div>
  </footer>
</template>
