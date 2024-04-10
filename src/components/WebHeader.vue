<script setup>

</script>

<template>
  <div class="HeaderTop"> 
  <div class="ShaperTop">
  <img src= "../assets/ShaperLogo.png"  class="ShaperLogo">
  </img>
  <div class="ShaperTitle">VocalShaper</div>
   <div class="VOCALSHAPER">VOCALSHAPER</div>
   <div class="DOWNLOAD">DOWNLOAD</div>
   <div class="DOCUMENT">DOCUMENT</div>
   <div class="CONTACT">CONTACT</div>
   <img src= "../assets/github.png"  class="GithubLogo">
  </img>
  </div>
  </div>
</template>

<style scoped>
@font-face {
    font-family:TitleT;
    src: url("../assets/HarmonyOS_Sans_Light.ttf");
}
.HeaderTop{
    background: linear-gradient(to bottom, rgba(0,0,0,0.85),rgba(0,0,0,0));
    width: 101.5%;
    height: 90px;
    margin: -1%;
}
.ShaperTop{
  font-family: TitleT;letter-spacing:1.5px;
}
.ShaperLogo{
    width: 35px; float: left;filter:opacity(75%);
    margin-top: 27.5px;margin-left: 65px;
}
.ShaperTitle{
    float: left;color: rgba(255, 255, 255, 0.65);
    margin-top: 31px;margin-left: 20px;font-size: 20px;
}
.VOCALSHAPER{
  float:left;margin-left: 240px;margin-top: 36px;font-size: 15px;color: rgba(255, 255, 255, 0.65);
}
.DOWNLOAD{
  float:left;margin-left: 110px;margin-top: 36px;font-size: 15px;color: rgba(255, 255, 255, 0.65);
}
.DOCUMENT{
  float:left;margin-left: 110px;margin-top: 36px;font-size: 15px;color: rgba(255, 255, 255, 0.65);
}
.CONTACT{
  float:left;margin-left: 110px;margin-top: 36px;font-size: 15px;color: rgba(255, 255, 255, 0.65);
}
.GithubLogo{
  float:left;width: 32px;
  margin-top: 28px;
  margin-left: 240px;
  filter:opacity(75%);  
  border:1.5px solid rgba(255, 255, 255, 0.50);
  border-radius: 50px;
}
</style>