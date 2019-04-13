<template>
  <div class="about">
    <div class="container">
      <div class="row">
        <div class="col-12 card-columns mt-5">
          <div class="card card-pin">
            <img class="card-img" src="../../public/image/gallery12.jpg" alt="Card image">
            <div class="overlay">
            </div>
          </div>
          <div class="card card-pin">
            <img class="card-img" src="../../public/image/gallery1.jpg" alt="Card image">
            <div class="overlay">
            </div>
          </div>
          <div class="card card-pin">
            <img class="card-img" src="../../public/image/gallery17.jpg" alt="Card image">
            <div class="overlay">
            </div>
          </div>
          <div class="card card-pin">
            <img class="card-img" src="../../public/image/gallery16.jpg" alt="Card image">
            <div class="overlay">
            </div>
          </div>
          <div class="card card-pin">
            <img class="card-img" src="../../public/image/gallery18.jpg" alt="Card image">
            <div class="overlay">
            </div>
          </div>
          <div class="card card-pin">
            <img class="card-img" src="../../public/image/gallery19.jpg" alt="Card image">
            <div class="overlay">
            </div>
          </div>
          <div class="card card-pin">
            <img class="card-img" src="../../public/image/gallery7.jpg" alt="Card image">
            <div class="overlay">
            </div>
          </div>
          <div class="card card-pin">
            <img class="card-img" src="../../public/image/gallery20.jpg" alt="Card image">
            <div class="overlay">
            </div>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-12 card-columns mt-5">
          <div class="card card-pin">
            <img class="card-img" src="../../public/image/gallery13.jpg" alt="Card image">
            <div class="overlay">
            </div>
          </div>
          <div class="card card-pin">
            <img class="card-img" src="../../public/image/gallery14.jpg" alt="Card image">
            <div class="overlay">
            </div>
          </div>
          <div class="card card-pin">
            <img class="card-img" src="../../public/image/analog1.jpg" alt="Card image">
            <div class="overlay">
            </div>
          </div>
          <div class="card card-pin">
            <img class="card-img" src="../../public/image/analog2.jpg" alt="Card image">
            <div class="overlay">
            </div>
          </div>
          <div class="card card-pin">
            <img class="card-img" src="../../public/image/analog3.jpg" alt="Card image">
            <div class="overlay">
            </div>
          </div>
          <div class="card card-pin">
            <img class="card-img" src="../../public/image/analog4.jpg" alt="Card image">
            <div class="overlay">
            </div>
          </div>
          <div class="card card-pin">
            <img class="card-img" src="../../public/image/analog5.jpg" alt="Card image">
            <div class="overlay">
            </div>
          </div>
          <div class="card card-pin">
            <img class="card-img" src="../../public/image/analog6.jpg" alt="Card image">
            <div class="overlay">
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
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