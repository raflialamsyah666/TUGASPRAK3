<template>
  <div class="col-md-4 mb-4">
    <div class="card h-100">
      <img :src="produk.img" class="card-img-top" :alt="produk.nama" />
      <div class="card-body">
        <h5 class="card-title">{{ produk.nama }}</h5>
        <p class="card-text">{{ produk.deskripsi }}</p>
        <a href="#" class="btn btn-primary">Beli Sekarang</a>
      </div>
    </div>
  </div>
</template>

<script setup>
defineProps({
  produk: Object
})
</script>
