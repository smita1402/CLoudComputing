<template>
  <div id="app">
    <img id="logo" src="https://assets.awwwards.com/awards/images/2015/07/simplicity-awwwards-logos.gif">
    <s3uploader/>
  </div>
</template>

<script>
import s3uploader from './components/s3uploader'

export default {
  name: 'App',
  components: {
    s3uploader
  }
}
</script>

<style>
#logo {
  width: 100px
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
