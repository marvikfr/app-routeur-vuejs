<template>
    <div>
        <h1>Voici la PAGE 2</h1>
        <div v-on:click="goDebut" class="btn btn-warning">Retour à l'accueil</div>
    </div>
</template>

<script>
    export default {
        name: 'Page2',
        
        methods: {
            goDebut: function(){
            this.$router.push('/')
            }
        }
    }


</script>


<style>

</style>