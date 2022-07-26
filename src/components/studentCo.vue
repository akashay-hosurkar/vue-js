<template>
  <h2>Students Name is : {{name}}</h2>
</template>

<script>
export default {
name:'studentCo',
props:{
    name:String
}
}
</script>

<style scoped>
h2{
    color:black
}
</style>