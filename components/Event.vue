<template>
  <div class="flex items-center py-1">
    <i
      class="icon-event"
      :class="`squid-craft-icon-${type} ${returnColor()}`"
    ></i>
    <span class="text-light">
      {{ text }}
    </span>
  </div>
</template>

<script setup>
const props = defineProps({
  text: {
    type: String,
    required: true
  },
  type: {
    type: String,
    required: true
  }
})

const returnColor = () => {
  const colors = {
    timer: 'text-yellow-400',
    skull: 'text-red-400',
    'money-up': 'text-green-500',
    calendar: 'text-green-500'
  }
  return colors[props.type]
}

returnColor()
</script>
