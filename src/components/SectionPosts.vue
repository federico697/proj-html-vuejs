<template>
        <section>
        <div class="container flex justify-content-between">
            <div class="post-card">
                <h4>popular posts</h4>
                <PopularPosts/>
            </div>
            <div class="post-card">
                <h4>recent posts</h4>
                <RecentPosts/>
            </div>
            <div class="post-card">
                <h4>featured posts</h4>
                <FeaturedPosts/>
            </div>
        </div>
    </section>
</template>

<script>
import PopularPosts from './PopularPosts.vue';
import RecentPosts from './RecentPosts.vue';
import FeaturedPosts from './FeaturedPosts.vue';
    export default {
        name: 'SectionPosts',
        components: {
            PopularPosts,
            RecentPosts,
            FeaturedPosts
        }
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