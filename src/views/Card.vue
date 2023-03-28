<template>
    <div id="body">
        <navbar/>
        <cards/>
        <foot/>

    </div>
</template>

<script>

    import cards from "../components/cards.vue"
    import navbar from '../components/navbar.vue'
    import foot from '../components/foot.vue'

    export default {
        name: "Card",
        components:{
            cards, navbar, foot
        }
    }
</script>
<style scoped>

</style>