
<template>
  
    <div class="blog">
      <Blog></Blog>
    </div>
  </template>
  
  <script>
  import Blog from '../components/Blog.vue'
  
  export default {
    name: 'BlogVue',
    components: {
      Blog
    }
    }
  </script>
  
  <style scoped>
  @media (min-width: 1024px) {
    .blog {
      min-height: 100vh;
      display: flex;
      align-items: center;
    }
  }
  </style>