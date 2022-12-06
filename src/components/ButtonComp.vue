<template>
        <span>
            {{nomeProps.button}}
        </span>
</template>

<script>
    export default {
        props:{
            nomeProps: Object
        }
    }
</script>

<style lang="scss" scoped>
span{
    margin-right: 20px;
    padding: 30px 50px;
    text-transform: uppercase;
    background-color: #000000;
    color: white;
    border: none;
    font-weight: bold;
    font-size: 12px;
    cursor: pointer;
}
span:hover{
    padding: 25px 45px;
}
</style>