<template>
<section id="profil" class="container mx-auto px-6 py-20 flex flex-col md:flex-row items-center">
<div class="md:w-1/2 mb-10 md:mb-0">
<h1 class="text-5xl font-bold text-gray-800 mb-4 animate-slide-in-left" style="animation-delay:
200ms;">
Halo, Saya <span class="text-blue-600">Nama Anda</span>
</h1>
<p class="text-xl text-gray-600 mb-8 animate-slide-in-left" style="animation-delay: 400ms;">
Mahasiswa Teknik Informatika yang bersemangat dalam pengembangan web dan desain
antarmuka.
</p>

<a href="#kontak" class="bg-blue-600 text-white font-bold py-3 px-6 rounded-lg hover:bg-blue-
700 transition-colors duration-300 inline-block animate-slide-in-left" style="animation-delay:

600ms;">
Hubungi Saya
</a>
</div>
<div class="md:w-1/2 flex justify-center animate-slide-in-right">
<img src="https://via.placeholder.com/400" alt="Foto Profil" class="w-80 h-80 rounded-full
object-cover shadow-lg">
</div>
</section>
</template>
• SectionTitle.vue (Komponen kecil yang bisa dipakai ulang)
Code snippet
<script setup>
defineProps({ title: String });
</script>
<template>
<div class="mb-12 text-center">
<h2 class="text-4xl font-bold text-gray-800">{{ title }}</h2>

<div class="w-24 h-1 bg-blue-600 mx-auto mt-4 rounded"></div>
</div>
</template>
