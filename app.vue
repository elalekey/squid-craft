<template>
  <Navbar />
  <main class="main-content">
    <div class="md:col-start-1 md:col-end-3 sm:col-span-4">
      <h3 class="title">Últimos eventos</h3>
      <div class="pt-2 pb-2">
        <Event
          v-for="({ type, text }, index) in events"
          :key="`event-${index}`"
          :type="type"
          :text="text"
        />
      </div>
      <h3 class="title lg:mt-8">Jugadores destacados</h3>
      <CardPlayer />
    </div>
    <div class="md:col-end-7 md:col-span-2 max-sm:mt-8">
      <h3 class="title">Últimos tweets</h3>
      <Tweets />
    </div>
  </main>
  <Footer />
</template>

<script setup>
const events = ref([
  {
    type: 'timer',
    text: 'Ha iniciado la prueba #1'
  },
  {
    type: 'skull',
    text: 'Anonimo ha sido eliminado'
  },
  {
    type: 'skull',
    text: 'Anonimo ha sido eliminado'
  },
  {
    type: 'skull',
    text: 'Anonimo ha sido eliminado'
  },
  {
    type: 'skull',
    text: 'Anonimo ha sido eliminado'
  },
  {
    type: 'money-up',
    text: 'El premio ha aumentado a 500.000$'
  },
  {
    type: 'calendar',
    text: 'El día 1 ha finalizado'
  }
])
</script>
