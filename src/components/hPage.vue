<template>
  <div>
    <!-- <h1>Send Data Child to Parent</h1> -->
    <h2>{{childUser}}</h2>

    <userPage :getUser="getUserName"/> <!--we pass this data to child components-->
  </div>
</template>

<script>
import userPage from './userPage.vue'

export default {
name:'hPage',
data(){
 return{
  childUser:""
 }
},
components:{
  userPage
},
methods:{
  getUserName(name){
    // to take data from child to parent we take method function
  //  alert(name)
  this.childUser=name
  }
}
}

</script>

<style scoped>
h2{
  color:orange
}
</style>