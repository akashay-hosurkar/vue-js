<template>
<h1 v-if="show">IF Condtion</h1>
<!-- <h1 v-else> Else Condtion</h1> -->
 <h1 v-else> Else Condtion</h1> <!--this condtion is control by toggle button -->

<!-- <button v-on:click="show=false" >HIDE </button> -->
<br/>
 <button v-on:click="show=!show" >TOGGLE</button>  <!--this for toggle  --> <!-- the toggle is for both hide and show -->

</template>

<script>
export default {
    name: 'vueIF',
    data() { // taking data property
        return {
             show:true //it will show the if else condtion statement which is in <h1>
            // show:false
        }
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

<style scoped>
h1 {
    color: darkgreen;
}
</style>
