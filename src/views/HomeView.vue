<script setup>
import Header from '../components/Header.vue'
import Banner from '../components/Banner.vue'
import Sidebar from '../components/Sidebar.vue'
</script>

<template>
  <Header/>
  <Banner/>
  <main class="flex">
    <Sidebar/>
    <div class="flex-1 p-10">


      <p class="text-3xl font-semibold">Visi & Misi Desa Tanjungrasa</p>
      <p class="text-lg font-semibold mt-4">Visi Desa Tanjungrasa</p>
      <p>Terwujudnya Penyelengaraan Pemerintah Desa Yang Siap Bersaing,Dalam Pembangunan, Pemberdayaan Masyarakat Dan Pembinanan Masyarakat Yang Berkualitas</p>
      <p class="text-lg font-semibold mt-4">Misi Desa Tanjungrasa</p>
      <ul>
        <li>Meningkatkan Tata Penyelengaraan Pelayanan Masyarkat Dan Pemerintahan Desa</li>
        <li>Meningkatkan Pembangunan Sarana Dan Prasarana Didalam Desa</li>
        <li>Meningkatkan Pembinaan Masyarakat Desa</li>
      </ul>
      

      <p class="text-3xl font-semibold my-4">Struktur Desa</p>
      <img src="@/assets/struktur-desa-tanjungrasa.png" alt=""/>
    </div>
  </main>
</template>

<style>
  body{
    background: #f1f1f1;
  }
</style>
