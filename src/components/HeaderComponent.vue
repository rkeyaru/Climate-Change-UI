<template>
  <div class="certified-brand text-center py-3 fw-bold container-fluid">
    CHECK OUT THE 100+ CERTIFIED BRANDS
  </div>
  <div class="container-xxl">
    <nav class="navbar navbar-expand-lg navbar-light mt-3">
      <div class="container-fluid">
        <a class="navbar-brand fw-bold" href="#"><img src="@/assets/logo.svg" alt="" /></a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNavAltMarkup"
          aria-controls="navbarNavAltMarkup"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
          <div class="navbar-nav ms-auto">
            <a class="nav-link fw-bold mx-2" href="#">Why Go Neutral?</a>
            <a class="nav-link fw-bold mx-2" href="#">How It Works</a>
            <a class="nav-link fw-bold mx-2" href="#">Certified Brands</a>
            <a class="nav-link fw-bold mx-2" href="#">Consumers</a>
            <a class="nav-link fw-bold mx-2" href="#">FAQ</a>
            <a class="nav-link fw-bold mx-2" href="#">About</a>
            <a class="btn join-us mx-2 me-5" href="">JOIN US</a>
          </div>
        </div>
      </div>
    </nav>
  </div>
</template>
<style scoped>
.certified-brand {
  background-color: #cca65b;
}
.nav-link {
  color: #3d4b4a !important;
}
.navbar-brand {
  font-size: 17px;
}
.join-us {
  background-color: black;
  color: whitesmoke;
  font-size: 15px;
  border-radius: 0;
  line-height: -0.5;
}
</style>
