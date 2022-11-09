<template>
    <div>
        <h2>Esta é a descrição da pessoa: {{ nome }} [DEU CERTO]</h2>
        <Form/>
    </div>
</template>

<script>

import Form from './Form.vue';

export default {
    name: "Pessoa",
    components: {
        Form
    },
    data() {
        return {
            nome: "Ruan"
        };
    }
}
</script>