<template>
  <div class="ticker">
    <div class="ticker-news">
      <span>
        <span>Der code funktioniert nicht...</span>
        <span>Luca hat die Hausaufgaben vergessen...</span>
        <span>Ich(die webseite) begehe suizid...</span>
        <span>Das hätte ich aber anders formuliert...</span>
        <span>Raucher rauchen (es stinkt)...</span>
        <span>Boh!...</span>
        <span>[Insert Bee Movie transcript here]...</span>
        <span>https://www.bebis-schleswig-holstein.de/...</span>
      </span>
    </div>
  </div>
  <div class=invertedbox>
    <h1>
      Boh!
    </h1>
    <hr class=whiteline>
    <p>
      Die offizielle Webseite
    </p>
  </div>
</template>
<script>
export default {

}
</script>

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


.ticker-news {
  width: 7000px;
  padding: 10px 0;
  color: #7c7c7c;
  font-size: 36px;
  background: black;
}

.ticker {
  overflow: hidden;
  width: 100%;
  padding: 5px 0 120px;
  position: fixed;
  bottom: -50px;
  left: 0;
  font-family: 'Open Sans', sans-serif;
}
.ticker-news > * {
  display: inline-block;
  animation: news 15s infinite linear;
}

@keyframes news {
  0% {
    transform: translateX(0);
  }

  100% {
    transform: translateX(-4135px);
  }
}




</style>
