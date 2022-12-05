<template>
  <header>
    <div id="intro-header">
      <div class="container flex white">
        <span>ciaociaociaociao</span>
        <ul class="flex">
          <li>ciao</li>
          <li>ciao</li>
          <li>ciao</li>
          <li>ciao</li>
        </ul>
      </div>
    </div>


    <div id="logo-header">
      <img src="../assets/images/logo-default-slim.png" alt="">
    </div>

    <div class="container border-top">
      <div id="navbar" class="flex justify-content-between">
      <div>ciao</div>
      <div>
        <font-awesome-icon icon="fa-solid fa-magnifying-glass" />
      </div>
    </div>
    </div>
    
  </header>
</template>

<script>
export default {
  name: 'HeaderComp',
  props: {
    msg: String
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
  width: 80%;
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
</style>
