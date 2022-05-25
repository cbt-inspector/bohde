<template>
  <div>
    <bohhead />
    <div class="maincontainer">
      <bohmenu />
<!--Text Body STARTS Here!!!!!-->
      <div class="textbody">
        <div class="flexflex" id="dgif">
          <img src="d.gif" alt="funny d gif thingy">
          <br>
          <p>haha funny gif (it says d)</p>
        </div>
        <div class="flexflex">
          <p>
            <span style="font-weight: bold;font-size: 28px;">boh</span> &nbsp;
            <b>/(bəʊ)/</b>
            <br>
            <br>
            <i>interjection</i> <br>
            boah but without the a
          </p>
        </div>
        <div class="flexflex" id="among-shapiro">
          <p>Now let's say hypothetically I was the impostor. ((ඞ))<br>How would I get from reactor ඞ to medbay in that timespan, from which we saw each other, till you ඞඞ found yellow dead? (((ඞඞඞsus!))) Also if I were the impostor ((ඞ)) hypothetically speaking, how would I have finished all my tasks?? ඞඞඞඞඞ?ඞඞඞ???</p>
        </div>
        <div class="flexflex">
          <p>im still not really sure what to put on the site, send suggestions to
            <a href="mailto:info@theboh.de" style="color:darkblue">info@theboh.de</a>
          </p>
        </div>
      </div>
<!--Text Body STOPS Here!!!!!-->
    </div>
    <bohfoot />
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Comfortaa:wght@300;400;500;600;700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Courier+Prime:ital,wght@0,400;0,700;1,400;1,700&display=swap');
.maincontainer {
  background: white;
  padding-bottom: 50px;
}
.textbody {
  height: auto;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  margin-top: 20px;
}
.textbody h2 {
  text-align: center;
  font-family: 'Open Sans', sans-serif;
  font-size: 28px;
}
.textbody p {
  font-family: 'Open Sans', sans-serif;
  font-size: 18px;
}

.flexflex {
  background: #cfcfcf;
  padding: 1vw;
  margin: 5px;
  flex-grow: 4;
  flex-shrink: 4;
}

#dgif img {
  width: 30vw;
}
#dgif p {
  font-size: 30px;
  margin: 0;
}

#among-shapiro {
  width: 60vw;
  height: auto;
  flex-shrink: none;
}
#among-shapiro p {
  font-size: 2em;
}


</style>
