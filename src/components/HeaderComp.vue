<template>
  <header>
    <div id="intro-header">
      <div class="container flex white">
        <span class="mr-1">Everything about Lifestyle, Travel and Gadgets!</span>
        <div class="flex">
          <div class="mr-1">sign in</div>
          <div class="mr-1">about us</div>
          <div class="mr-1">contact us</div>
          <div class="mr-1">buy now</div>
        </div>
      </div>
    </div>


    <div id="logo-header">
      <img src="../assets/images/logo-default-slim.png" alt="">
    </div>

    <div class="container border-top">
      <div id="navbar" class="flex justify-content-between">
        <div>
          <!-- componente figlio con i props -->
          <LinkComp v-for="(elem, index) in links" :key="index" :nomeProps="elem"/>
        </div>
        <div>
          <font-awesome-icon icon="fa-solid fa-magnifying-glass" />
        </div>
    </div>
    </div>
    
  </header>
</template>

<script>
import LinkComp from './LinkComp.vue';

export default {
  name: 'HeaderComp',
  components: {
    LinkComp
  },
  data(){
    return{
      links: [
        {
          link: "home"
        },
        {
          link: "elements"
        },
        {
          link: "features"
        },
        {
          link: "pages"
        },
        {
          link: "portfolio"
        },
        {
          link: "blog"
        },
        {
          link: "shop"
        }
      ]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
#intro-header{
  background-color: #0088CC;
}
.container,
#logo-header,
#navbar{
  margin: 0 auto;
  width: 75%;
  padding: 10px 0;
}
.border-top{
  border-top: 1px solid #EEEEEE;
  width: 100%;
}
.flex{
  display: flex;
}
.justify-content-between{
  justify-content: space-between;
  align-items: center;
}
li{
  margin-left: 20px;
}
.white{
  color: white;
}
img{
  width: 10%;
  padding: 20px 0;
}
.mr-1{
  margin-right: 20px;
}
</style>
