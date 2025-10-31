<template>
  <div class="row items-center q-mb-md">
    <q-icon :name="icon" size="28px" color="grey-8" class="q-mr-sm" />
    <span class="text-h5 text-weight-medium text-grey-9">{{ title }}</span>
  </div>
</template>

<script setup>
import { defineProps } from 'vue';

defineProps({
  title: {
    type: String,
    required: true
  },
  icon: {
    type: String,
    default: 'star' // Icono por defecto de Quasar/Material Icons
  }
});
</script>