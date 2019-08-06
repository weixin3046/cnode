<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
html, body, div, span, iframe, h1, h2, h3, h4, h5, h6, p, pre, a, code, em, img, small, strong, i, dl, dt, dd, ol, ul, li, form, label, table, tbody, tr, th, td, canvas, footer, header, hgroup, menu, nav, time, mark, audio, video {
  margin: 0;
  padding: 0;
  border: 0;
  font-size: 100%;
  font: inherit;
  vertical-align: baseline;
  outline: none;
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
#app {
  
}
ol, ul { list-style: none; }
img { border: 0; max-width: 100%; }
a {text-decoration: none;color: #000}
.clearfix {zoom: 1; }
.clearfix:after, .clearfix:before {content: "\200B"; display: block; height: 0; visibility: hidden; }
.clearfix:after {clear: both; }
.f-r {
  float: right;
}

.f-l {
  float: left;
}
.container {
  padding-right: 15px;
  padding-left: 15px;
  margin-right: auto;
  margin-left: auto;
}
@media (min-width: 768px) {
  .container {
    width: 750px;
  }
}
@media (min-width: 992px) {
  .container {
    width: 970px;
  }
}
@media (min-width: 1200px) {
  .container {
    width: 1170px;
  }
}
</style>
