<template>
  <div id="app">
    <app-header></app-header>
    <navigation></navigation>
    <main>
      <router-view></router-view>
    </main>
  </div>
</template>

<script>

  import AppHeader from '@/components/app-header'
  import Navigation from '@/components/navigation'

  export default {
    name: 'app',

    components: {
      AppHeader,
      Navigation
    }
  }

</script>

<style>

  #app {
    width: 100%;
    height: 100%;
  }

  main {
    height: calc(100% - 60px);
    width: calc(100% - 196px);
    margin-left: 196px;
    background: grey;
    margin-top: 60px;
  }

</style>
