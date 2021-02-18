<template>
    <div>
        <nav>
            <a href="/home">Accueil</a> | 
            <a href="/about">A propos</a> |
            <a href="/contact">Contactez-nous !</a>
        </nav>
        <hr />
        <div>{{ message }} </div>
        <div> {{ $route.params.name }} </div>
    </div>

</template>

<script>
    export default {
        name: 'HomeLink',
        props: {
            message: String
        }
    }
</script>