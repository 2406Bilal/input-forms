<template>
  <SignupComponents />
</template>

<script>
import SignupComponents from './components/signup_components.vue'

export default {
  name: 'App',
  components: { SignupComponents }
}
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
body{
  margin: 0;
  background: #eee;
}
</style>
<!-- Пустая строка после закрывающего тега </style> -->
