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
      <h1 class="QUE PROYECTOS REALIZAMOS">{{ msg }}</h1>
      <h2>
        ¿QUÉ REALIZARA ISCLAB?
    </h2><br>
    <h3>
        Nuestro laboratorio está pensado para programadores por lo que los productos que creamos se categorizan como software.
    </h3>
    </div>

  </template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}

h3 {
  font-size: 1.5rem;
  text-align: justify;

}

h2 {
  font-size: 1.5rem;
}


.greetings h1,
.greetings h3 {
  text-align: justify;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
