<template>
  <div class="foot bg-gradient-to-b from-red-500 via-orange-600 to-orange-500">
    <div
      class="container md:px-6 py-2 md:mx-auto flex items-center sm:flex-row flex-col"
    >
      <a
        class="flex title-font font-medium items-center md:justify-start justify-center text-gray-900"
      >
        <img
          src="../static/logo.svg"
          class="dynamic text-white p-2 bg-gradient-to-l from-orange-400 to-red-400"
        />
        <span class="ml-2 text-base md:text-xl">Aestas Flores | 2020</span>
      </a>
      <p class="text-xs md:text-sm text-gray-300 sm:ml-2 sm:mt-0 mt-4">
        — Made by
        <a
          href="https://github.com/kaguwomin"
          rel="noopener noreferrer"
          class="text-gray-900 hover:underline"
          target="_blank"
          >@kaguwomin</a
        >
      </p>
    </div>
  </div>
</template>

<style>
.foot {
  padding-top: 8vh;
}

.dynamic {
  transition: border-radius 0.2s;
  border-radius: 100%;
  width: 42px;
  height: 42px;
}

.dynamic:hover {
  border-radius: 6px;
}
</style>
