<template>
  <v-content class="homees text-center">
    <h1 class="primary--text">Arquitectura Creativa</h1>

    <h2 class="text primary--text">Nuestro trabajo nos</h2>
    
    <v-div class="text animated primary--text">
      <v-div class="flip">motiva</v-div>

      <v-div class="flip">inspira</v-div>

      <v-div class="flip">apasiona.</v-div>
    </v-div>
    
  </v-content>
</template>
<script>

export default {
  name: "Home"
};
</script>
<style scoped>
.homees {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 70vh;
  background-color: black;
}
.text {
  color: white;
  font-size: 30px;
  line-height: 50px;
  display: inline-block;
  text-align: left;
}
.animated{
    height: 35px;
    overflow: hidden;
    margin-left: 5px;
}


</style>