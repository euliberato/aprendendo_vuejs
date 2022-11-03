<template>
  <div>
    <PrimeiroComponente/>
    <p>{{descricao}}</p>
  </div>
</template>

<script>
  import PrimeiroComponente from './components/PrimeiroComponente.vue'

  export default {
    name: 'App',
    components: {
      PrimeiroComponente
    },
    data (){
      return {
        descricao: "Descricao do template"
      }
    }
  }
</script>