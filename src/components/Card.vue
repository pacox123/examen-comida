<template>
    <grid>
        <img v-bind:src="url" :alt="nombre" :v-bind:descripcion="descripcion" :v-bind:costo="costo">
        <h4>{{nombre}}</h4>
        <p>{{descripcion}}</p>
        <h5>${{costo}}</h5>
        
    </grid>
</template>

<script>
import Grid from "./Grid.vue";
    export default{
    props: {
        url: {
            String
        },
        nombre: {
            String
        },
        descripcion: {
            String
        },
        costo: {
            String
        },
    },
    components: { Grid }
}
</script>

<style scoped>
    img{
        width: 12rem;
        height: 12rem;
        padding: 0.5rem;
        background-color: snow;
    }
    a{
        text-decoration: none;
        color: snow;
        background-color: #301675;
        padding: 0.3rem;
        border-radius: 5px;
        border: 1px solid #f2f2f2;
    }
</style>