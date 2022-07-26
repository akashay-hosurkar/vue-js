<template>
  <h2>Teacher Name is :{{name}}</h2>
</template>

<script>
export default {
name:'teacherCo',
props:{
    name:String
}
}
</script>

<style scoped>
h2{
    color:red
}
</style>