<template>
<div>
    <!-- <h1>Hi Iam Home Component {{"Akshay".length}}</h1>
  <h1>Hi Iam Home Component 10+10</h1> -->
    <!-- <h1>Hi Iam Home Component</h1>
<h1 v-on:mousemove="getMouse()">Hi Iam Home Component</h1>
<button v-on:click="getData()">Click me</button>
<h3>{{count}}</h3> -->
    <!-- <button v-on:click="test()">Click me</button> -->
    <!-- <button v-on:click="getData('Button 1 Clicked')">Click me</button>
<button v-on:click="getData('Button doubled Clicked')">Click me</button>
<button v-on:dblclick="getData('Button doubled Clicked')">Click me</button> -->

    <!-- <h1>Email {{email}}</h1> -->
    <!-- <h1>Mobile {{mobile}}</h1> 
 <h1>Mobile {{mobile==8888}}</h1> 
  <h1>Name {{getName("Naruto")}}</h1>   -->
    <!-- <h1>Name1: {{getName("Kakshi")}}</h1>
<h1>Name2: {{getName("Sasuke")}}</h1>
<h1>All DATA: {{getData().name}}</h1> -->
    <!-- <h1>All DATA: {{getData().email}}</h1>  it acces only email property by using .email from getData() function -->
    <!-- <h2>Child Compoents</h2> -->
    <!-- <h1>HTML Binding</h1> -->
       <!-- <h2>{{text}}</h2> -->
 <!-- <div v-html="tag"></div> -->
 <!-- <div v-html="tag2"></div> -->

    <!-- <ul>
        <li v-for="item in users" :key="item.name">  <userComponent :data="item" :getData="getData"/> </li>
    </ul> -->
    <!-- <childComponent  name="akshay" :user="user" :getData="getData"/> -->
    
</div>
</template>

<script>
// import childComponent from './childComponent.vue'
// import userComponent from './userComponent.vue'


export default {
    name: "homePage",
    components: {
        // userComponent
        // childComponent
    },
    //this data is for html binding
    // data(){
    //     return {
    //         text:"Zayn Malik", //during html text binding problem not occur it occur when during html tag 
    //          tag:"<h1>Zayn Malik</h1>",
    //          tag2:"<h1>ankita@talented.com </h1>"

    //     }
    // }
//     methods:{
//   getData(name){
//     alert(name)
//   }
// },
//     data() {
//         return {
//             users: [{
//                     name: "Naruto",
//                     email: 'Naruto@naruto.com'
//                 },
//                 {
//                     name: "Sasuke",
//                     email: 'Sasuke@Sharingan.com'
//                 },
//                 {
//                     name: "Hinata",
//                     email: 'Hinata@Naruto.com'
//                 },
//                 {
//                     name: "Kakshi",
//                     email: 'kakshii@Whitefang.com'
//                 },
//                 {
//                     name: "Tom",
//                     email: 'Tom@Jerry.com'
//                 }
//             ]
//         }
//     },
//     // methods:{
    //     getData(){
    //         console.log("parent function called")
    //     }
}
// }
// data(){
// return{
// count:0
// }
// },
// methods: {
// test()
// {
//     alert("function call ala re")
// }
// getData(data) {
//     // alert(data)

// },
// getData() {
// this.count=10;//it will print 10
//  this.count=this.count+1;

// },
// getMouse() {
//   console.warn("Function call ala re vaps");
// }
// }
// 
// mobile:234567890,data() {
//     return {
//         email: 'akshay@joke.com',
// getName:function(a){
//     return a;
// }
//     }
// },
// methods: {
// getName(){
//     return "Akshay"
// }
// getName(name) {
//     return name;
// },
// getData() {
//     return {
//         name: "Naruto",
// email: 'naruto@uzumaki.com'
// email:this.email //it will take the email:'akshay@joke.com' from data function  we can access this property from method so we have to use(this keyw) by this.email              
// }
// }
// }
// }
</script>

<style scoped>
</style>
