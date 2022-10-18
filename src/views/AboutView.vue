<template>
  <div class="container w-75">
    <h4 class="text-center">About Us</h4>
    <div class="about-card">
      <div class="row">
        <div class="col-lg-6 text-center">
          <img class="about-photo" src="/public/Photos/PierreFilm.jpeg" />
          <p>Pierre Malan Jacobs</p>
        </div>
        <div class="col-lg-6 text-center">
          <img class="about-photo" src="/public/Photos/LisaFilm.jpeg" />
          <p>Lisa Jacobs</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    /* min-height: 100vh; */
    display: flex;
    align-items: center;
  }
}

.about-photo {
  height: 275px;
  border-radius: 10em;
  margin-bottom: 1em;
  margin-right: auto !important;
  margin-left: auto !important;
  place-items: center;
}
</style>
