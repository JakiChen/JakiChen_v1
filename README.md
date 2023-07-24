<!---
<h4 align="center"><samp> Hi there 👋🏾  welcome to my Github! I am very interested in design & advanced website development Tech （ I'm exploring React Tech 🐍 ☁️） </samp></h4>
<p align="center">
  <img width="250" src="https://user-images.githubusercontent.com/5679180/79618120-0daffb80-80be-11ea-819e-d2b0fa904d07.gif">
</p>
--->


<?xml version="1.0" encoding="utf-8"?>
<svg viewBox="-1136 -1136 2272 2272" width="600" height="600" 
  xmlns="http://www.w3.org/2000/svg" 
  xmlns:xlink="http://www.w3.org/1999/xlink">
  <!-- MIT license by Tom CHEN https://github.com/tomchen/animated-svg-clock -->
  <title>Clock</title>
  <style type="text/css">
  #face-outline {
    fill: #fff;
    stroke: #d3d3d3;
    stroke-width: 64;
  }
  #face-use,
  #hand-h-use,
  #hand-m-use {
    fill: #000;
    stroke: none;
  }
  #hand-s-use {
    fill: #bd2420;
    stroke: none;
  }
  #center-dot {
    fill: #fff;
    stroke: none;
  }
  @keyframes rotation {
    from {
      -ms-transform: rotate(0deg);
      -moz-transform: rotate(0deg);
      -webkit-transform: rotate(0deg);
      -o-transform: rotate(0deg);
      transform: rotate(0deg);
    }
    to {
      -ms-transform: rotate(360deg);
      -moz-transform: rotate(360deg);
      -webkit-transform: rotate(360deg);
      -o-transform: rotate(360deg);
      transform: rotate(360deg);
    }
  }
  #hand-h-use {
    -ms-animation: rotation 43200s linear infinite;
    -moz-animation: rotation 43200s linear infinite;
    -webkit-animation: rotation 43200s linear infinite;
    -o-animation: rotation 43200s linear infinite;
    animation: rotation 43200s linear infinite;
  }
  #hand-m-use {
    -ms-animation: rotation 3600s linear infinite;
    -moz-animation: rotation 3600s linear infinite;
    -webkit-animation: rotation 3600s linear infinite;
    -o-animation: rotation 3600s linear infinite;
    animation: rotation 3600s linear infinite;
  }
  #hand-s-use {
    -ms-animation: rotation 60s linear infinite;
    -moz-animation: rotation 60s linear infinite;
    -webkit-animation: rotation 60s linear infinite;
    -o-animation: rotation 60s linear infinite;
    animation: rotation 60s linear infinite;
  }
  </style>
  <defs>
    <path id="mark-5min" d="M -40,-1000 l 80,0 0,245 -80,0 z" />
    <path id="mark-min" d="M -15,-1000 l 30,0 0,80  -30,0 z" />
    <path id="hand-h" d="M -50,-650 l 100,0 10,890 -120,0 z" />
    <path id="hand-m" d="M -40,-950 l 80,0 10,1200 -100,0 z" />
    <g id="hand-s">
      <path d="M -20,-550 l 30,0
                     7,890 -30,0 z" />
      <path d="M   0,-750 a 105,105 0 0 1 0,210
                          a 105,105 0 0 1 0,-210 z" />
    </g>
    <g id="face-30d">
      <use xlink:href="#mark-5min" />
      <use xlink:href="#mark-min" transform="rotate(06)" />
      <use xlink:href="#mark-min" transform="rotate(12)" />
      <use xlink:href="#mark-min" transform="rotate(18)" />
      <use xlink:href="#mark-min" transform="rotate(24)" />
    </g>
    <g id="face-90d">
      <use xlink:href="#face-30d" />
      <use xlink:href="#face-30d" transform="rotate(30)" />
      <use xlink:href="#face-30d" transform="rotate(60)" />
    </g>
    <g id="face">
      <use xlink:href="#face-90d" />
      <use xlink:href="#face-90d" transform="rotate(90)" />
      <use xlink:href="#face-90d" transform="rotate(180)" />
      <use xlink:href="#face-90d" transform="rotate(270)" />
    </g>
  </defs>
  <circle id="face-outline" r="1104" />
  <use xlink:href="#face" id="face-use" />
  <use xlink:href="#hand-h" id="hand-h-use" />
  <use xlink:href="#hand-m" id="hand-m-use" />
  <use xlink:href="#hand-s" id="hand-s-use" />
  <circle id="center-dot" r="5" />
  <script type="text/javascript">
  function setTime(h, m, s) {
    document.getElementById("hand-h").setAttribute("transform", "rotate(" + ((h >= 12 ? h - 12 : h) * 30 + m / 2 + s / 120) + ")");
    document.getElementById("hand-m").setAttribute("transform", "rotate(" + (m * 6 + s / 10) + ")");
    document.getElementById("hand-s").setAttribute("transform", "rotate(" + (s * 6) + ")");
  }
  var date = new Date();
  setTime(date.getHours(), date.getMinutes(), date.getSeconds());
  </script>
</svg>


<!---
A freelance Web Designer & Developer from Kerala, India. I design and develop websites, landing pages and applications for startups and enterprises.
<p align="center">
<a href= "https://dev.to/ari_hacks"><img src="https://img.icons8.com/windows/32/000000/dev.png"/></a>
<a href= "https://twitter.com/ari_hacks"><img src="https://img.icons8.com/material-outlined/30/000000/twitter.png"/></a>
</p>
--->
<!---
![](https://komarev.com/ghpvc/?username=JakiChen&style=flat-square)
--->

<!--
动态图形
<img src="https://github-readme-stats.vercel.app/api?username=JakiChen&hide_title=true&show_icons=true&icon_color=007aff&text_color=333&bg_color=fff" />

**ripperhe/ripperhe** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
