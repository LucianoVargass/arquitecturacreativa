<template>
    
        <v-footer dark class="app">
            <v-container dark pa-1>
                <h3 class="text-center text-secundary font-weight-thin">Contactanos</h3>
          <v-row class="text-center ">
              <v-col class="">
                 <h4 class="font-weight-thin">Redes Sociales</h4>
                 <v-div>
                 <v-btn icon plain><v-icon>mdi-facebook</v-icon></v-btn>
                 <v-btn icon plain><v-icon>mdi-instagram</v-icon></v-btn>
                 <v-btn icon plain><v-icon>mdi-linkedin</v-icon></v-btn>
                 </v-div>
              </v-col>
              <v-col>
                  <h4 class="font-weight-thin">Contacto</h4>
                  <p><v-icon  class="ml-2 " small>mdi-email</v-icon> Email: arquitectura.creativa@gmail.com</p>
                   <p><v-icon  small>mdi-phone</v-icon>Tel: +54 299  6070801</p>
              </v-col>
              <v-col>
                  <h4 class="font-weight-thin">Encontranos</h4>
                 <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3019.773231600467!2d-65.09721698495581!3d-40.81097671915042!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x95fa33c246a090a5%3A0xa96c6ed131cde36a!2sLola%20Cafe%20-%20Bar!5e0!3m2!1ses-419!2sar!4v1617855892487!5m2!1ses-419!2sar" width="300" height="150" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
                  </v-col>
          </v-row>
          <p class="text-center ml-1 font-weight-thin"> {{ new Date().getFullYear() }} — <v-icon class="mr-1" plain>mdi-copyright</v-icon>Vrain Soluciones Informaticas</p>
          </v-container>
        </v-footer>

</template>
<script>


export default {
    name: 'Footer',
    components: {
    
    
  }
    
}
</script>