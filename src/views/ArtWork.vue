<template>
  <!-- <v-row>
    <v-col cols="12" md="4">
      <v-img height="300px" src="https://picsum.photos/seed/1/200/100"></v-img>
    </v-col>
    <v-col cols="12" md="4">
      <v-img height="300px" src="https://picsum.photos/seed/1/200/100"></v-img>
    </v-col>
    <v-col cols="12" md="4">
      <v-img height="300px" src="https://picsum.photos/seed/1/200/100"></v-img>
    </v-col>
  </v-row> -->

    <!-- <v-container class="grey lighten-5">
    <v-row
      class="mb-6"
      
    >
      <v-col
        v-for="n in 4"
        :key="n"
      >
        <v-card
          class="pa-5"
          tile
          outlined>
          <v-img height="150px" width="150px" src="../assets/Logo/HonLogo.png"></v-img>
          
        </v-card>
        <v-card
          class="pa-5"
          tile
          outlined>
          <v-img height="150px" width="150px" src="../assets/Logo/HonLogo.png"></v-img>
          
        </v-card>
      </v-col>
    </v-row>

    
  </v-container> -->


  <v-container>
    <v-row id="TextLogo" align="center" justify="center" >
      <p class="grey--text lighten-2 display-1 mt-4">Logo</p>
    </v-row>
    <v-row id="Logo">
      <v-col
        v-for="image in logo"
        :key="image"
      >
        <!-- <v-card
          class="pa-5"
          tile
          outlined
          
        > -->
          <v-img width="200px" height="200px"  :src="image"></v-img>
        <!-- </v-card> -->
      </v-col>
    </v-row>
    <v-row id="TextComics" align="center" justify="center" >
      <p class="grey--text lighten-2 display-1 mt-4">Comics</p>
    </v-row>
    <v-row id="Comics">
      <v-col
        v-for="image in comics"
        :key="image"
        class="float-left"
      >
        <!-- <v-card
          class="pa-5 mx-auto"
          tile
          outlined
          
        > -->
          <v-img :src="image"></v-img>
        <!-- </v-card> -->
      </v-col>
    </v-row>
    <v-row id="TextIllustrations" align="center" justify="center" >
      <p class="grey--text lighten-2 display-1 mt-4">Illustrations</p>
    </v-row>
    <v-row id="Illustrations">
      <v-col
        v-for="image in illustrations"
        :key="image"
        cols="4"
      >
        <!-- <v-card
          class="pa-5"
          tile
          outlined
          
        > -->
          <v-img   :src="image"></v-img>
        <!-- </v-card> -->
      </v-col>
    </v-row>
    <v-row id="TextQuotes" align="center" justify="center" >
      <p class="grey--text lighten-2 display-1 mt-4">Quotes</p>
    </v-row>
    <v-row id="Quotes">
      <v-col
        v-for="image in quotes"
        :key="image"
      >
        <!-- <v-card
          class="pa-5"
          tile
          outlined
          
        > -->
          <v-img width="200px" height="200px" :src="image"></v-img>
        <!-- </v-card> -->
      </v-col>
    </v-row>
    <v-row id="TextDD" align="center" justify="center" >
      <p class="grey--text lighten-2 display-1 mt-4">Digital Drawings</p>
    </v-row>
    <v-row id="DigitalDrawings">
      <v-col
        v-for="image in digital_drwaings"
        :key="image"
        
      >
        <!-- <v-card
          class="pa-5"
          tile
          outlined
          
        > -->
          <v-img  width="200px" height="200px" :src="image"></v-img>
        <!-- </v-card> -->
      </v-col>
    </v-row>
  </v-container>
</template>
<script>

export default {
  name: 'App',
  components: {  },
  data: () => ({
    logo: [
    
      require('../assets/Logo/AVLogo.png'),
      require('../assets/Logo/DaisyCover.png'),
      require('../assets/Logo/HonLogo.png'),
      require('../assets/Logo/CambodianCheeringPartylogo-01.png'),
      require('../assets/Logo/CambodianCheeringPartylogo-02.png'),
      require('../assets/Logo/CambodianCheeringPartyWithMask-01.png'),
      require('../assets/Logo/CambodianCheeringPartyWithoutMask-01.png'),
      require('../assets/Logo/InfiniteCompany.png'),
      require('../assets/Logo/Promofy.png')

    ],
    comics: [
    
      require('../assets/Comics/all-01.png'),
      require('../assets/Comics/Unhappy-01.png'),
      require('../assets/Comics/Unhappy-02.png')

    ],
    illustrations: [
    
      require('../assets/Illustrations/SchoolTrip.png'),
      require('../assets/Illustrations/Covid19.png'),
      require('../assets/Illustrations/Boutique.png'),
      require('../assets/Illustrations/momo.png'),
      require('../assets/Illustrations/CartoonMe.png'),
      require('../assets/Illustrations/ShootPhoto.png')

    ],
    quotes: [
    
      require('../assets/Quotes/cactus.png'),
      require('../assets/Quotes/EnjoyLittlethings.png'),
      require('../assets/Quotes/Mask.png'),
      require('../assets/Quotes/Rainbow.png'),
      require('../assets/Quotes/Stress.png')

    ],
    digital_drwaings: [
    
      require('../assets/DigitalDrawings/OctoberCalendar.png'),
      require('../assets/DigitalDrawings/peaceout.png'),
      require('../assets/DigitalDrawings/selfloved.png')

    ]
  }),
  
};
</script>