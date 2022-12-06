<template>
    <section>
        <div class="container flex flex-wrap justify-content-between white">
            <div class="card card-1">
                <div class="info">
                    <button class="badge">photography</button>
                    <h2>How To Take Better Concert Pictures in 30 Seconds</h2>
                    <p class="dis-non">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab autem aut ipsum, natus nemo consequatur vero dicta deleniti mollitia velit corrupti repudiandae deserunt consectetur incidunt debitis! Voluptate tempore necessitatibus nulla?</p> 
                </div>
            </div>
            <div class="card card-2">
                <div class="info">
                    <button class="badge">gadgets</button>
                    <h2>gadgets that make your smartphone even smarter</h2> 
                    <p class="dis-non">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab autem aut ipsum, natus nemo consequatur vero dicta deleniti mollitia velit corrupti repudiandae deserunt consectetur incidunt debitis! Voluptate tempore necessitatibus nulla?</p> 
                </div>
            </div>
            <div class="card card-3">
                <div class="info">
                    <button class="badge">travel</button>
                    <h2>20 top-rated tourist attractions in manhattan</h2> 
                    <p class="dis-non">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab autem aut ipsum, natus nemo consequatur vero dicta deleniti mollitia velit corrupti repudiandae deserunt consectetur incidunt debitis! Voluptate tempore necessitatibus nulla?</p> 
                </div>
            </div>
            <div class="card card-4 margin-top-30">
                <div class="info info-bottom">
                    <button class="badge">lifestyle</button>
                    <h2>the best way to ride a motorcycle</h2> 
                    <p class="dis-non">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab autem aut ipsum, natus nemo consequatur vero dicta deleniti mollitia velit corrupti repudiandae deserunt consectetur incidunt debitis! Voluptate tempore necessitatibus nulla?</p> 
                </div>
            </div>
            <div class="card card-5 margin-top-30">
                <div class="info info-bottom">
                    <button class="badge">travel</button>
                    <h2>5 fun Things to Do at the Beach</h2> 
                    <p class="dis-non">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab autem aut ipsum, natus nemo consequatur vero dicta deleniti mollitia velit corrupti repudiandae deserunt consectetur incidunt debitis! Voluptate tempore necessitatibus nulla?</p> 
                </div>
            </div>
            <div class="card card-6 margin-top-30">
                <div class="info">
                    <button class="badge">recipes</button>
                    <h2>amazingly fresh fruit and herb drinks for summer</h2> 
                    <p class="dis-non">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab autem aut ipsum, natus nemo consequatur vero dicta deleniti mollitia velit corrupti repudiandae deserunt consectetur incidunt debitis! Voluptate tempore necessitatibus nulla?</p> 
                </div>
            </div>
        </div>
    </section>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
section{
    background-color: #f7f7f7;
    padding: 20px 0;
}
.white{
    color: white;
}
.container{
  margin: 0 auto;
  width: 75%;
  padding: 50px 0;
}
.flex{
    display: flex;
}
.flex-wrap{
    flex-wrap: wrap;
}
.justify-content-between{
  justify-content: space-between;
}
.card{
 flex-basis: 32%;
 height: 250px;
 background-size: cover;
 background-repeat: no-repeat;
 background-position: center;

 .dis-non{
    display: none;
 }
}
.card:hover{
 border: 4px solid #ffffff;

 .info{
    position: relative;
    top: 50px;
 }
 .dis-non{
    display: block;
 }
}
.card-1{
    background-image: 
    linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), 
    url('../assets/images/blog-46.jpg');
}
.card-2{
    background-image: 
    linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)),  
    url('../assets/images/blog-47.jpg');
}
.card-3{
    background-image:
    linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)),  
    url('../assets/images/blog-48.jpg');
}
.card-4{
    background-image:
    linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)),  
    url('../assets/images/blog-49.jpg');
}
.card-5{
    background-image:
    linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)),  
    url('../assets/images/blog-50.jpg');
}
.card-6{
    background-image:
    linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)),  
    url('../assets/images/blog-51.jpg');
}
.info{
    position: relative;
    top: 150px;
    left: 20px;
    width: 90%;
}
.info-bottom{
    top: 180px;
}
.badge{
    padding: 4px 10px;
    margin-bottom: 5px;
    border-radius: 3px;
    background-color: #0088CC;
    display: flex;
    align-items: center;
    justify-content: center;
    border: none;
    cursor: pointer;
}
.margin-top-30{
    margin-top: 30px;
}
.h-200{
    height: 200px;
}
</style>