<template>
  <div class="App text-light">
    <!-- Setting app routes using Vue Router -->
    <router-view></router-view>
  </div>
</template>

<script>

export default {
  name: "App"
}
</script>

<style>
  .App {
    background-color: #282c34;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
</style>
