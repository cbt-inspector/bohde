<template>
  <div class="wrapper">
    <div class="marquee">
      <p>
        Der code funktioniert nicht...Luca hat die Hausaufgaben vergessen...Ich(die webseite) begehe suizid...Das hätte ich aber anders formuliert...Raucher rauchen (es stinkt)...Boh!...[Insert Bee Movie transcript here]...https://www.bebis-schleswig-holstein.de/...
      </p>
      <p>
        Der code funktioniert nicht...Luca hat die Hausaufgaben vergessen...Ich(die webseite) begehe suizid...Das hätte ich aber anders formuliert...Raucher rauchen (es stinkt)...Boh!...[Insert Bee Movie transcript here]...https://www.bebis-schleswig-holstein.de/...
      </p>
    </div>
  </div>

  <div class=invertedbox>
    <h1>
      Boh!
    </h1>
    <hr class=whiteline>
    <p class=skewer>
      Die offizielle Webseite
    </p>
  </div>
  <div>
    <button class=menu>Menu</button>
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
  background-color: black;
  text-align: center;
  padding: 1px;
  color: white;
}

body {
  margin: 0;
  height: 700px;
  overflow-y: hidden;
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

.marquee {
  white-space: nowrap;
  overflow: hidden;
  display: inline-block;
  animation: marquee 11s linear infinite;
}

.marquee p {
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


@keyframes marquee {
  0% {
    transform: translate3d(0, 0, 0);
  }

  100% {
    transform: translate3d(-50%, 0, 0);
  }
}

</style>
