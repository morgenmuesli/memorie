<template>
  <div id="app">
    <GameField />
  </div>
</template>

<script>
import GameField from "@/components/GameField";

export default {
  name: 'App',
  components: {
    GameField
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
