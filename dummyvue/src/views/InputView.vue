<script setup lang="ts">
  import { ref } from 'vue';
  const textboxtext = ref("")
</script>

<!-- https://bulma.io/documentation/elements/box/ -->
<!-- https://bulma.io/documentation/helpers/color-helpers/ -->
<template>
  <div class="box">
    <div class="box">
      {{textboxtext}}
    </div>
    <input class="input" type="text" placeholder="input" v-model="textboxtext">
  </div>
</template>
