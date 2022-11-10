<template>
    <div>
        {{message}}
    </div>
</template>

<script>
    export default {
        name: 'AppTitle',
        data:{
            message: "La mia prima app con Vite!"
        }
    }
</script>

<style lang="css" scoped>
    div{
        font-size: 50px;
        color: red;
    }
</style>