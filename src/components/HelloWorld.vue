<template>
  <h1>{{ msg }}</h1>

  <p>
    <a href="https://vitejs.dev/guide/features.html" target="_blank">
      Vite Documentation
    </a>
    |
    <a href="https://v3.vuejs.org/" target="_blank">Vue 3 Documentation</a>
  </p>

  <button type="button" @click="state.count++">count is: {{ state.count }}</button>
  <p>
    Edit
    <code>components/HelloWorld.vue</code> to test hot module replacement.
  </p>

<div class="buttons">
<button data-duplicate-btn>Duplicate
<button data-delete-btn>Delete last card
<button data-title-btn>Change Title
<button data-toggle-btn>Toggle 
Details</button>
  
</div>

<div class="wrapper">
  <div class="container">
  <img class="image" src="https://media.discordapp.net/attachments/963095262363017246/1020131830323744788/unknown.png?width=468&height=468"/>
  
  <div class="header">
<h3>Nick Giacobe</h3>
<h4>God of IST</h4>
    </div>
    <div>
    <details class="details">
      <summary>Details</summary>
        <div>
          Professor Giacobe may look like a simple man but perceptions can be misleading. Underneath the facade of a simple college of IST professor lies the holiness of an <b>IST GOD</b>!
      </div>
    </details>
 <div>


</template>

<script setup>
import { defineProps, reactive } from 'vue'

defineProps({
  msg: String
})

const state = reactive({ count: 0 })
</script>

<style scoped>
a {
  color: #42b983;
}
</style>
