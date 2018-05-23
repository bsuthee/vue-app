<template>
  <div>
   <h1> About {{name.toUpperCase()}} {{surname}} </h1>
   <h2> age {{age * 2}} </h2>
   <input type="text" :value="name" > <br>
   <input type="text" v-model="name"> <br>
   <input type="text" v-model="name">
   </div>
</template>
<script>
export default {
  data(){
    return{
      name: 'Suthee',
      age: 25,
      surname: 'Banprasert'
    }
  }
}
</script>

