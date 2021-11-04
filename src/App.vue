<template>
  <div>
    <about></about>
    <welcome></welcome>
  </div>
</template>

<script>
import About from './components/About.vue'
import Welcome from './components/Welcome.vue'

export default {
  name: 'App',
  components: {
    About,
    Welcome
  }
}
</script>

<style>

div {
  background: blue;
}
</style>
