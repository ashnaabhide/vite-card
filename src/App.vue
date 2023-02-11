<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div>
    <div class="buttons">
  <button class="duplicate">duplicate</button>
  <button data-delete-btn>delete</button>
  <button data-toggle-btn>toggle</button>
  <button class="modify">modify title</button>
</div>
<div class="wrapper">
  <div class="container">
  <img class="image" src="https://static.boredpanda.com/blog/wp-content/uploads/2020/05/700-1.jpg" />
  <div class="header">
    <h3>BORZOI</h3>
      <h4>woof</h4>
    <details class="details">
      <summary>Details</summary>
      <div>
        <ul>
        <li>The magnificent borzoi! </li>
        <li>Look how  disproportionate its nose is. Marvelous. </li>
        </ul>
      </div>
  </details>
  </div>
</div>
</div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
