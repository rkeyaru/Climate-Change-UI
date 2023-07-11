<script setup></script>

<template>
  <main>
    <div class="container text-center mt-5">
      <div class="text d-flex flex-column align-items-center justify-content-center">
        <div class="home-page-title w-50">
          <h1 class="text-heading px-5">
            Together, companies and consumers can halt climate change.
          </h1>
        </div>
        <div class="w-25">
          <p class="home-page-text lead">
            We help people consider the climate impacts of the brands they choose.
          </p>
        </div>
        <div class="w-25 mt-2">
          <button class="btn get-certify-button">GET CERTIFIED</button>
          <a class="link-dark ms-3 browse-certified-brand" href="">Browse Certified Brands</a>
        </div>

        <div class="mt-2 image-container">
          <img src="@/assets/image1.png" alt="Save environment" class="w-100 home-page-image" />
        </div>

        <div class="w-75">
          <div class="row">
            <div class="col-6 ps-5">
              <h2 class="w-50 title">The world needs a price on carbon</h2>
            </div>
            <div class="col-6 image-description-container w-50">
              <p class="image-description upper lead">
                Many governments have tried to find policy solutions.But their past attempts have
                fallen short of the scale and impace needed.
              </p>
              <p class="image-description lower lead">
                Carbon pricing would create incentives to lower carbon emissions and spur low carbon
                innovation.
              </p>
              <p class="m-0 p-0 text-start fw-bold">Why Go Neutral</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>
<style scoped>
.text-heading {
  color: #001414;
  font-family: Untitled Sans, Arial, sans-serif;
  font-weight: bold;
}
.home-page-text {
  font-size: 16px;
}
.get-certify-button {
  font-size: 12px;
  font-weight: 500;
  background-color: #cca65b;
  border-radius: 0;
}
.browse-certified-brand {
  font-size: 10px;
  text-underline-offset: 6px;
}
.image-container {
  padding-right: 16%;
}
.home-page-image {
  width: 115% !important;
}
.image-title {
  font-family: 'Open Sans', sans-serif;
  font-weight: bold;
}

.image-description {
  font-family: verdana;
  font-size: 12px;
}

.upper::first-letter {
  font-size: 300%;
  float: left;
  line-height: 1;
  display: inline-block;
}
.upper {
}
.lower {
  padding-right: 5%;
}
.title {
  margin-left: 30%;
}
</style>
