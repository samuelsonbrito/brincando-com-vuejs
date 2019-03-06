<template>
  <div id="app">
    
    <input type="text" :disabled="controlador">

    <button @click="ativador()">Ativador</button>
    
  </div>
</template>

<script>

export default{

  data(){
    return {
      controlador: true
    }
  },

  methods:{

    ativador(){
      this.controlador = !this.controlador
    }

  } 

}

</script>

<style>


</style>
