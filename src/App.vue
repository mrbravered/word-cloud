<template>
  <div id="app">
    <img src="./assets/logo.png">
    <WordCloud/>
  </div>
</template>

<script>
import WordCloud from './components/WordCloud'
import vuetify from '@/plugins/vuetify'

export default {
  name: 'App',
  vuetify,
  components: {
    WordCloud
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
