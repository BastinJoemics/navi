<template>
  <div id="q-app">
    <router-view />
  </div>
</template>

<script>
import Offline from './components/Offline'
export default {
  name: 'App',
  components: { Offline }
}
</script>

<style>
</style>
