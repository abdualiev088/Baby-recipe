<template>
  <div class="min-h-screen bg-[#0d0d0f] text-white p-6 font-sans selection:bg-cyan-500/30">
    
    <div class="max-w-[140px] mx-auto grid grid-cols-1 lg:grid-cols-12 gap-6">
      
      <Sidebar class="lg:col-span-3" />
      <div class="lg:col-span-9">
        <slot />
        <h1>sdad</h1>
      </div>

    </div>
  </div>
</template>