<template>
  <div id="app">
    <h1 class="title text-white text-center rounded m-5 p-3"><img src="./assets/logo.png" alt="">  Calculator</h1>
    <calculator></calculator>
  </div>
</template>

<script>
import Calculator from './components/Calculator.vue'

export default {
  name: 'App',
  components: {
    Calculator
  }
}
</script>

<style>
  body {
    background: #31475e !important;
  }
  img {
    width: auto;
    height: auto;
    max-width: 50px;
    max-height: 50px;
  }
</style>
