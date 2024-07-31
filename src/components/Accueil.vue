<template>
<main>
  <img class="forme3" src="../assets/images/forme3.png">
  <img class="forme5" src="../assets/images/forme5.png">
<div class="content-container">
  <section class="top-container"><img class="setting-icons" src="../assets/images/settingIcons.png"></section>
  <div class='content'>
    <img class="Moi" src="../assets/images/Moi.png">
  <p class="Welcome">Bienvenue!</p>
  <br>
<div class="home-box">
 <p>Je m'appelle <span>Juliana Muir Elesgaray</span></p>
  <div class='visible'>
    <p class="home-text">
      et je suis une 
    </p>
    <ul>
      <li>Web Developper</li>
      <li>Web Designer</li>
      <li>Graphiste</li>
    </ul>
  </div>
  <p class="end-text">basé à Nancy.</p>
</div>
</div>
</div>
</main>
</template>

<script>
export default {
  name: 'Accueil'
}
</script>

<style scoped>
main {
  margin-top: 15%;
}

.forme3 {
  width: 100px;
  position: absolute;
  top: 240px;
  left: 430px;
}
.forme5 {
  width: 150px;
  position: absolute;
  top: 260px;
  left: 340px;
}

.Moi {
  width: 400px;
  position: absolute;
  top: 320px;
  right: 280px;
}

.Welcome {
  text-align: center;
  font-family: Big Pixel;
  font-size: 48px;
  margin-top: 50px;
}

span {
  color: #da3892;
  font-family: Big Pixel;
  font-size: 36px;
  margin-top: 50px;
}

.home-box {
  width: 90%;
  text-align: center;
  margin-left: auto;
  margin-right: auto;
}

.content {
  width:100%;
  font-size:20px;
  line-height:40px;
  color:rgb(173, 176, 230);
}

.visible {
  font-weight:bold;
  overflow:hidden;
  height:40px;   
}

.home-text {
  display:inline;
  float: left;
  margin-left: 115px;
}

ul {
  color: #a76cad;
  font-family: Big Pixel;
  font-size: 36px;
  font-weight: bold;
  padding-left:250px;
  text-align:left;
  list-style:none;
  animation:6s linear 0s normal none infinite change;
  -webkit-animation:6s linear 0s normal none infinite change;
  -moz-animation:6s linear 0s normal none infinite change;
  -o-animation:6s linear 0s normal none infinite change;
}

.end-text {
  position: absolute;
  top: 540px;
  right: 610px;
}

@-webkit-keyframes opacity {
  0%   {opacity:0;}
  50%  {opacity:1;}
  100% {opacity:0;}
}
@keyframes opacity {
  0%   {opacity:0;}
  50%  {opacity:1;}
  100% {opacity:0;}
}

@-webkit-keyframes change {
  0%   {margin-top:0;}
  15%  {margin-top:0;}
  25%  {margin-top:-40px;}
  40%  {margin-top:-40px;}
  50%  {margin-top:-80px;}
  65%  {margin-top:-80px;}
  75%  {margin-top:-40px;}
  85%  {margin-top:-40px;}
  100% {margin-top:0;}
}
@keyframes change {
  0%   {margin-top:0;}
  15%  {margin-top:0;}
  25%  {margin-top:-40px;}
  40%  {margin-top:-40px;}
  50%  {margin-top:-80px;}
  65%  {margin-top:-80px;}
  75%  {margin-top:-40px;}
  85%  {margin-top:-40px;}
  100% {margin-top:0;}
}
</style>