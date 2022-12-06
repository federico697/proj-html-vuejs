<template>
    <button>
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
button{
    margin-right: 50px;
    padding: 8px;
    text-transform: uppercase;
    background-color: white;
    border: 4px solid rgb(255, 255, 255);
    font-weight: bold;
}
button:hover{
    background-color: #212529;
    color: white;
    border: 4px solid #0088cc;
}
.flex{
  display: flex;
}

</style>