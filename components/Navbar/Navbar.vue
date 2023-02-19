<template>
  <header
    class="sticky top-0 z-40 w-full backdrop-blur shadow-sm py-4 px-4 m-auto"
  >
    <div class="max-w-7xl container relative flex items-center justify-center">
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
  </header>
</template>
