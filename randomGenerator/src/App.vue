<template>
<div id="app">
  <div class="container">
  <div class="row">
    <div class="media">
    <img src="./assets/random.png" class="img-fluid"/>
  </div>
  </div>
</div>
    <RandomGenerator />

  </div>
</template>

<script>
import RandomGenerator from './components/RandomGenerator'

export default {
  name: 'App',
  components: {
    RandomGenerator
  }
}
</script>

<style>
#app {

}
</style>
