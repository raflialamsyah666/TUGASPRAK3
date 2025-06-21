<template>
  <div id="carouselExample" class="carousel slide my-4" data-bs-ride="carousel">
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img class="d-block w-50 mx-auto" alt="carousel 1" />
      </div>
      <div class="carousel-item">
        <img  class="d-block w-50 mx-auto" alt="carousel 2" />
      </div>
      <div class="carousel-item">
        <img  class="d-block w-50 mx-auto" alt="carousel 3" />
      </div>
    </div>
    <button
      class="carousel-control-prev"
      type="button"
      data-bs-target="#carouselExample"
      data-bs-slide="prev"
    >
      <span class="carousel-control-prev-icon"></span>
    </button>
    <button
      class="carousel-control-next"
      type="button"
      data-bs-target="#carouselExample"
      data-bs-slide="next"
    >
      <span class="carousel-control-next-icon"></span>
    </button>
  </div>
</template>
