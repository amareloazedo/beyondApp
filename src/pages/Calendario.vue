<template>
    <v-app>
        Tela de Calendário
    </v-app>
</template>

<script>

    export default {

        methods: {
        goTo(path) {
        this.$router.push(path)
        }
   } 
}
    
</script>