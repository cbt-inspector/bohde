<template>
  <div>
    <bohheaddark />
    <div class="maincontainer">
      <bohmenudark />
<!--Text Body STARTS Here!!!!!-->
      <div class="textbody">
        <h2>Lorem ipsum</h2>
        <p style="color:rgba(0, 255, 55, 0.7)">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. <br>
          Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. <br>
          Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. <br>
          Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. <br>
        </p>
        <p style="color:rgba(0, 255, 55, 0.7)">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. <br>
          Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. <br>
          Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. <br>
          Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. <br>
        </p>
      </div>
      <div class="row">
        <div class="lcolumn">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. <br>
          Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. <br>
          Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. <br>
          Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. <br>
        </div>
        <div class="rcolumn">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. <br>
          Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. <br>
          Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. <br>
          Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. <br>
        </div>
      </div>
<!--Text Body STOPS Here!!!!!-->
    </div>
    <bohfootdark />
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Comfortaa:wght@300;400;500;600;700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Courier+Prime:ital,wght@0,400;0,700;1,400;1,700&display=swap');
/*
rgba(232, 49, 98, 1)
rgba(26, 32, 44, 1)
rgba(70, 15, 29, 1)
rgba(227, 116, 0, 1)
rgba(37, 71, 63, 1)
rgba(63, 81, 99, 1)
*/
.maincontainer {
  background: #12141d;
  padding-bottom: 50px;
  height: 800px;
}
.row::after {
  content: "";
  clear: both;
  display: table;
}
.rcolumn {
  float: left;
  display: inline;
  position: absolute;
  padding: 15px;
  margin-top: 50px;
  right: 15%;
  width: 30%;
  font-family: 'Comfortaa', sans-serif;
  font-size: 25px;
  background: rgba(26, 32, 44, 1);
  border: 1px solid;
  border-color: rgba(0, 255, 55, 0.3);
  border-radius: 20px;
}
.lcolumn {
  float: left;
  display: inline;
  position: absolute;
  padding: 15px;
  margin-top: 50px;
  left: 15%;
  width: 30%;
  font-family: 'Comfortaa', sans-serif;
  font-size: 25px;
  background: rgba(26, 32, 44, 1);
  border: 1px solid;
  border-color: rgba(0, 255, 55, 0.3);
  border-radius: 20px;
}
.textbody {
  background: black;
  border-radius: 0px 0px 50px 50px;
  /*color: rgba(232, 0, 110, 0.7);*/
  height: auto;
  padding-top: 20px;
  padding-bottom: 30px;
  margin-top: auto;
  margin-left: 6%;
  margin-right: 6%;
}
.textbody h2 {
  text-align: center;
  font-family: 'Open Sans', sans-serif;
  font-size: 28px;
}
.textbody p {
  font-family: 'Open Sans', sans-serif;
  font-size: 18px;
  width: 70%;
  margin-left: 15%;
}
</style>
