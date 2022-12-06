<template>
    <section>
        <div class="flex border-bottom w-100 gap my-1">
            <div class="w-10">
                <img src="../assets/images/blog-55.jpg" alt="" class="w-100">
            </div>
            <div>
                <div>Simple Ways to Have a Pretty Face</div>
                <div>january 12, 2019</div>
            </div>
        </div>
        <div class="flex border-bottom w-100 gap my-1">
            <div class="w-10">
                <img src="../assets/images/blog-56.jpg" alt="" class="w-100">
            </div>
            <div>
                <div>Ranking the gratest players in basketball</div>
                <div>january 12, 2019</div>
            </div>
        </div>
        <div class="flex border-bottom w-100 gap my-1">
            <div class="w-10">
                <img src="../assets/images/blog-57.jpg" alt="" class="w-100">
            </div>
            <div>
                <div>4 Ways to Look Cool in Glasses</div>
                <div>january 12, 2019</div>
            </div>
        </div>
        <div class="flex border-bottom w-100 gap my-1">
            <div class="w-10">
                <img src="../assets/images/blog-58.jpg" alt="" class="w-100">
            </div>
            <div>
                <div>Top Camper Traliler Towing Tips</div>
                <div>january 12, 2019</div>
            </div>
        </div>
        <div class="flex gap my-1">
            <div class="w-10">
                <img src="../assets/images/blog-59.jpg" alt="" class="w-100">
            </div>
            <div>
                <div>5 Lovely Walks in New York</div>
                <div>january 12, 2019</div>
            </div>
        </div>
    </section>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
.container{
    width: 80%;
    margin: 0 auto;
}
.flex{
    display: flex;
}
.justify-content-between{
    justify-content: space-between;
}
.post-card{
    flex-basis: 32%;
}
.border-bottom{
    border-bottom: 2px solid #eeeeee;
}
.w-10{
    width: 10%;
}
.w-100{
    width: 100%;
}
img{
    margin-bottom: 15px;
}
.gap{
    gap: 15px;
}
.my-1{
    margin: 15px 0;
}
.bg-red{
    background-color: red;
}
</style>