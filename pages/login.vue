<template>
  <div>
    <bohhead />
    <div style="background:white">
      <bohmenu />
      <div class="mainbody">
        <form action="#" method="post">
          <p id="label">login form (((🅱)))</p>
          <div>
            <input type="text" name="user" id="user" class="frm" placeholder="username/email">
          </div>
          <div>
            <input type="password" name="pass" id="pass" class="frm" placeholder="password">
          </div>
          <div>
            <button class="submit">login</button>
          </div>
        </form>
      </div>
    </div>
    <bohfoot />
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Comfortaa:wght@300;400;500;600;700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Courier+Prime:ital,wght@0,400;0,700;1,400;1,700&display=swap');

body {
  margin: 0;
  overflow: auto;
}
h1 {
  font-family: 'Open Sans', sans-serif;
  font-size: 50px;
}
input, button {
  text-align: center;
  font-family: 'Open Sans', sans-serif;
  font-size: 28px;
}
p {
  font-family: 'Open Sans', sans-serif;
  font-size: 25px;
  text-align: center;
}
a {
  font-family: 'Open Sans', sans-serif;
}
.mainbody {
  height:90vh;
  background:rgb(230, 230, 230);
  margin-left: 6%;
  margin-right: 6%;
  display: flex;
  align-content: center;
  justify-content: center;
}

.frm {
  margin: 10px;
  border: 1px solid #111;
  border-radius: 5px;
}
.submit {
  margin: 10px;
  border: 1px solid #111;
  border-radius: 5px;
  width: calc(100% - 20px);
  transition-duration: 0.5s;
}

.submit:hover {
  background: #f11;
  font-weight: bold;
}

</style>
