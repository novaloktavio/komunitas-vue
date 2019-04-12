<template>
  <div class="home">
    <carousel :per-page="1" :autoplay="true" :loop="true">
      <slide style="max-height:450px">
        <img style="height:100%" src="../../public/image/slider.jpg" alt="">
      </slide>
      <slide style="max-height:450px">
        <img style="height:100%" src="../../public/image/gallery1.jpg" alt="">
      </slide>
      <slide style="max-height:450px">
        <img style="height:100%" src="../../public/image/gallery7.jpg" alt="">
      </slide>
      <slide style="max-height:450px">
        <img style="height:100%" src="../../public/image/gallery13.jpg" alt="">
      </slide>
      <slide style="max-height:450px">
        <img style="height:100%" src="../../public/image/gallery12.jpeg" alt="">
      </slide>
      <slide style="max-height:450px">
        <img style="height:100%" src="../../public/image/gallery14.jpg" alt="">
      </slide>
    </carousel>
    <div class="row p-4 my-5">
      <div class="col-12">
        <h3>T H I S &nbsp;&nbsp;I S &nbsp;&nbsp;M E</h3>
        <p>I love photography since 2013, but my first DSLR Camera in 2018.<br />
          I like to take any photos like portraits, minimalism, landscape, street, etc.
        </p>
      </div>
      <div class="col-12 mt-3">
        <a class="btn-see" href="#">SEE MY GALLERY</a>
      </div>
    </div>
    <div class="row my-work mb-5">
      <div class="col-12 my-4">
      <hr />
        <h3>M Y &nbsp;&nbsp;R E C E N T &nbsp;&nbsp;W O R K</h3>
      <hr />
      </div>
      <!-- <div class="col-12 card-columns">
        <div class="card card-pin">
          <img class="card-img"
            src="../../public/image/gallery12.jpg"
            alt="Card image">
          <div class="overlay">
            <h3 class="card-title title">Some Title</h3>
            <div class="download">
              <a href="http://lorempixel.com/486/320/" download>
                <i class="fa fa-download" aria-hidden="true"></i>
              </a>
            </div>
            <div class="more">
              <a href="#!">
                <i class="fa fa-arrow-circle-o-right" aria-hidden="true"></i> More
              </a>
            </div>
          </div>
        </div>
        <div class="card card-pin">
          <img class="card-img"
            src="../../public/image/gallery1.jpg"
            alt="Card image">
          <div class="overlay">
            <h3 class="card-title title">Some Title</h3>
            <div class="more">
              <a href="#!">
                <i class="fa fa-arrow-circle-o-right" aria-hidden="true"></i> More
              </a>
            </div>
          </div>
        </div>
        <div class="card card-pin">
          <img class="card-img"
            src="../../public/image/gallery17.jpg"
            alt="Card image">
          <div class="overlay">
            <h3 class="card-title title">Some Title</h3>
            <div class="more">
              <a href="#!">
                <i class="fa fa-arrow-circle-o-right" aria-hidden="true"></i> More
              </a>
            </div>
          </div>
        </div>
        <div class="card card-pin">
          <img class="card-img"
            src="../../public/image/gallery16.jpg"
            alt="Card image">
          <div class="overlay">
            <h3 class="card-title title">Some Title</h3>
            <div class="more">
              <a href="#!">
                <i class="fa fa-arrow-circle-o-right" aria-hidden="true"></i> More
              </a>
            </div>
          </div>
        </div>
      </div> -->
      <div class="col-xs-4 col-md-4 mb-4">
        <img width="100%" src="../../public/image/gallery1.jpg">
      </div>
      <div class="col-xs-4 col-md-4 mb-4">      
        <img width="100%" src="../../public/image/gallery7.jpg">
      </div>
      <div class="col-xs-4 col-md-4 mb-4">
        <img width="100%" src="../../public/image/gallery10.jpg">
      </div>
      <div class="col-xs-4 col-md-4 mb-4">
        <img width="100%" src="../../public/image/gallery13.jpg">
      </div>
      <div class="col-xs-4 col-md-4 mb-4">
        <img width="100%" src="../../public/image/gallery11.jpg">
      </div>
      <div class="col-xs-4 col-md-4 mb-4">
        <img width="100%" src="../../public/image/gallery.jpg">
      </div>
      <div class="col-12 mt-3">
        <a class="btn-see" href="#">SEE MORE</a>
      </div>
    </div>
  </div>
</template>

<script>
  export default {}
</script>

<style>
  .btn-see {
    background: #232323;
    color: #fff;
    padding: 14px;
    border-radius: 50px;
    text-decoration: none;
    font-size: 14px;
    transition: ease .5s;
    border: 1px solid #232323
  }
  .btn-see:hover{
    color: #232323;
    border: 1px solid #232323;
    background: #ffffff;
    transition: ease .5s;
    text-decoration: none;
  }
  .text-muted a {
    color: #989898;
  }
  .text-muted a:hover {
    color: grey;
  }
  .fa a:active,
  a:hover,
  a:visited {
    text-decoration: none;
  }
  .general .card-title {
    color: #f3f3f3;
  }
  .general .card-text {
    color: #f3f3f3;
  }
  .card-img {
    display: block;
    width: 100%;
    height: auto;
  }
  .overlay {
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    height: 100%;
    width: 100%;
    opacity: 0;
    transition: .2s ease;
    background-color: #000;
  }
  .card-pin:hover .overlay {
    opacity: .5;
    /* border: 5px solid #f3f3f3; */
    transition: ease .5s;
    background-color: #000000;
  }
  .more {
    color: white;
    font-size: 20px;
    position: absolute;
    bottom: 0;
    right: 0;
    text-transform: uppercase;
    transform: translate(-20%, -20%);
    -ms-transform: translate(-50%, -50%);
  }
  .card-pin:hover .card-title {
    color: #ffffff;
    margin-top: 10px;
    text-align: center;
    font-size: 1.2em;
  }
  .card-pin:hover .more a {
    text-decoration: none;
    color: #ffffff;
  }
  .card-pin:hover .download a {
    text-decoration: none;
    color: #ffffff;
  }
</style>