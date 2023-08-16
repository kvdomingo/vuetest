<script setup>
import CounterButton from "@/components/CounterButton.vue";
</script>

<template>
  <main
    class="flex h-screen w-full flex-col items-center justify-center gap-4 bg-gradient-to-b from-emerald-900 to-emerald-950"
  >
    <h1>Welcome, Vue!</h1>
    <CounterButton>count!</CounterButton>
  </main>
</template>

<style scoped>
h1 {
  font-size: theme(fontSize.4xl);
}

h2 {
  font-size: theme(fontSize.3xl);
}

h3 {
  font-size: theme(fontSize.2xl);
}

h4 {
  font-size: theme(fontSize.xl);
}

h5 {
  font-size: theme(fontSize.lg);
}

a {
  color: theme(colors.sky.300);
}
</style>
