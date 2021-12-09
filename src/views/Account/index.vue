<template>
     <div id="main">
        <Header title="List" />
        <router-view />
        <TabBar />
    </div>
</template>

<script>
import Header from '@/components/Header'
import TabBar from '@/components/TabBar'

export default {
    name:'Account',
    components:{
        Header,
        TabBar
    }
}
</script>

<style scoped>

</style>