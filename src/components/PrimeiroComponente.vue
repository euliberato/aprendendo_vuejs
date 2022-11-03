<template>
    <div>
      <h1>Olá, Vue!</h1>
      <br>
      <p>Nome {{ nome }} e sou {{ ocupacao }}</p>
    </div>
</template>

<script>
  export default {
    name: 'PrimeiroComponente',
    data(){
      return {
        nome: "Ruan",
        ocupacao: "Estudante"
      }
    }
  }
</script>

<style>
  h1 {
    background: #fff;
    border-radius: 10px;
    color: #000;
    padding: 10px;
  }
</style>