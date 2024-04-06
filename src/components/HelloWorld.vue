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
    <h2 style="color: white;">ARDHIKA FACRIZ SUSILO</h2>
    <h3 style="font-size: 15px;">
      <p><i class="bi bi-envelope-at"> ardhika.facriz@gmail.com</i> | <i class="bi bi-telephone"> 0898-8888-8888</i></p>
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 700;
  font-size: 2.1rem;
  position: relative;
  top: -10px;
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
