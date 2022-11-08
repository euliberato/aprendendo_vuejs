<template>
  <div>
    <PrimeiroComponente/>
    <p>{{descricao}}</p>
    <LifeCycle/>
    <Pessoa />
    <Info />
  </div>
</template>

<script>
  import PrimeiroComponente from './components/PrimeiroComponente.vue'
  import LifeCycle from './components/LifeCycle.vue';
  import Pessoa from './components/Pessoa.vue';
  import Info from './components/Info.Vue';

  export default {
    name: 'App',
    components: {
    PrimeiroComponente,
    LifeCycle,
    Pessoa,
    Info
},
    data (){
      return {
        descricao: "Descricao do template"
      }
    }
  }
</script>