<template>
  <button @click="open = true" class="btn btn-primary">
    Confirmer l'achat
  </button>
  <div v-if="open" class="calc">
    <div class="modal-container">
      <h3>Confirmation de votre commande</h3>
      <ul>
        <li>Du contenu</li>
        <li>Du contenu</li>
        <li>Du contenu</li>
      </ul>
    </div>
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue';

const open = ref(false);
</script>

<style lang="scss">
@import './assets/scss/base.scss';
</style>
