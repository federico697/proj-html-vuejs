<template>
    <div>
        <SectionPhoto/>
        <SectionPosts/>
    </div>
</template>

<script>
import SectionPhoto from './SectionPhoto.vue';
import SectionPosts from './SectionPosts.vue';

    export default {
        name: 'MainComp',
        components: {
            SectionPhoto,
            SectionPosts
        }
    }
</script>

<style lang="scss" scoped>

</style>