<template>
  <div id="app">
    <BookList/>
  </div>
</template>

<script>
import BookList from './components/Book/BookList'

export default {
  name: 'app',
  components: {
    BookList
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
