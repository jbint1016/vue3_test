<template>
  <header>
    <div>
      <h1><a href="#"><img src="../자료/logo.svg" alt="welcome enmedia"></a></h1>
      <nav>
        <ul>
          <li><a href="#">HOME</a></li>
          <li><a href="#">ABOUT</a></li>
          <li><a href="#">CONTACT</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section class="mainSection">
    
    <div class="sliderPage">
      <a href="#" class="btn_l">&lt;</a>
      <a href="#" class="btn_r">&gt;</a>
      <ul>
        <li class="slider">
          <h2>Lorem ipsum <br>
              dolor sit amet,
          </h2>
          <p>Lorem ipsum dolor sit amet, consectetur
    sed do eiusmod tempor incididunt ut
    labore et dolore magna aliqua.
          </p>
        </li>
      </ul>
    </div>

    <div class="slide2">
        <ul>
          <li>
            <figure>
              <img src="../자료/img1.png" alt="img1">
              <figcaption>
              <h3>Lorem ipsum
                dolor sit amet,
              </h3>
              <p>Lorem ipsum dolor sit amet,
                consectetur adipiscing elit,
              </p>
              <small>Lorem ipsum dolor sit amet,</small>
              </figcaption>
            </figure>
          </li>
          <li>
            <figure>
              <img src="../자료/img2.png" alt="img2">
              <figcaption>
              <h3>Lorem ipsum
                dolor sit amet,
              </h3>
              <p>Lorem ipsum dolor sit amet,
                consectetur adipiscing elit,
              </p>
              <small>Lorem ipsum dolor sit amet,</small>
              </figcaption>
            </figure>
          </li>
          <li>
            <figure>
              <img src="../자료/img3.png" alt="img3">
              <figcaption>
              <h3>Lorem ipsum
                dolor sit amet,
              </h3>
              <p>Lorem ipsum dolor sit amet,
                consectetur adipiscing elit,
              </p>
              <small>Lorem ipsum dolor sit amet,</small>
              </figcaption>
            </figure>
          </li>
          <li>
            <figure>
              <img src="../자료/img4.png" alt="img4">
              <figcaption>
              <h3>Lorem ipsum
                dolor sit amet,
              </h3>
              <p>Lorem ipsum dolor sit amet,
                consectetur adipiscing elit,
              </p>
              <small>Lorem ipsum dolor sit amet,</small>
              </figcaption>
            </figure>
          </li>
        </ul>
    </div>
  </section>

  <footer>
    <div>
      <h2><a href="#"><img src="../자료/logo.svg" alt="welcome enmedia"></a></h2>
      <p>Copyrights 2024. 테스트 All Rights Reserved</p>
    </div>
  </footer>

  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

// export default {
//   name: 'App',
//   components: {
//     HelloWorld
//   }
// }
</script>

<style>
#app {
  font-family: 'Pretendard';
  /* -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px; */
}

@font-face {
    font-family: 'Pretendard-Light';
    src: url('https://fastly.jsdelivr.net/gh/Project-Noonnu/noonfonts_2107@1.1/Pretendard-Regular.woff') format('woff');
    font-weight: 300;
    font-style: normal;
}
@font-face {
    font-family: 'Pretendard-Regular';
    src: url('https://fastly.jsdelivr.net/gh/Project-Noonnu/noonfonts_2107@1.1/Pretendard-Regular.woff') format('woff');
    font-weight: 400;
    font-style: normal;
}
@font-face {
    font-family: 'Pretendard-SemiBold';
    src: url('https://fastly.jsdelivr.net/gh/Project-Noonnu/noonfonts_2107@1.1/Pretendard-Regular.woff') format('woff');
    font-weight: 600;
    font-style: normal;
}
@font-face {
    font-family: 'Pretendard-Bold';
    src: url('https://fastly.jsdelivr.net/gh/Project-Noonnu/noonfonts_2107@1.1/Pretendard-Regular.woff') format('woff');
    font-weight: 700;
    font-style: normal;
}
@font-face {
    font-family: 'Pretendard-Black';
    src: url('https://fastly.jsdelivr.net/gh/Project-Noonnu/noonfonts_2107@1.1/Pretendard-Regular.woff') format('woff');
    font-weight: 900;
    font-style: normal;
}


html, body, div, span, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
abbr, address, cite, code,
del, dfn, em, img, ins, kbd, q, samp,
small, strong, sub, sup, var,
b, i,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, figcaption, figure, 
footer, header, hgroup, menu, nav, section, summary,
time, mark, audio, video {
    margin:0;
    padding:0;
    border:0;
    outline:0;
    font-size:100%;
    vertical-align:baseline;
    background:transparent;
}

