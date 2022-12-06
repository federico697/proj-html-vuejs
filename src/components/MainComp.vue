<template>
    <div>
        <SectionPhoto/>
        <SectionPosts/>
        <SectionButton/>
        <LastSection/>
    </div>
</template>

<script>
import SectionPhoto from './SectionPhoto.vue';
import SectionPosts from './SectionPosts.vue';
import SectionButton from './SectionButton.vue';
import LastSection from './LastSection.vue'

    export default {
        name: 'MainComp',
        components: {
            SectionPhoto,
            SectionPosts,
            SectionButton,
            LastSection
        }
    }
</script>

<style lang="scss" scoped>

</style>