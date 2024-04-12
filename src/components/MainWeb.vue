<script setup>
import WebHeader from './WebHeader.vue';
</script>

<template>
  <div>
  <WebHeader />
  <div>
  <img src= "../assets/Dashichang.png"  class="ShaperLogo">
  </img>
  <p class="MainCha">VocalShaper Studio</p>
  <span class="highlight">VocalShaper Studio</span>
  </div>
  <div>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
  </div>
  </div>
</template>

<style scoped>
.ShaperLogo{
  width: 1540px;height: 730px;margin: -10px;
}

.MainCha {
  position:relative;float: left;
  margin-top: -430px;margin-left: 11%;
  font-size: 100px;
  letter-spacing:10px;
  font-weight: 550;
  -webkit-text-stroke: 1.8px rgba(255, 255, 255, 0.55); 
  -webkit-text-fill-color : rgba(255, 255, 255, 0);

}
.highlight { 
  position:relative;float: left;
  margin-top: -430px;margin-left: 11%;
  font-size: 100px;
  letter-spacing:10px;
  font-weight: 550; 
  -webkit-text-fill-color : rgba(98, 111, 252, 0.6); 
  animation: wave-animation 5s ease-in-out infinite;
}
 
@keyframes wave-animation {
  0%,100%
 {clip-path:polygon(
  0%46%,7%44%,13%42%,20%42%,26%44%,32%46%,
  37%48%,44%50%,51%52%,55%54%,64%56%,
  71%58%,80%60%,84%60%,90%58%,94%56%,
  98%54%,100%52%,100%100%,0%100%)
 }
  50%
 {clip-path:polygon(
  0%52%,4%54%,9%56%,14%58%,20%60%,29%60%,
  36%58%,45%56%,52%54%,60%52%,67%50%,
  74%48%,79%46%,85%44%,89%42%,94%42%,
  96%44%,100%46%,100%100%,0%100%);
 }
}
</style>