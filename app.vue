<template>
  <Navbar />
  <div
    class="h-full container mx-auto max-sm:px-4 md:px-0 py-8 grid md:grid-cols-6 md:items-baseline xl:max-w-7xl md:max-w-4xl"
  >
    <div
      class="flex items-center md:col-start-1 md:col-end-3 sm:col-span-4"
    >
      <i class="squid-craft-icon-news icon"></i>
      <h3 class="title">Últimas noticias</h3>
    </div>
    <div class="md:col-end-7 md:col-span-2">
      <div class="flex items-center">
        <i class="squid-craft-icon-twitter icon"></i>
        <h3 class="title">Últimos tweets</h3>
      </div>
      <blockquote
        class="twitter-tweet"
        data-lang="es"
        data-theme="dark"
        data-chrome="transparent nofooter noborders noheader noscrollbar"
      >
        <p lang="es" dir="ltr">
          Nos vemos el 21 y 28 de febrero
          <a
            href="https://twitter.com/hashtag/Squidcraft2?src=hash&amp;ref_src=twsrc%5Etfw"
            >#Squidcraft2</a
          >
          🦑
          <a href="https://t.co/4UvZtPJa2t"
            >pic.twitter.com/4UvZtPJa2t</a
          >
        </p>
        &mdash; SQUID CRAFT 2 (@SquidCraftGames)
        <a
          href="https://twitter.com/SquidCraftGames/status/1624893224689999873?ref_src=twsrc%5Etfw"
          >12 de febrero de 2023</a
        >
      </blockquote>
    </div>
  </div>
  <Footer />
</template>

<script setup>
useHead({
  title: 'Squid Craft Games',
  script: [
    {
      src: 'https://platform.twitter.com/widgets.js',
      async: true
    }
  ]
})
</script>