body {
    line-height:1;
}

article,aside,details,figcaption,figure,
footer,header,hgroup,menu,nav,section { 
    display:block;
}

nav ul {
    list-style:none;
}

blockquote, q {
    quotes:none;
}

blockquote:before, blockquote:after,
q:before, q:after {
    content:'';
    content:none;
}

a {
    margin:0;
    padding:0;
    font-size:100%;
    vertical-align:baseline;
    background:transparent;
}

/* change colours to suit your needs */
ins {
    background-color:#ff9;
    color:#000;
    text-decoration:none;
}

/* change colours to suit your needs */
mark {
    background-color:#ff9;
    color:#000; 
    font-style:italic;
    font-weight:bold;
}

del {
    text-decoration: line-through;
}

abbr[title], dfn[title] {
    border-bottom:1px dotted;
    cursor:help;
}

table {
    border-collapse:collapse;
    border-spacing:0;
}

/* change border colour to suit your needs */
hr {
    display:block;
    height:1px;
    border:0;   
    border-top:1px solid #cccccc;
    margin:1em 0;
    padding:0;
}

input, select {
    vertical-align:middle;
}

a{text-decoration: none;}
ul li, ol li{
  list-style: none;
}

@media screen and (min-width:1280px){
  header{
    padding: 0.6250em 4.3750em;
  }
  header > div{
    max-width: 1820px; margin: 0 auto; position: relative;
  }
  header h1{
    max-width: 8.4375em; 
  }
  header h1 a{
    display: block;
  }
  header h1 a img{
    width: 100%;
  }
  header nav{
    box-sizing: border-box; position: absolute; right: 0; top: 0;
  }
  header nav ul li{
    display: inline-block;
  }
  header nav ul li:not(:first-child){
    margin-left: 1.55563em;
  }
  header nav ul li a{
    display: block; font-size: 15px; font-weight: 700; line-height: 39px;
    color: black;
  }


  .sliderPage{
    background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), url('../자료/main.png') left top / cover no-repeat;
    padding: 13.13em 0; margin-bottom: 10.0000em; position: relative;
  } 
  .sliderPage > a{
    position: absolute; top: 50%;
    color: white; font-weight: 300;
    height: 3.75003em; width: 2.5000em; display: block; font-size: 3.7500em;
  }
  .btn_l{
    left: 5%;
  }
  .btn_r{
    right: 5%;
  }
  .sliderPage ul{
    max-width: 1440px; margin: 0 auto; 
  }
  .sliderPage ul li h2{
    color: white; font-size: 58px; font-weight: 900; line-height: 1.3125em;
    margin-bottom: 45px;
  }
  .sliderPage ul li p{
    font-size: 27px; font-weight: 400; color: white; line-height: 1.3125em;
    max-width: 480px;
  }


  .slide2{
    background-color: white;
  }
  .slide2 ul{
    max-width: 1440px; margin: 0 auto 9.38em; 
  }
  .slide2 ul::after{
    content: ''; display: block; clear: both;
  }
  .slide2 ul li{
    float: left; width: 24%;
  }
  .slide2 ul li:not(:first-child){
    margin-left: 1%;
  }
  .slide2 ul li figure{
    box-sizing: border-box;
  }
  .slide2 ul li figure img{
    width: 100%; border-radius: 5px 5px 0 0; 
    min-height: 190px; display: block;
  }
  .slide2 ul li figure figcaption{
    background-color: white; padding: 1.88em 1.88em;
    box-shadow: 3px 3px 9px rgb(0, 0, 0, 0.2); 
    border-radius: 0 0 5px 5px;
  }
  .slide2 ul li figure figcaption h3{
    font-size: 30px; font-weight: 900; margin-bottom: 15px;
    max-width: 210px; 
  }
  .slide2 ul li figure figcaption p{
    font-size: 20px; max-width: 13.44em; line-height: 20px;
    margin-bottom: 5.63em; font-weight: 300;
  }
  .slide2 ul li figure figcaption small{
    font-size: 15px; font-weight: 400; color: #bdbdbd;
  }

  footer{
    background-color: #1c1d1c; padding: 7.19em 0;
  }
  footer > div{
    max-width: 1440px; margin: 0 auto;
  }
  footer h2{
    max-width: 15.94em; margin-bottom: 30px;
  }
  footer h2 a{
    display: block;
  }
  footer h2 a img{
    width: 100%;
  }
  footer p{
    font-size: 15px; font-weight: 300; color: white; 
  }
}

</style>
