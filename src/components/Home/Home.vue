<script>
import { defineComponent } from 'vue'

export default defineComponent({
  setup() { },
})
</script>

<template>
  <div class="presentation">
    <h3>Bonjour</h3>
    <h3>Je suis Renaud</h3>
    <h3>Développeur Web</h3>
    <p class="descriptionPresentation">Développeur fullstack</p>
    <router-link to="/Contact" class="btnContact">Contacter - moi !</router-link>
  </div>    
</template>

<style src="./Home.css" scoped> </style>