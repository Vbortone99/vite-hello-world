<template>
    <header>
        <h1>{{ titleText }}</h1>
    </header>
</template>

<script>
    export default {
        name:'AppTitle',
        data(){
            return {
                titleText:'La mia prima app con Vite!'
            }
        }
    }
</script>

<style lang="css" scoped>
    h1{
     text-align: center;
     color: var(color darkgreen);
    }
</style>