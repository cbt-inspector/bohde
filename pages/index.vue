<template>
  <div>
    <h1 class="blue">bing chilling</h1>
    <img src="~/static/bingchilling.png" />
    <p>
      the chinese government is coming to kill me
    </p>
    <p v-if="rendering === 'server'">
      please send help
    </p>
    <p v-if="rendering === 'client'">Navigation is done on client side.</p>
    <ul>
      <li>oh no</li>
      <li>i am going to die</li>
      <li>mika is cringe</li>
    </ul>

    <NuxtLink to="/bruhmomentbruhmomentbruhmomentbruhmomentbruhmomentbruhmomentbruhmomentbruhmomentbruhmomentbruhmomentbruhmomentbruhmomentbruhmomentbruhmomentbruhmoment">this goes nowhere</NuxtLink>
    <p> </p>
    <NuxtLink to="/drip-page">militant drip enjoyer</NuxtLink>
  </div>

</template>
<script>
export default {
  asyncData() {
    return {
      rendering: process.server ? 'server' : 'client'
    }
  }
}
</script>

<style>
.blue {
    color: blue;
  }
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300&display=swap');
h1 {
  font-family: 'Open Sans', sans-serif;
}
p {
  font-family: 'Open Sans', sans-serif;
}
li {
  font-family: 'Open Sans', sans-serif;
}
NuxtLink {
  font-family: 'Open Sans', sans-serif;
}

</style>

