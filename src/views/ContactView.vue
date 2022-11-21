
<template>
  
    <div class="contact">
      <Contact></Contact>
    </div>
  </template>
  
  <script>
  import Contact from '../components/Contact.vue'
  
  export default {
    name: 'ContactVue',
    components: {
      Contact
    }
    }
  </script>
  
  <style scoped>
  @media (min-width: 1024px) {
    .contact {
      max-height: 100vh;
      display: flex;
      align-items: center;
    }
  }
  </style>
  