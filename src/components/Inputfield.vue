<template>
  <h1>Get Input Field value</h1>
  <input type="text" placeholder="Enter Email" v-model="email"/>
  <br/>
  <br/>
  <input type="text" placeholder="Enter Password" v-model="password"/>
  <br/><br/>
  <button v-on:click="getData()" type="button">Get Values</button>
</template>

<script>
export default {
name:'inputField',
data(){
return{
    email:null,
    password:null,
}
},
methods:{
    getData(){
        console.warn("values:",this.email,this.password)
    }
}
}
</script>

<style scoped>
h1{
    color:darkgreen
}
</style>