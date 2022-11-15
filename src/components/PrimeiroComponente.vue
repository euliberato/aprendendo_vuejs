<template>
  <div>
    <h1>Olá Vue! [Teste]</h1>
    <MultiplosEventos/>
    <Reutilizacao/>
    
  </div>
</template>

<script>

import MultiplosEventos from './MultiplosEventos.vue';
import Reutilizacao from './Reutilizacao.vue';


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
    components: { MultiplosEventos, Reutilizacao }
}
</script>