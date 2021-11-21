<template>
  <nuxt-link
    tag="img"
    :src="require('~/static/404error.gif')"
    to="/">
  </nuxt-link>
  <img src:"~/static/404error.gif" href="https://theboh.de/" class=largeimg>
</template>

<style>
body {
  background-color: black;
}
.largeimg {
  width: 400%;
}
</style>

<script>
</script>
