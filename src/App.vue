<template>
  <div id="app">
    {{ message }}
  </div>
</template>

<script>
  export default {
    data() {
      return {
        message: 'Say Hello to my little Vue'
      }
    }
  }
</script>

<style>
  body {
    display: flex;
    align-items: center;
    justify-content: center;
    font: 30px Arial;
    color: green;
  }
</style>
