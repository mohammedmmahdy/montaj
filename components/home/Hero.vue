<template>
  <fwb-carousel :pictures="pictures" slide animation slideInterval="5000"/>
</template>

<script setup>
import { FwbCarousel } from 'flowbite-vue'

const pictures = [
  {src: 'https://marketplace.canva.com/EAFIMHQ5yhE/1/0/1600w/canva-orange-and-teal-summer-sale-kids-fashion-bright-website-banner-L6kUMOWkkho.jpg', alt: 'Image 1'},
  {src: 'https://marketplace.canva.com/EAFj07TCU3Q/1/0/1600w/canva-cream-green-playful-kids-fashion-trends-twitter-header-uQwSJ7Tnmzc.jpg', alt: 'Image 2'},
  {src: 'https://marketplace.canva.com/EAFvzokLJlg/1/0/1600w/canva-red-and-white-illustration-fashion-store-twitter-header-Dy9wQG-7f34.jpg', alt: 'Image 3'},
]
</script>