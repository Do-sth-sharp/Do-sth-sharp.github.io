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
    background: linear-gradient(to bottom, rgba(0,0,0,0.8),rgba(0,0,0,0));
    width: 1548px;
    height: 90px;
    margin: -1%;position:fixed;
}
.ShaperTop{
  font-family: TitleT;letter-spacing:1.5px;
}
.ShaperLogo{
    width: 35px; float: left;filter:opacity(90%);
    margin-top: 27.5px;margin-left: 6%;
}
.ShaperTitle{
    float: left;color: rgba(255, 255, 255, 0.80);
    margin-top: 31px;margin-left: 1%;font-size: 20px;
}
.VOCALSHAPER{
  float:left;margin-left: 10%;margin-top: 36px;font-size: 15px;color: rgba(255, 255, 255, 0.80);
}
.DOWNLOAD{
  float:left;margin-left: 10%;margin-top: 36px;font-size: 15px;color: rgba(255, 255, 255, 0.80);
}
.DOCUMENT{
  float:left;margin-left: 10%;margin-top: 36px;font-size: 15px;color: rgba(255, 255, 255, 0.80);
}
.CONTACT{
  float:left;margin-left: 10%;margin-top: 36px;font-size: 15px;color: rgba(255, 255, 255, 0.80);
}
.GithubLogo{
  float:left;width: 32px;
  margin-top: 28px;
  margin-left: 9%;
  filter:opacity(90%);  
  border-radius: 50px;
}
</style>