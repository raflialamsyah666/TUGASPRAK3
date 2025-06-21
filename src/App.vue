<template>
  <div>
    <Navbar />
    <Carousel />
    <section class="container my-5">
      <h2 class="text-center mb-4">Produk Terbaru</h2>
      <div class="row">
        <ProductCard
          v-for="(produk, index) in produkList"
          :key="index"
          :produk="produk"
        />
      </div>
    </section>
    <Footer />
  </div>
</template>

<script setup>
import Navbar from './components/Navbar.vue'
import Carousel from './components/Carousel.vue'
import ProductCard from './components/ProductCard.vue'
import Footer from './components/Footer.vue'

const produkList = [
  { nama: 'Produk 1', deskripsi: 'Deskripsi produk 1', img: '/img/product1.jpg' },
  { nama: 'Produk 2', deskripsi: 'Deskripsi produk 2', img: '/img/product2.jpg' },
  { nama: 'Produk 3', deskripsi: 'Deskripsi produk 3', img: '/img/product3.jpg' }
]
</script>
