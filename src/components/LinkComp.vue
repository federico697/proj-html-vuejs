<template>
    <button class="mr-50">
        {{nomeProps.link}}
    </button>
</template>

<script>
    export default {
        props:{
            nomeProps: Object
        }
    }
</script>

<style lang="scss" scoped>
.mr-50{
    margin-right: 50px;
}
</style>