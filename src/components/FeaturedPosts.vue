<template>
    <section>
        <div class="card my-1">
            <div class="info info-bottom white">
                    <button class="badge white">lifestyle</button>
                    <h2>the best way to ride a motorcycle</h2> 
            </div>
        </div>
        <h4>featured author</h4>
            <div class="flex align-item-center">
                <div class="w-20">
                    <img src="../assets/images/avatar.jpg" alt="" class="w-100">
                </div>
                <div class="w-70 ml-30">
                    <div>John Doe</div>
                    <div>Lorem ipsum dolor, sit amet consectetur adipisicing eullam non molestias esse culpa facilis. Blanditiis, odit?</div>
                </div>
            </div>
    </section>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
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
.card{
    height: 200px;
    background-image:
    linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), 
    url('../assets/images/blog-66.jpg');
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    opacity: 1;
}
.info{
    position: relative;
    top: 130px;
    left: 20px;
    width: 90%;
}
.white{
    color: white;
}
.flex{
  display: flex;
}
.flex-col{
    flex-direction: column;
}
.justify-content-between{
  justify-content: space-between;
}
.align-item-center{
    align-items: center;
}
.w-20{
    width: 20%;
}
.w-70{
    width: 70%;
}
.w-100{
    width: 100%;
}
.ml-30{
    margin-left: 30px;
}
.my-1{
    margin: 30px 0;
}
h4{
    margin: 20px 0;
    margin-top: 5px;
}
</style>