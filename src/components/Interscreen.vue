<template>
  <v-container class="image2 fill-height" fluid>
    <v-row
      justify="center"
      no-gutters
    >
      <v-col cols="6"></v-col>

      <v-col
        cols="4"
        align-self="center"
      >
        <div class="d-flex flex-column justify-space-between">
          <!-- Buttons -->
          <div>
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

          <!-- Card -->
          <v-card 
            title="Siga nossas redes sociais:" 
            text="@fastAcai" 
            variant="tonal"
            class="mt-16 mb-2" 
            color="white"
          ></v-card>
          <v-card 
            title="Contatos:" 
            text="fastAcai@outlook.com" 
            variant="tonal"
            color="white"
          ></v-card>
        </div>
      </v-col>
    </v-row>
  

    <!-- Option 1 -->
    <!-- <v-col 
      cols="12"
    >
      <v-sheet class="button pa-2 ma-2">
        <v-btn 
          block 
          color="primary"
          size="x-large"
        >
          Sou Cliente
        </v-btn>
        <br>
        <v-btn 
          block
          size="x-large"
        >
          Sou Funcionário
        </v-btn>
      </v-sheet>
    </v-col> -->

    <!-- Option 2 -->
    <!-- <v-col 
      cols="12"
      md="6"
    >
      <v-sheet class="button pa-2 ma-2">
        <v-btn 
          block 
          color="primary"
          size="x-large"
        >
          Sou Cliente
        </v-btn>
      </v-sheet>
    </v-col>
    <v-col 
      cols="12"
      md="6"
    >
      <v-sheet class="button pa-2 ma-2">
        <v-btn 
          block
          size="x-large"
        >
          Sou Funcionário
        </v-btn>
      </v-sheet>
    </v-col> -->
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
.image1 {
  background-image: 
    url(../assets/img/interscreen/image_1.jpg),
    url(../assets/img/interscreen/image_2.jpg);
  background-position:
    right, /* this positions the first image */
    left; /* this positions the second image */
  background-repeat:
    no-repeat; /* this applies to both images */
  background-size: 
    50% /* width */
    100%; /* height */
}

.image2 {
  background-image: 
  linear-gradient(90deg, rgba(2,0,36,1) 0%, rgba(101,25,173,1) 0%, rgba(0,0,0,1) 100%, rgba(0,212,255,1) 100%),
    url(../assets/img/interscreen/image_1.jpg);
  background-position:
    right, /* this positions the first image */
    left; /* this positions the second image */
  background-repeat:
    no-repeat; /* this applies to both images */
  background-size: 
    50% /* width */
    100%; /* height */
}
</style>

