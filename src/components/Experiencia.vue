<template>
  <div class="q-mb-lg">
    <div class="text-subtitle1 text-weight-bold q-mb-xs">{{ title }}</div>
    <div class="text-caption text-grey-7 q-mb-sm">{{ dates }}</div>
    <p class="text-body2" v-html="description"></p>
    
    <div v-if="linkUrl" class="q-mt-sm">
      <a :href="linkUrl" target="_blank" class="text-primary text-weight-medium">{{ linkText }}</a>
    </div>
  </div>
</template>

<script setup>
import { defineProps } from 'vue';

defineProps({
  title: {
    type: String,
    required: true
  },
  dates: {
    type: String,
    required: true
  },
  description: {
    type: String,
    required: true
  },
  linkUrl: {
    type: String,
    default: ''
  },
  linkText: {
    type: String,
    default: 'Ver Enlace'
  }
});
</script>