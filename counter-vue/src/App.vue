<template>
  <div>
    <img alt="Vue logo" src="./assets/logo.png" />
    <h1>Counter</h1>
    <Counter />
  </div>
</template>

<script>
import Counter from './components/counter.vue'

export default {
  components: {
    Counter
  }
}
</script>

<style>
div {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
