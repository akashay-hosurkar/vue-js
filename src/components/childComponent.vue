<template>
<h3>home</h3>
<h1>{{name}}</h1>
<h1>{{user.name}}</h1>
<button v-on:click="getData()">function</button>
</template>

<script>
export default{
    name:'childComponent',
    props:{
        name:String,
        user:Object,
        getData:Function
    }
}
</script>

<style scoped>
h2{
    color:orange
}
</style>