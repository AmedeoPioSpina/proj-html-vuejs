<template lang="">
    <footer>
        <NewsLetters />
        <UsefulLinks />
        <FooterBand />
    </footer>
</template>
<script>
import NewsLetters from './NewsLetters.vue';
import UsefulLinks from './UsefulLinks.vue';
import FooterBand from './FooterBand.vue';
export default {
    name: "AppFooter",
    components:{
        NewsLetters,
        UsefulLinks,
        FooterBand
    }
}
</script>
<style lang="">
    
</style>