<template>
  <div class="header border-b-1 border-slate-500/20">
    <div class="max-w-7xl mx-auto">
      <div
        class="py-4 border-b border-slate-900/10 lg:border-0 dark:border-slate-300/10 lg:mx-0"
      >
        <div class="relative flex items-center">
          <div>Squid Craft Games</div>
          <div class="flex items-center ml-auto">
            <div class="grid grid-flow-col auto-cols-max gap-4">
              <NuxtLink to="/">
                <i class="icon-hover squid-craft-icon-home"></i>
              </NuxtLink>
              <NuxtLink to="/streamers">
                <i class="icon-hover squid-craft-icon-streamers"></i>
              </NuxtLink>
              <NuxtLink to="/jugadores">
                <i class="icon-hover squid-craft-icon-list"></i>
              </NuxtLink>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
