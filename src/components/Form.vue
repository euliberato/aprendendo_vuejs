<template>
    <div>
        <h2>Meu formulário: </h2>
        <form action="">
            <div><InputText/></div>
            <div><InputText/></div>
            <div><Submit/></div>
        </form>
        <h2>[TESTE]</h2>
    </div>
</template>

<script lang="ts">
import InputText from './Form/InputText.vue';
import Submit from './Form/Submit.vue';

    export default {
        name: 'Form',
        components: {
            InputText,
            Submit
        }
    }
</script>