<template>
  <div id="q-app">
    <router-view />
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
  .body--dark {
    background: #000
  }

  .text-weight-regular {
    color: white;
  }

  .q-layout__section--marginal{
    background: rgb(43, 24, 24);
  }

  .full-width {
    background-color: #000;
  }

  .q-item__section {
    color: antiquewhite;
  }

  .justify-between {
    background: black;
  }

  .q-layout {
    background: black;
}

  .ellipsis {
    background: #ccc;
  }

  .q-pa-sm {
    background: #ccc;
  }

  .q-toolbar {
    background: #ccc;
  }

  .q-btn__wrapper {
    background: #777;
  }

  .q-card > div {
    background: #ccc;
  }

  html, body, #q-app {
    background: black;
  }
</style>