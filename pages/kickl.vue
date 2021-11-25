

<template>
<script>
function kicklfunc(kik) {
  var mult = document.getElementById("inpt").value;
  var kik = mult /1.723300970873786407766990291262;
  document.getElementById("valfield").innerHTML = "Die länge ist " + kik + " Kickl lang";
}
</script>
<header>
<div class="invertedbox">
  <h1>
    <a href="/">Boh!</a>
  </h1>
  <hr class="whiteline">
  <p class="skewer">
    Die offizielle Webseite
  </p>
</div>
<div class=whitebckg>
  <div class="dropdown">
    <button class="menu">Menu</button>
    <div class="dropdown-content">
      <a href="/">Homepage</a>
      <a href="/pentest">Pentesting Service</a>
      <a href="http://www.ismycomputeron.com/">Suprise</a>
      <a href="https://www.bibun.ga/">Bing Chilling&copy;</a>
      <a href="https://www.bibun.ga/tacdrip.png">😳dro🅱pf😳</a>
    </div>
  </div>
<div class=textbdy>
  <h2>Kickl Umrechner</h2>
  <br>
  <div class="calc">
    <button type="submit" onclick="kicklfunc()">Gib hier meter ein &rarr;</button>
    <input id="inpt" type="number">
    <a id="valfield" style="color:red">Und hier wird es in Kickl angegeben</a>
  </div>
  <br>
  <img src="~/static/20211125_190305375_iOS.jpg" style="display:block;margin-left:auto;margin-right:auto"/>
</div>
</div>
<div class="footeradv">
<div class="foottable" style="margin-top:10px">
  <table style="margin-left:auto;margin-right:auto;">
    <tr>
      <th colspan="3" style="align-text:center">Contact info or smth idk</th>
    </tr>
    <tr>
      <td><a href= "mailto:owen@theboh.de">owen@theboh.de</a></td>
      <td>&nbsp;|&nbsp;</td>
      <td><a href= "mailto:luca@theboh.de">luca@theboh.de</a></td>
      <td>&nbsp;|&nbsp;</td>
      <td><a href= "mailto:emil@theboh.de">emil@theboh.de</a></td>
    </tr>
  </table>
  <hr>
  <a style="color: rgba(255, 255, 255, 0.5)">&copy; 2021 Das-Boh AG. All Rights Reserved</a>
</div>
</div>
</header>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Comfortaa:wght@300;400;500;600;700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Courier+Prime:ital,wght@0,400;0,700;1,400;1,700&display=swap');
/*monospace*/
body {
  margin: 0;
  overflow: auto;
}
h1 {
  font-family: 'Open Sans', sans-serif;
  font-size: 50px;
}
p {
  font-family: 'Open Sans', sans-serif;
  font-size: 25px;
}
a {
  font-family: 'Open Sans', sans-serif;
}
.calc {
  margin-left: 20%;
  margin-right: auto;
}
.calc a, input, button {
  font-family: 'Comfortaa', serif;
  font-size: 25px;
}
.invertedbox {
  font-family: 'Comfortaa', serif;
  background-color: black;
  text-align: center;
  padding: 0;
  color: white;
  overflow: hidden;
  height: 270px;
}
.invertedbox a {
  font-family: 'Open Sans', sans-serif;
  text-decoration: none;
  color: white;
}
.whiteline {
  background-color: white;
  width: 70%;
}
.whitebckg {
  background: white;
  height: auto;
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
.skewer {
  transform: skewY(-3deg);
}
.menu {
  background-color: white;
  border: 1px solid black;
  color: black;
  padding: 3px 50px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 18px;
  transition-duration: 0.2s;
  cursor: pointer;
  font-family: 'Open Sans', sans-serif;
}
.menu:hover {
  background: black;
  color: white;
}
.dropdown {
  position: relative;
  display: inline-block;
}
.dropdown-content {
  display: none;
  position: absolute;
  background-color: white;
  text-align: center;
  min-width: 100%;
  box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
  z-index: 1;
}
.dropdown-content a {
  color: black;
  background: white;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  transition-duration: 0.2s;
}
.dropdown-content a:hover {
  background: black;
  color: white;
}
.dropdown:hover .dropdown-content {
  display: block;
  background: black;
}
.dropdown:hover .dropbtn {
  background: black;
}
.footeradv {
  position: relative;
  bottom: 0px;
  background: black;
  width: 100%;
  text-align: center;
  height: 150px;
  overflow: hidden;
  color: rgba(255, 255, 255, 0.5);
}
.footeradv th, td, a {
  font-family: 'Courier Prime', sans-serif;
  color: grey;
}
.footeradv hr {
    border: none;
    border-top: 3px double #333;
    color: #333;
    overflow: visible;
    text-align: center;
    height: 5px;
    width: 30%;
}
.footeradv hr:after {
    background: black;
    content: '§';
    padding: 0 4px;
    position: relative;
    top: -13px;
    color: grey;
}
.foottable {
  background: black;
}
</style>
