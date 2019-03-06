<template>
  <div id="app">

    {{ nome }} {{ idade }}
    <div v-text="nome"></div>

    <input type="text" v-model="nome" placeholder="Nome">
    <input type="text" v-model="idade" placeholder="Idade">
    
  </div>
</template>

<script>

export default{
  data(){
    return {
      nome: '',
      idade: '',
    }
  }
}

</script>

<style>

  input{
    background-color: rgb(238, 175, 247);
    text-align: center;
    border-radius: 10px;
  }

</style>
