<template>
  <div>
    <h1>Olá Vue! [Teste]</h1>
    <MultiplosEventos/>
  </div>
</template>

<script>

import MultiplosEventos from './MultiplosEventos.vue';


export default {
    default: {
        name: "PrimeiroComponente",
        components: {
            MultiplosEventos
        },
        data() {
            return {
                nome: "Matheus",
                profissao: "Programador"
            };
        }
    },
    components: { MultiplosEventos, MultiplosEventos }
}
</script>