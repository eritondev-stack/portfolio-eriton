<template>
  <div class="btn-eriton" @click="chamarEvento()">
    Botao clicar
  </div>
</template>

<script>
export default {

methods:{
  chamarEvento(){
    console.log("Cheguei aqui componente filho")
    this.$emit('myEvent')
  }
}
}
</script>

<style>
.btn-eriton{
  width: 100px;
  text-align: center;
  color: white;
  background-color: blue;
  cursor: pointer;
}


</style>