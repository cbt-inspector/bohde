<template>
<header>
  <div class="wrapper">
  <div class="sidescroll">
    <p>
      Der code funktioniert nicht.....Luca hat die Hausaufgaben vergessen.....Ich(die webseite) begehe suizid.....Das hätte ich aber anders formuliert.....Raucher rauchen (es stinkt).....Boh!.....[Insert Bee Movie transcript here].....https://www.bebis-schleswig-holstein.de/ .....Ich will die Lehrer alle umbringen und dann die Schule sprengen.....Händy spiele sind schlecht bitte kauf einfach ein PC.....aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa.....
    </p>
    <p>
      Der code funktioniert nicht.....Luca hat die Hausaufgaben vergessen.....Ich(die webseite) begehe suizid.....Das hätte ich aber anders formuliert.....Raucher rauchen (es stinkt).....Boh!.....[Insert Bee Movie transcript here].....https://www.bebis-schleswig-holstein.de/ .....Ich will die Lehrer alle umbringen und dann die Schule sprengen.....Händy spiele sind schlecht bitte kauf einfach ein PC.....aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa.....
    </p>
  </div>
</div>

<div class="invertedbox">
  <h1>
    Boh!
  </h1>
  <hr class="whiteline">
  <p class="skewer">
    Die offizielle Webseite
  </p>
</div>

<div class=whitebckg>
  <button class="menu">Menu</button>
</div>
<div class=textbdy>
  <h3>Wieso Boh?</h3>
  <p>
    If you’re anything like me, there’ll be plenty of times in Italy when you just don’t know the answer.
    Why hasn’t a single bus come in 45 minutes? I don’t know. Do you really need that piece of paperwork or can you get by with a wink and a smile? I don’t know. Which region makes the best pasta? Heaven help me, I don’t know.
    That’s why I’m such a big fan of today’s word: <b>boh</b>.
    It means ‘I don’t know’, but in its most informal form – like when we shorten the phrase to ‘dunno’.
    Don’t be fooled by the transcription: it doesn’t rhyme with “oh” or “so” in English. Instead the vowel is shorter: more of a “buh”.
    And according to the dictionary, Italians have been making this funny 🅱 sound since circa 1840 to express “doubt, indifference or reticence”.
  </p>
</div>
</header>
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
  padding: 0;
  color: white;
  overflow: hidden;
  height: 400px;
}

body {
  margin: 0;
  overflow: hidden;
  background-image: image('~/static/bingchilling.png');
}

.whiteline {
  background-color: white;
  width: 70%;
}

.whitebckg {
  background: white;
}

.textbdy {
  background: white;
  height: 1500px;
}
.textbdy h3 {
  text-align: center;
  font-family: 'Open Sans', sans-serif;
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
  font-family: 'Open Sans', sans-serif;
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
