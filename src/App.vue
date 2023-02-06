<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Hello Vue 3 + Vite" />
</template>

<script setup>
import HelloWorld from './components/HelloWorld.vue'

// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/script-setup-2/active-rfcs/0000-script-setup.md
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.wrapper {
  width: 400px;
  border: 4px solid green;
  display: inline-flex;
}

.image{
  width: 100%;
}

.header {
  text-align: center;
  font-wieght: bold;
  font-size: 2rem;
}

.header h3,
 header h4 {
  margin: 18px;
}

.details {
  margin-left: 24px;
  padding: 10px;
}
.details summary {
  font-size: 25px;
  font-weight: bold;
}

.buttons button:focus,
.buttons button:hover {
  background-color: rgba(50, 0, 200, .5);
}

.buttons button:active {
  background-color: rgba(200, 0, 50, .5);
}

.buttons {
  display: block;
}

button {
  padding: 15px;
  font-size: 32px;
  display: block;
}

@media only screen and (max-width: 600px) {
  .wrapper {
    
   background-color: pink;
  }
}

@media only screen and (max-width: 1200px) {
  .wrapper {
    
   background-color: orange;
  }
}

@media only screen and (max-width: 425px) {
  .wrapper {
    
   font-size: 1rem;
   font-wieght: normal;
  }
  .details {
    display: none;
  }
}


</style>
