<template>
<!-- <h1>Hi Iam Home Component {{"Akshay".length}}</h1>
  <h1>Hi Iam Home Component 10+10</h1> -->

<h1>Email {{email}}</h1>
<!-- <h1>Mobile {{mobile}}</h1> 
 <h1>Mobile {{mobile==8888}}</h1> 
  <h1>Name {{getName("Naruto")}}</h1>   -->
<h1>Name1: {{getName("Kakshi")}}</h1>
<h1>Name2: {{getName("Sasuke")}}</h1>
<h1>All DATA: {{getData().name}}</h1>
<!-- <h1>All DATA: {{getData().email}}</h1>  it acces only email property by using .email from getData() function -->

</template>

<script>
export default {
    name: 'homeComponent',
    data() {
        return {
            email: 'akshay@joke.com',
            // mobile:234567890,
            // getName:function(a){
            //     return a;
            // }
        }
    },
    methods: {
        // getName(){
        //     return "Akshay"
        // }
        getName(name) {
            return name;
        },
        getData() {
            return {
                name: "Naruto",
                // email: 'naruto@uzumaki.com'
                email:this.email //it will take the email:'akshay@joke.com' from data function  we can access this property from method so we have to use(this keyword) by this.email              
                }
        }
    }
}
</script>

<style scoped>
h1 {
    color: orangered;
}
</style>
