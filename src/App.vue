<template>
  <div id="app">
    <div class="col-12 pt-5">
      <h2>N O V A L &nbsp&nbspO K T A V I O</h2>
    </div>
    <nav class="navbar navbar-expand-lg sticky-top">
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
  </div>
</template>

<style>
.navbar{
  background: #fff;
}
.navbar ul li a{
  color: #2c3e50;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
