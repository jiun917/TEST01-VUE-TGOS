<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  Marker標題:<input id="title" type="text" value="台灣高鐵左營站" /><br/>
  X:<input id="X" type="text" value="178846.498" />
  Y:<input id="Y" type="text" value="2509812.399" /><br/>
  圖片位址(URL):
  <input id="iconUrl" type="text" value="https://api.tgos.tw/TGOSMAPAPI/images/Sample/marker1.png" 
  size="50" /><br/>
  訊息視窗內容
  <input id="infoWindowContent" type="text" value="高雄市左營區高鐵路105號" size="50" /> <br/>
  訊息視窗透明度(0~1)
  <input id="infoWindowOpacity" type="text" value="0.7" size="3"/> <br/>     
  <input type="button" value="確定修改" onclick="setMarker()"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'


export default {
  name: 'App',
  components: {
  HelloWorld
}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
