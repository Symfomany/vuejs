<template>
  <div id="app">
    <h3>Les frous</h3>
    <p>
      C'est terrible
      {{ message }}
      
    </p>
  </div>
</template>

<script>
import Hello from './components/Hello'

export default {
  data: {
    message: 'Hello Vue.js!'
  },
  components: {
    Hello
  }
}
</script>

<style>
html {
  height: 100%;
}

body {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100%;
}
#app h3{
  color: rgb(138, 150, 72);
}
#app {
  color: #2c3e50;
  margin-top: -100px;
  max-width: 600px;
  font-family: Source Sans Pro, Helvetica, sans-serif;
  text-align: center;
}

#app a {
  color: #42b983;
  text-decoration: none;
}

.logo {
  width: 100px;
  height: 100px
}
</style>
