<template>
  <nav class="w-full flex items-center justify-between px-12 py-4">
    <div class="logo text-base shrink-0">
      Baby <span class="italic font-normal">nutrition</span>
    </div>

    <div class="flex items-center gap-6 w-full justify-center">
      <NuxtLink to="/" class="flex items-center gap-1.5 text-sm text-[#2A2230] hover:opacity-70 transition-opacity">
        <img src="../assets/icons/Home.png" alt="Home" class="w-4 h-4" />
        Home
      </NuxtLink>
      <NuxtLink to="/about" class="flex items-center gap-1.5 text-sm text-[#2A2230] hover:opacity-70 transition-opacity">
        <img src="../assets/icons/Info.png" alt="About" class="w-4 h-4" />
        About us
      </NuxtLink>
    </div>

    <div class="shrink-0">
      <LanguageSwitcher />
    </div>
  </nav>
</template>
