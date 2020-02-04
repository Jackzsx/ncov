<template>
  <div id="app">
    <div id="nav">
      <img src="./assets/wuhan-ncov.jpg" style="width:100%">
    </div>

<!-- <header><div class="bg"></div>
<h1><small>
  新型冠状病毒</small><br>疫情实时动态 · 湖北</h1>
</header> -->
    <router-view/>
  </div>
</template>

<style lang="stylus">
#app
  font-family 'Avenir', Helvetica, Arial, sans-serif
  -webkit-font-smoothing antialiased
  -moz-osx-font-smoothing grayscale
  text-align center
  color #2c3e50
  max-width 500px
  margin 0 auto
  header
    padding: 1rem;
    position: relative;
    color: #fff;
    .bg
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-image: url(./assets/wuhan-ncov.jpg);
      background-position: center;
      background-size: 100%;
      z-index: -1;
      filter: brightness(0.5);
</style>
