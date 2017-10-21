<template>
  <div>
  <h2>contacto</h2>
  <li v-for="dia in lista">{{dia}}</li>
  </div>

</template>

<script>
export default {
  data(){
    return {
      lista: ["lunes", "martes", "miercoles"]
    }
  }
}
</script>

<style></style>
