<template>
    <div>
        <h2>Esta é a descrição da pessoa: {{ nome }} [DEU CERTO]</h2>
        <Info :email="email" :esta_trabalhando=true />
        <Form/>
    </div>
</template>

<script>

import Info from './Info.vue';
import Form from './Form.vue';

export default {
    name: "Pessoa",
    components: {
        Form,
        Info
    },
    data() {
        return {
            nome: "Ruan",
            email: 'ruanlib2@gmail.com'
        };
    }
}
</script>