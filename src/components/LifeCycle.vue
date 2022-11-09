<template>
  <h1>Meu nome é {{ nome }} [Teste]</h1>
  <Info />
</template>

<script>
import Info from './Info.vue'

export default {
  name: 'LifeCycle',
  components: {
    Info
  },
  data() {
    return { 
      nome: "Ainda não sei"
    }
  },
  created() {
    setTimeout(() => {
      this.nome = "Ruan"
    }, 1000);

    this.lifeCycle()
  },
  mounted() {
    setTimeout(() => {
      this.nome = "Liberato"
    }, 2000);

    this.lifeCycle()
  },
  methods: {
    lifeCycle() {
      console.log("Executou");
    }
  }
}
</script>