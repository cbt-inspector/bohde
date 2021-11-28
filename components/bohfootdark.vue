<template>
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
      <a style="color: rgba(63, 81, 99, 1)">&copy; 2021 Das-Boh AG. All Rights Reserved</a>
    </div>
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Comfortaa:wght@300;400;500;600;700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Courier+Prime:ital,wght@0,400;0,700;1,400;1,700&display=swap');

.footeradv {
  position: relative;
  bottom: 0px;
  background: #12141d;
  width: 100%;
  text-align: center;
  padding-top: 50px;
  height: 250px;
  overflow: hidden;
  /*color: rgba(255, 255, 255, 0.5);*/
  color: rgba(63, 81, 99, 1);
}

.footeradv th, td, a {
  font-family: 'Courier Prime', sans-serif;
  color: rgba(63, 81, 99, 1);
}

.footeradv hr {
  border: none;
  border-top: 3px double rgba(70, 15, 29, 1);
  color: rgba(70, 15, 29, 1);
  overflow: visible;
  text-align: center;
  height: 5px;
  width: 30%;
}

.footeradv hr:after {
  background: #12141d;
  content: '§';
  padding: 0 4px;
  position: relative;
  top: -13px;
  color: rgba(232, 49, 98, 0.9);
}

.foottable {
  background: #12141d;
}

</style>
