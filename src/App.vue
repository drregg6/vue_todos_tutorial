<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
    </div>
    <Header />
    <router-view />
  </div>
</template>

<script>
import Header from './components/layout/Header';
export default {
  name: 'app',
  components: {
    Header
  }
}
</script>

<style>
  * {
    box-sizing: border-box;
  }
</style>