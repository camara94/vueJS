<script>
    export default {
        name: 'Detail',
        beforeCreate() { console.log('Je ne suis pas encore  créé') },
        created() { console.log('Je suis créé !') },
        beforeMount() { console.log('Je vais bientôt être monté sur le DOM!') },
        mounted() { console.log('Je suis monté sur le DOM!') }
    }
</script>

<template>
    {{ $route.params.name }}
</template>