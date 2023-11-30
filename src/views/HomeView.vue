<script setup lang="ts">
import TheWelcome from '../components/TheWelcome.vue'

import '@asko/vue/dist/style.css'
import { AsButton, AsAlert, AsTag } from '@asko/vue'
</script>

<template>
  <main>
    <div class="flex flex-col gap-4 my-8">
      <AsButton class="w-fit">Dette er en ASKO Button!!!</AsButton>
      <AsAlert>Og dette er en ASKO Alert!!!!!!!!</AsAlert>
      <div class="flex gap-2">
        <AsTag color="green">Og masse</AsTag>
        <AsTag color="blue">ASKO</AsTag>
        <AsTag color="yellow">Tags!!!</AsTag>
      </div>
    </div>
    <TheWelcome />
  </main>
</template>
