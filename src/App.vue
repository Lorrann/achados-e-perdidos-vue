<template>
  <div id="app">
    <nav class="demo">
      <a href="#/" class="brand">
        <span>Achados e Perdidos</span>
      </a>

      <!-- responsive-->
      <input id="bmenub" type="checkbox" class="show">
      <label for="bmenub" class="burger pseudo button">menu</label>

      <div class="menu">
        <a href="#/login" class="pseudo button icon-picture">Log in</a>
      </div>
    </nav>

    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'app',
}
</script>

