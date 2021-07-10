<template>
  <div id="app">
    <button @click="go$">go$</button>
    <button @click="click">click</button>
  </div>
</template>

<script>

export default {
  name: 'App',

  methods: {
    // Marked grey as unused!
    go$() {
      console.log("go$")
    },
    click() {
      this.go$()
    },
  },
}
</script>

<style>
</style>