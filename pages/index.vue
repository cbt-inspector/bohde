<template>
  <div class=invertedbox>
    <h1>
      Boh!
    </h1>
    <hr class=whiteline>
    <p>
      Die offizielle Webseite
    </p>
  </div>
  <div>
    <marquee direction="down" width="100%" height="350" behavior="alternate">
      <marquee behavior="alternate">
        Boh!
      </marquee>
    </marquee>
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
</style>
