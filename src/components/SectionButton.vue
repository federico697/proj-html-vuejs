<template>
    <section>
        <div class="container">
            <font-awesome-icon icon="fa-solid fa-chevron-left" />
            <div class="flex justify-content-between">
                <!-- componente figlio con il props -->
                <ButtonComp v-for="(elem, index) in buttons" :key="index" :nomeProps="elem"/>
            </div>
            <font-awesome-icon icon="fa-solid fa-chevron-right" />
        </div>
    </section>
</template>

<script>
import ButtonComp from './ButtonComp.vue';

    export default {
        components: {
            ButtonComp
        },
        data(){
            return{
                buttons: [
                    {
                        button: "gadgets"
                    },
                    {
                        button: "photography"
                    },
                    {
                        button: "lifestyle"
                    },
                    {
                        button: "fashion"
                    },
                    {
                        button: "recipes"
                    },
                    {
                        button: "travel"
                    },
                ]
            }
        }
    }
</script>

<style lang="scss" scoped>
section{
    background-color: #0088CC;
    padding: 50px 0;
}
.container{
    width: 75%;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.flex{
    display: flex;
}
.justify-content-between{
  justify-content: space-between;
  align-items: center;
}

</style>