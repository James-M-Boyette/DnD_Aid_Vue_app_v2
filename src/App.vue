<template>
  <div id="app">
    <div id="page-wrapper">
      <!-- Header -->
      <section id="header">
        <div class="container">
          <div class="row">
            <div class="col-12">
              <!-- Logo -->
              <h1><a href="index.html" id="logo">Halcyonic</a></h1>

              <!-- Nav -->
              <nav id="nav">
                <!-- <a href="index.html">Homepage</a>
                <a href="threecolumn.html">Three Column</a>
                <a href="twocolumn1.html">Two Column #1</a>
                <a href="twocolumn2.html">Two Column #2</a>
                <a href="onecolumn.html">One Column</a> -->
              </nav>
            </div>
          </div>
        </div>
        <div id="banner">
          <div class="container">
            <div class="row">
              <div class="hero-j">
                <!-- <img class="hero-image" src="~@/assets/Imgs/DnDAidLogo.png" alt="" /> -->
                <img class="hero-image" src="~@/assets/Imgs/DnDAidLogo.png" href="/home" />
                <!-- <button class="hero-image"></button> -->
              </div>
            </div>
          </div>
        </div>
        <div class="container">
          <div class="row">
            <div class="col-12">
              <!-- Logo -->
              <h1><a href="index.html" id="logo">Halcyonic</a></h1>

              <!-- Nav -->
              <nav id="nav">
                <a href="index.html">Homepage</a>
                <a href="threecolumn.html">Three Column</a>
                <a href="twocolumn1.html">Two Column #1</a>
                <a href="twocolumn2.html">Two Column #2</a>
                <a href="onecolumn.html">One Column</a>
              </nav>
            </div>
          </div>
        </div>
      </section>

      <!-- Footer -->
      <section id="footer">
        <div class="container">
          <div class="row">
            <div class="col-8 col-12-medium">
              <!-- Links -->
              <section></section>
            </div>
          </div>
        </div>
      </section>

      <!-- Copyright -->
      <div id="copyright">
        &copy; Untitled. All rights reserved. | Design:
        <a href="http://html5up.net">HTML5 UP</a>
      </div>
    </div>
    <router-view />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
.hero-j {
  padding: 50px;
  /* size: 100%; */
  text-align: center;
  background-position: center;
  background-repeat: no-repeat;
  /* background-size: 100% 100%; */
  /* background-size: cover; */
  /* height: 100%;
  width: contain; */
  position: relative;
  /* background: #1abc9c; */
  /* background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)),
    url("~@/assets/Imgs/Banners/BlackHex50bluer.png"); */
  /* background-image: url("~@/assets/Imgs/Banners/BlackHex50.png"); */
  /* filter: saturate(200%); */
  /* filter: hue-rotate(20deg); */
  color: white;
  font-size: 30px;
}
</style>
