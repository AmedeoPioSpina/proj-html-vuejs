<template lang="">
    <header>
        <NavContainer />
        <JumbotronContainer />
        <IntroContents />
    </header>
</template>
<script>
import NavContainer from './NavContainer.vue';
import JumbotronContainer from './JumbotronContainer.vue';
import IntroContents from './IntroContents.vue';
export default {
    name: "AppHeader",
    components:{
        NavContainer,
        JumbotronContainer,
        IntroContents
    }

}
</script>

<style lang="scss">
</style>