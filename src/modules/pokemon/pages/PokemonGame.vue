<template>
  <div v-if="false" class="flex flex-col justify-center items-center w-screen h-screen">
    <h1 class="text-3xl">Please wait</h1>
    <h3 class="animate-pulse">Loading Pokemons</h3>
  </div>

  <div class="flex flex-col justify-center items-center w-screen h-screen">
    <h1 class="m-5">Who is this Pokemon?</h1>

    <PokemonPicture />
    <PokemonOptions />
  </div>
</template>

<script setup lang="ts">
import PokemonPicture from '../components/PokemonPicture.vue';
import PokemonOptions from '../components/PokemonOptions.vue';
</script>
