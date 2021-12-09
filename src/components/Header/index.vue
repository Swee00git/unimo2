<template>
   <header id="header">
       <h1>{{ title }}</h1>
   </header>
</template>

<script>
export default {
    name:'Header',
    props:{
        title:{
            type : String,
            default:'Unimo Store'
        }
    }
}
</script>

<style scoped>
    #header{width:100%; height:50px; color: #fff; background: #ebf8fa; border-bottom: 1px solid #5a5656; position: relative;}
    #header h1{ font-size: 1.5em; color: #1a1919; text-align: center; line-height: 50px; font-weight: normal; }
    #header i{ position: absolute; left: 5px; top: 50%; margin-top: -13px; font-size: 26px;}
</style>