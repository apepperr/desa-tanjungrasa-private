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


      <p class="text-3xl font-semibold">Visi & Misi Desa</p>
      <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Corporis, ipsam. Voluptatum vitae veniam numquam tempora asperiores odit nisi, ipsa minus corporis eos veritatis nulla rerum reiciendis iure nam eligendi aliquam! Lorem ipsum dolor sit amet consectetur, adipisicing elit. Corporis, ipsam. Voluptatum vitae veniam numquam tempora asperiores odit nisi, ipsa minus corporis eos veritatis nulla rerum reiciendis iure nam eligendi aliquam! Lorem ipsum dolor sit amet consectetur, adipisicing elit. Corporis, ipsam. Voluptatum vitae veniam numquam tempora asperiores odit nisi, ipsa minus corporis eos veritatis nulla rerum reiciendis iure nam eligendi aliquam! Lorem ipsum dolor sit amet consectetur, adipisicing elit. Corporis, ipsam. Voluptatum vitae veniam numquam tempora asperiores odit nisi, ipsa minus corporis eos veritatis nulla rerum reiciendis iure nam eligendi aliquam! Lorem ipsum dolor sit amet consectetur, adipisicing elit. Corporis, ipsam. Voluptatum vitae veniam numquam tempora asperiores odit nisi, ipsa minus corporis eos veritatis nulla rerum reiciendis iure nam eligendi aliquam!</p>

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
