<template>
  <h1>CheckBox And Radio Buttons </h1>
  <h3>Anime character</h3>
  <label for="naruto">Naruto</label><!-- it is for name   -->
  <input type="checkbox" value="naruto" v-model="anime" id="naruto"/>
  <label for="kakshi">Kakshi</label><!-- it is for name   -->
  <input type="checkbox" value="kakshi" v-model="anime" id="kakshi"/>
  <label for="sasuke">Sasuke</label><!-- it is for name   -->
  <input type="checkbox" value="sasuke" v-model="anime" id="sasuke"/>
  <br/> <br/>
  <h3>Who is Favourite Anime Character</h3>
  <label for="naruto">Naruto</label><!-- it is for name   -->
  <input type="radio" value="Naruto" v-model="who" name="who" id="naruto"/>
  <label for="kakshi">Kakshi</label><!-- it is for name   -->
  <input type="radio" value="Kakshi" v-model="who" name="who" id="kakshi"/>
   <label for="sasuke">Sasuke</label><!-- it is for name   -->
<input type="radio" value="Sasuke" v-model="who" name="who" id="sasuke"/>
<br/> <br/>
  <h4>Selected Anime Character: {{anime}}</h4>
  <h4>Who is Favourite Anime Character: {{who}}</h4>

</template>

<script>
export default {
name:'checkBox',
data(){
    return{
        anime:[],
        who:null
    }
}
}
</script>

<style scoped>
h1{
    color: darkorange;
}
</style>