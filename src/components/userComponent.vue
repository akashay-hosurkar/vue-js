<template>
<div class="user">
  <h1>User Component</h1>
  <h2>{{data.name}}</h2>
  <h2>{{data.email}}</h2>
  <button v-on:click=" getData(data.name)" >Alert Name</button> 
 </div>
  </template>

<script>
export default {
name:'userComponent',
props:{
  data:Object,
  getData:Function
},

}
</script>

<style scoped>
h1{
  color:red;
}
.user{
  background-color: skyblue;
  padding: 10px;
  border-bottom: 4px solid red;
  border-top: 4px solid red ;
  border-left: 3px solid red;
  border-right: 3px solid red;
 margin-bottom: 20px;
}
</style>