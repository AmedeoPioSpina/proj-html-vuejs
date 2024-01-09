<template lang="">
    <header>
        <NavContainer />
        <JumbotronContainer />
    </header>
</template>
<script>
import NavContainer from './NavContainer.vue';
import JumbotronContainer from './JumbotronContainer.vue';
export default {
    name: "AppHeader",
    components:{
        NavContainer,
        JumbotronContainer
    }

}
</script>

<style lang="">
</style>