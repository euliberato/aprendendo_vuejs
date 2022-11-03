<template>
    <h1>[Teste de Life Cycle] Chamando: [data.nome] => [{{ nome }}]</h1>
</template>

<script>
    export default {
        name: 'LyfeCycle',
        data(){
            return {
                nome: 'Undefined'
            }
        },
        created(){
            setTimeout(() => {
                this.nome = 'Teste'
            }, 1000);
        },
        mounted(){
            setTimeout(() => {
                this.nome = 'Teste2'
            }, 2000);
        }
    }
</script>