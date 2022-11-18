<template>
    <div>
        <img :src="avatar" :alt="descricao">
        <MudarImage @mudar-imagem="trocarImagem"/>
    </div>
</template>

<script>

import MudarImage from './MudarImage.vue';

export default {
    name: "Picture",
    data() {
        return {
            avatar: "/img/avatar.png",
            descricao: "Ruan Liberato"
        };
    },
    components: { 
        MudarImage 
    },
    methods: {
        trocarImagem(){
            console.log('olá');
        }
    }
}
</script>