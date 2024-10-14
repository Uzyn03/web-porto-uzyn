<script setup>
defineProps({
  pesanGue: {
    type: String,
    required: true,
  },
});
</script>

<template>
  <p class="font-semibold text-orange-500 text-xl bg-sky-600">{{ pesanGue }}</p>
</template>
