<script setup lang="ts">
import { computed, ref } from "vue";

const count = ref(0);
const double = computed(() => count.value * 2);
</script>

<template>
  <div class="flex flex-col items-center gap-2">
    <p>Count: {{ count }}</p>
    <p>Double: {{ double }}</p>
    <button
      @click="() => count++"
      class="rounded-xl bg-emerald-900 px-12 py-2 transition-colors hover:bg-emerald-700 active:bg-emerald-800"
    >
      <slot></slot>
    </button>
  </div>
</template>
