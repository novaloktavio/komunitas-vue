<template>
  <div class="home">
    <carousel :per-page="1" :autoplay="true" :loop="true">
      <slide style="max-height:450px">
        <img class="img-slider" style="height:100%" src="../../public/image/slider.jpg" alt="">
      </slide>
      <slide style="max-height:450px">
        <img class="img-slider" style="height:100%" src="../../public/image/gallery1.jpg" alt="">
      </slide>
      <slide style="max-height:450px">
        <img class="img-slider" style="height:100%" src="../../public/image/gallery7.jpg" alt="">
      </slide>
      <slide style="max-height:450px">
        <img class="img-slider" style="height:100%" src="../../public/image/gallery13.jpg" alt="">
      </slide>
      <slide style="max-height:450px">
        <img class="img-slider" style="height:100%" src="../../public/image/gallery12.jpeg" alt="">
      </slide>
      <slide style="max-height:450px">
        <img class="img-slider" style="height:100%" src="../../public/image/gallery14.jpg" alt="">
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
        <router-link class="btn-see" :to="{name: 'Gallery'}">SEE MY GALLERY</router-link>
        <!-- <a class="btn-see" href="#">SEE MY GALLERY</a> -->
      </div>
    </div>
    <div class="container">
      <div class="row my-work mb-5">
        <div class="col-12 my-4">
        <hr />
          <h5>M Y &nbsp;&nbsp;R E C E N T &nbsp;&nbsp;W O R K</h5>
        <hr />
        </div>
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
          <router-link class="btn-see" :to="{name: 'Gallery'}">SEE MORE</router-link>
          <!-- <a class="btn-see" href="#">SEE MORE</a> -->
        </div>
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
  @media (max-width:767px){
    .img-slider{
      width:100%;
      height:auto;
    }
  }
</style>