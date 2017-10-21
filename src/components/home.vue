<template>
  <div>
  <h2>cambiar</h2>
    <input type="text" placeholder="Introducir texto" v-model="nuevoTexto">
    {{textoadesplegar}}
    <input type="button" value="Enviar texto" v-on:click="agregarTexto">
  </div>
</template>

<script>
export default {
  data(){
    return {
      nuevoTexto:'',
      textoadesplegar:''
    }
  },
  methods:{
    agregarTexto(){
      this.textoadesplegar = this.nuevoTexto;
    }
  }

}
</script>

<style></style>
