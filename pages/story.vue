<template>
<body>
  <div class="bg-text-container">
    <div class="animate-text">
      <span>Der Beste Boh&nbsp;</span>
      <span>Der Beste Boh&nbsp;</span>
    </div>
    <div class="animate-text left">
      <span>Der Beste Boh&nbsp;</span>
      <span>Der Beste Boh&nbsp;</span>
    </div>
  </div>



  <div class="container">
    <div class="col">
      <h1>Wieso Boh?</h1>
      <p>Boh! ist ein zeitloser Ausdruck, der immer passt.
      Es gibt keine bessere Art 'Boah!' falsh zu schreiben.
      Daher sagen wir Boh!, und zwingen ihnen es auch zu sagen.
      (wir haben deine familie entführt und fordern $40,000 lösegeld)
      </p>
    </div>
  </div>

</body>
</template>

<style>

@import url(https://fonts.googleapis.com/css?family=Montserrat:800,200);

$font-size: 280px;
$bg-color: #25be96;
$text-color: #230229;

body {
  font-family: montserrat;
  overflow-x: hidden;
  width: 100%;
  height: 100vh;
  display: flex;
  align-items: center;
  background: $bg-color;

  line-height: 1.7;
  color: #fff;

  transform: skewY(-5deg);
}

.bg-text-container {
    transform: translateX(-50%);
    left: 50%;
    position: absolute;
  z-index: -999;
}


@keyframes text-scrolling {
  0% { transform: translate3d(-100%, 0, 0); }
  100% { transform: translate3d(0%, 0, 0); }
}

.animate-text {
  animation: text-scrolling 20s linear infinite;
  will-change: transform;
  display: block;
  position: relative;
  white-space: nowrap;

  &.left {
    animation-direction: reverse;
  }

}

span {
  font-size: $font-size;
  color: transparent;
  -webkit-text-stroke: 2px $text-color;
  text-transform: uppercase;
  display: inline-block;
  line-height: 0.75;
  min-width: auto;
  font-weight: 800;
}





.container {
  padding: 30px;
  max-width: 1000px;
  width: 100%;
  margin: 0 auto;
  .col {
    max-width:600px;
    margin: 0;
  }
}


h1 {
  font-size: 90px;
  margin: 0;
}
p {
  font-size: 18px;
  font-weight: 200;
  margin: 0;
}



</style>

<script>

/* Set width of all animated text to match container */
let parent = document.querySelectorAll('.animate-text');
for(let i = 0; i < parent.length; i++) {
  parent[i].style.width = parent[i].children[0].clientWidth + "px";
};
</script>
