<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <img src="../../resources/img/new/Tya_offerings1.jpg" alt="Jero Tya using antique prayer tools">
    <h3>
      
    </h3>
  </div>
</template>

<style scoped>
ul { margin: 0; }

img {
margin-top: 0px;
width: 100%;
height: auto;
border-radius: 5px;
border: 1px solid lime;
}

h1 {
  font-weight: 500;
  font-size: 2.6rem;
  
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
