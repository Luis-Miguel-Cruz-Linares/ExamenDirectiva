<template> 
   <Grid>
    <img v-bind:src="url" v-bind:alt="nombre">
    <h2>{{nombre}}</h2>
    <p>{{descripcion}}</p>
    <h3>{{precio}}</h3>
    <a :href="url" target="_blank">Ordenar</a>
    <a :href="url" target="_blank">Ver más</a>
    
   </grid> 
</template>

<script>
import Grid from './Grid.vue';
import a from './a.vue';
    export default {
    props: {
        url: {
            String,
        },
        nombre: {
            String,
        },
        descripcion: {
            String,
        },
        precio: {
            String,
        }
    },
    components: { Grid, a }
};
</script>

<style scoped>
   
    img {
        width: 8rem;
        height: 8rem;
        padding: 0.5rem;
        background: rgb(122, 192, 122);
    }
    a {
        text-decoration: none;
        color: snow;
        background: #301675;
        padding: 0.3rem;
        border-radius: 5px;
        border: 1px solid #f2f2f2;
    }
</style>