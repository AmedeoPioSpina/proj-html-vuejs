<template lang="">
    <main>
        <MainContent />
        <LastContent />
    </main>
</template>
<script>
import MainContent from './MainContent.vue';
import LastContent from './LastContent.vue';
export default {
    name: "AppMain",
    components: {
        MainContent,
        LastContent
    }
}
</script>
<style lang="">
    
</style>