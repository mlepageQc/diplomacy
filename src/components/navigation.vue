<template>
  <nav class="navigation">
    <router-link to="index" class="navigation__item">Salut</router-link>
    <router-link to="index" class="navigation__item">Cava</router-link>
    <router-link to="index" class="navigation__item">Ouitoi</router-link>
  </nav>
</template>

<script>

  export default {

  }

</script>

<style>

  .navigation {
    font-size: 15px;
    display: flex;
    flex-direction: column;
    padding: 20px 0;
    position: fixed;
    top: 60px;
    width: 196px;
    left: 0;
    bottom: 0;
    background: pink;
  }

</style>
