<template>
  <div id="app">
    <a href="https://http://rubyonrails.org/" target="_blank" title="Rails">
      <img src="./assets/vue.png" height="50"/>
    </a>
    <a href="https://vuejs.org" target="_blank" title="Vue">
      <img src="./assets/rails.svg" height="50"/>
    </a>
    <employee-index></employee-index>
  </div>
</template>

<script>
import EmployeeIndex from './components/EmployeeIndex'

export default {
  name: 'app',
  components: {
    EmployeeIndex
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
  width: 100%;
}
</style>
