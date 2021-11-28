<template>
  <div style="background:white">
  <div class="dropdown">
    <button class="menu">Menu</button>
    <div class="dropdown-content">
      <a href="/">Homepage</a>
      <a href="/pentest">Pentesting Service</a>
      <a href="/kickl">Kickl Umrechner</a>
      <a href="https://www.bibun.ga/">Bing Chilling&copy;</a>
      <a href="https://www.bibun.ga/tacdrip.png">😳dro🅱pf😳</a>
    </div>
  </div>
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Comfortaa:wght@300;400;500;600;700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Courier+Prime:ital,wght@0,400;0,700;1,400;1,700&display=swap');

.menu {
  background-color: white;
  border: 1px solid black;
  color: black;
  padding: 3px 54px;
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
  background: white;
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
  font-family: 'Open Sans', sans-serif;
  font-size: 18px
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

</style>
