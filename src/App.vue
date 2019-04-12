<template>
  <div id="app">
    <div class="col-12 pt-2">
      <h2 style="font-size:4vh !important;">N O V A L &nbsp;&nbsp;O K T A V I O</h2>
    </div>
    <nav class="navbar navbar-expand-lg navbar-light sticky-top">
      <!-- <a class="navbar-brand" href="#">Photonesia</a> -->
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav" style="justify-content: center;">
        <ul class="navbar-nav">
          <li class="nav-item active">
            <a class="nav-link" href="#">HOME <span class="sr-only">(current)</span></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">GALLERY</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">ABOUT</a>
          </li>
        </ul>
      </div>
    </nav>
    <router-view/>
    <div class="footer row p-3">
      <div class="col-xs-4 col-md-4 col-lg-4 px-4 mt-4 text-left">
       <h6><b>ABOUT ME</b></h6>
        <span style="font-size:14px">My name is Noval Oktavio. I'm a photography hobbyst. <br>I'm from Bandung, Indonesia.</span>
      </div>
      <div class="col-xs-4 col-md-4 col-lg-4 px-4 mt-4 text-left">
       <h6><b>CONTACT</b></h6>
        <span style="font-size:14px;color: #e2e2e2;">081214845674</span><br>
        <span style="font-size:14px;color: #e2e2e2;">novaloktavio@gmail.com</span>
      </div>
      <div class="col-xs-4 col-md-4 col-lg-4 px-4 mt-4 text-left">
        <h6><b>FIND ME</b></h6>
      </div>
    </div>
  </div>
</template>

<style>
.navbar{
  background: #fff;
}
.navbar ul li a{
  color: #2c3e50;
}
.footer{
  background: #232323;
  color: #fff;
  min-height: 150px;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin: 15px 15px 0 15px;
}
</style>
