<script setup src="https://unpkg.com/aos@next/dist/aos.js">
import TheWelcome from '../components/TheWelcome.vue'

    AOS.init({
        offset: 400,
        duration: 1500
    });
    </script>


<template>
  <main>
    <TheWelcome />
  </main>
</template>

