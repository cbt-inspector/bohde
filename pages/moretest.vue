<template>
  <div>
    <bohhead />
    <div style="background:white">
      <bohmenu />
      <div class=textbdy>
        <h2>Kickl Umrechner</h2>
        <br>
        <div class="calc">
        <script>
        function kicklfunc(kik) {
          var mult = document.getElementById("inpt").value;
          var kik = mult /1.723300970873786407766990291262;
          document.getElementById("valfield").innerHTML = "Die länge ist " + kik + " Kickl lang"
        }
        </script>
          <button type="submit" onclick="kicklfunc()">Gib hier meter ein &rarr;</button>
          <input id="inpt" type="number">
          <a id="valfield" style="color:red">Und hier wird es in Kickl angegeben</a>
        </div>
        <br>
        <img src="~/static/20211125_190305375_iOS.jpg" style="display:block;margin-left:auto;margin-right:auto;padding-bottom:50px"/>
      </div>
    </div>
    <bohfoot />
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Comfortaa:wght@300;400;500;600;700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Courier+Prime:ital,wght@0,400;0,700;1,400;1,700&display=swap');

.calc {
  margin-left: 20%;
  margin-right: auto;
}
.calc a, input, button {
  font-family: 'Comfortaa', sans-serif;
  font-size: 25px;
}
.textbdy {
  background: white;
  height: auto;
}
.textbdy h2 {
  text-align: center;
  font-family: 'Open Sans', sans-serif;
  font-size: 28px;
}
.textbdy p {
  font-family: 'Open Sans', sans-serif;
  font-size: 18px;
  width: 70%;
  margin-left: 15%;
}
</style>
