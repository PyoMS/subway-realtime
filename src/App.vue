<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <TestMsg msg="Test!!!!!!!!!"/>
</template>

<script>
import TestMsg from "@/components/TestMsg";

export default {
  name: 'App',
  components: {
    TestMsg
  }
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
</style>
