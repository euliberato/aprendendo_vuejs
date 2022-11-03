<template>
  <div>
    <PrimeiroComponente/>
    <p>{{descricao}}</p>
    <LifeCycle/>
  </div>
  
</template>

<script>
  import PrimeiroComponente from './components/PrimeiroComponente.vue'
  import LifeCycle from './components/LifeCycle.vue';

  export default {
    name: 'App',
    components: {
      PrimeiroComponente,
      LifeCycle
    },
    data (){
      return {
        descricao: "Descricao do template"
      }
    }
  }
</script>