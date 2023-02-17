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
      <h1 class="">{{ msg }}</h1>
      <h3>
        Laboratorio de sistemas y aplicaciones web
  
  email
  contacto@isclab.com.mx" 
  
      </h3><br>
      <h2>
        ¿QUÉ ES ISCLAB?
    </h2><br>
    <h3>
        Nos definimos como un laboratorio de la carrera de ISC, donde 
    buscamos el desarrollo de nuestros estudiantes a través de la creación 
    de proyectos que sean útiles a la sociedad.
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
}

h2 {
  font-size: 1.5rem;
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
