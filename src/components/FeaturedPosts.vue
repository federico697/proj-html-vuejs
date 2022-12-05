<template>
    <section>
        <div class="card">
            <div class="info info-bottom white">
                    <button class="badge white">lifestyle</button>
                    <h2>the best way to ride a motorcycle</h2> 
            </div>
        </div>
        <h4>featured author</h4>
            <div>
                <div>

                </div>
                <div>

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
    background-image: url('../assets/images/blog-66.jpg');
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
</style>