<template>
<!--  <div class="wrapper">
  <div class="sidescroll">
    <p>
      Der code funktioniert nicht...Luca hat die Hausaufgaben vergessen...Ich(die webseite) begehe suizid...Das hätte ich aber anders formuliert...Raucher rauchen (es stinkt)...Boh!...[Insert Bee Movie transcript here]...https://www.bebis-schleswig-holstein.de/...
    </p>
    <p>
      Der code funktioniert nicht...Luca hat die Hausaufgaben vergessen...Ich(die webseite) begehe suizid...Das hätte ich aber anders formuliert...Raucher rauchen (es stinkt)...Boh!...[Insert Bee Movie transcript here]...https://www.bebis-schleswig-holstein.de/...
    </p>
  </div>
</div>
-->
<div class="invertedbox">
  <h1>
    Boh!
  </h1>
  <hr class="whiteline">
  <p class="skewer">
    Die offizielle Webseite
  </p>
</div>
<div>
  <button class="menu">Menu</button>
  <p>
    wieso wurde dies getan
  </p>
</div>

</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300&display=swap');

h1 {
  font-family: 'Open Sans', sans-serif;
  font-size: 50px;
}

p {
  font-family: 'Open Sans', sans-serif;
  font-size: 25px;
}

.invertedbox {
  background-color: grey;
  text-align: center;
  padding: 0;
  color: white;
  overflow: hidden;
}

.adverse {
  color: green;
  background: purple;
}
body {
  margin: 0;
  overflow: hidden;
  background: white;
}

.whiteline {
  background-color: white;
  width: 70%;
}

.skewer {
  transform: skewY(-3deg);
}

.wrapper {
  max-width: 100%;
  overflow: hidden;
  color: white;
  background: black;
}

.sidescroll {
  white-space: nowrap;
  overflow: hidden;
  display: inline-block;
  animation: sidescroll 11s linear infinite;
}

.sidescroll p {
  display: inline-block;
  font-size: 12px;
}

.menu {
  background-color: white;
  border: 1px solid black;
  color: black;
  padding: 3px 30px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  transition-duration: 0.2s;
  cursor: pointer;
}

.menu:hover {
  background-color: black;
  color: white;
}


@keyframes sidescroll {
  0% {
    transform: translate3d(0, 0, 0);
  }

  100% {
    transform: translate3d(-50%, 0, 0);
  }
}

</style>
