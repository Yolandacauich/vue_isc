<script setup>
import HelloWorld from './components/que_es_isclab.vue'
import Proyectos from './components/proyectos.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/Logo-removebg-preview.png" width="450" height="125" />

    <div class="wrapper">
      <HelloWorld msg="BIENVENIDO" />
    </div>
  </header>
  <main>
  <Proyectos />
</main>
</template>

<style scoped>
header {
  line-height: 1.5;
  text-align: justify;
}

main{
  line-height: 1.5;
  margin-left: 4.5;

}
.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
