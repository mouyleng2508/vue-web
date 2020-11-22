<template>
  <nav>
    <v-layout justify-center>
      <v-img
        src="../assets/home.gif"
        alt=""
        class="py-5"
        contain
        height="280px"
        width="350px"
      >
      </v-img>
    </v-layout>

    
      <!-- <v-toolbar flat align="center"> -->
        <!-- <v-card flat centered >
          <v-tab centered >
            <v-tab to="/">HOME</v-tab> | 
            <v-tab to="/about">ABOUT</v-tab> |
            <v-tab to="/art_works">ART WORKS</v-tab> |
            <v-tab to="/experiences">EXPERIENCES</v-tab>
          </v-tab>
        </v-card> -->


        <v-card align="center" flat justify="space-around">
            <!-- on click on btn "to = "/" -->
            <v-btn text to="/">HOME</v-btn> | 
            <v-btn text to="/about">ABOUT</v-btn> |
            <v-btn text to="/art_works">ART WORKS</v-btn> |
            <v-btn text to="/experiences">EXPERIENCES</v-btn>
        </v-card>
      <!-- </v-toolbar> -->

  </nav>
</template>

<script>
export default {};
</script>