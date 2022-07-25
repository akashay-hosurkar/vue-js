<template>
  <div>

    <img alt="Vue logo" src="./assets/logo.png">
    <!-- <HelloWorld msg="Welcome to Vue.js"/>

   -->
    <!-- <HelloWorld msg="Events and Binding in vue.js"/> -->
    <!-- <HelloWorld msg="Input field in vue.js"/> -->

    <!-- <HelloWorld msg="Pass Data to Child Component in vue.js" /> -->
    <!-- <HelloWorld1 msg="CheckBox and Radio Button in vue.js" /> -->
    <!-- <Home1/> -->
    <!-- <inputField/> -->
    <!-- <checkBox/> -->
    <!-- <vueIF/> -->
  <!-- <vFor/> -->
  
<home/>
<classBinding/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
// import vueIF from './components/vueIF.vue'
// import home from './components/Home.vue'
// import Home1 from './components/Home1.vue'
// import inputField from './components/Inputfield.vue'
// import checkBox from './components/CheckBox.vue'
// import vueIF from './components/vueIF.vue'
// import vFor from './components/vFor.vue'
import classBinding from './components/classBinding.vue'










export default {
  name: 'App',
  components: {
    // HelloWorld,
    classBinding
    // vueIF,
    // home,
    //  Home1,
    // inputField,
    // checkBox,
    // vFor
    
}
}
</script>

<!--  <style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

 -->
