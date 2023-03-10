<template>
  <v-container class="container fill-height" fluid>
    <v-row 
      no-gutters
      justify="space-between"
      class="fill-height"
    >
      <!-- Column 1 -->
      <v-col
        cols="12"
        sm="6"
        class="image-background"
        style="background-color: blue;"
      >
        <!-- <img src="src\assets\img\interscreen\image_1.jpg" alt=""> -->
      </v-col>
      
      <!-- Column 2 -->
      <v-col
        cols="12"
        sm="6"
        align-self="center"
        style="background-color: red;"
      >
        <!-- Buttons -->
        <div class="buttons pa-12">
          <v-btn 
            block 
            color="primary"
            size="x-large"
            elevation="10"
          >
            Sou Cliente
          </v-btn>
          <br>
          <v-btn 
            block
            size="x-large"
            elevation="10"
          >
            Sou Funcionário
          </v-btn>
        </div>
      </v-col>
    </v-row>
  </v-container>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'Interscreen',

  data () {
    return {
        
    }
  },
})
</script>

<style scoped>
.container {
  background: rgb(107,11,198);
  background: linear-gradient(90deg, rgba(107,11,198,1) 66%, rgba(0,0,0,1) 100%);
}

.buttons {

}

.image-background {
  background: url(../assets/img/interscreen/image_1.jpg);
  background-repeat: no-repeat, repeat;
  background-size: 120% 100%;
  border: 5px solid #4b078a;
  
  transition: opacity 0.3s linear 2s;  
}
</style>