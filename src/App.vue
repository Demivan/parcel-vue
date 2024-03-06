<script setup lang="ts">
import type { ExternalProps } from './types';

defineProps<ExternalProps>();
</script>

<template>
  <div>
    <h1>{{ externalProp }}</h1>
  </div>
</template>
