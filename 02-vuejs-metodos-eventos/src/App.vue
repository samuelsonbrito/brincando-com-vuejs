<template>
  <div id="app">
    
    {{ valor }}

    <button v-on:click="contador()">+</button>
    <button @click="contador()">+</button>

  </div>
</template>

<script>

export default{

  data(){
    return {
      valor: 0
    }
  },

  methods:{

    contador(){
      this.valor++
    }
  } 

}

</script>

<style>


</style>
