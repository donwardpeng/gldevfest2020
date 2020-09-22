<template>
  <v-container grid-list-md>
    <v-layout row wrap>
      <v-flex xs12 md12>
        <v-card>
          <img class="responsive" src="gdg-devfest-cool.png" style="padding: 10px; width: 100%;" />
        </v-card>
      </v-flex>
      <!-- <v-flex xs12 md4>
      <v-card>
        <v-card-text>
          <p class="display-1">Oct. 17, 2020</p>
          <p class="headline">Entirely Online and Streaming!</p>
        </v-card-text>
         <v-img
        height="100px"
        src="gdg.png"></v-img>
      <v-card-actions>-->
      <!-- <v-btn icon flat color="primary">
            <v-icon >share</v-icon>
      </v-btn>-->
      <!-- <v-btn color="primary" @click="openSubscriptionPopup">
            Subscribe to updates
      </v-btn>-->
      <!-- </v-card-actions>
      </v-card>
      </v-flex>-->
      <!-- <v-flex xs12 md7 pa-2>
      <div class="video-container">
        <iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/1p5C7RgL9vk" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      </div>
      </v-flex>-->
      <v-flex xs12 md8>
        <v-card>
          <v-card-title class="headline">What is the GDG Great Lakes DevFest?</v-card-title>
          <v-card-text
            class="subheading"
          >The Ann Arbor, Detroit and Windsor Google Developer Groups (GDGs) are excited to work together to host our the first GDG Great Lakes DevFest on Saturday, Oct 17, 2020. DevFests are Google sponsored software developer conferences that allow the local software development community to come together to network and learn about the coolest new technology out there.</v-card-text>
        </v-card>
      </v-flex>
      <v-flex xs12 md4>
        <v-card>
        <v-img height="200px" src="gdg.png"></v-img>
        </v-card>
      </v-flex>
      <v-flex xs12 md12>
        <v-card>
          <v-card-title class="headline">What can you expect at the GDG Great Lakes DevFest?</v-card-title>
          <v-card-text
            class="subheading"
          >A full day of great talks on some of the latest Google technology out there with great opportunities to network within the local tech community. This year is unique for us since the conference will be entirely online - streamed and recorded. <p><p>The best part - it is all free!</p></p></v-card-text>
        </v-card>
      </v-flex>
      <v-flex xs12 md12>
        <v-card>
          <v-card-title class="headline">What technologies will we be covering?</v-card-title>
          <v-card-text class="subheading">
            Some of the coolest development technologies out there including but not limited to Flutter, Android, TensorFlow, and Google Cloud Platform (GCP).
            <p><p><b>Interested in speaking? Click on the 'Apply to Speak' button in the header to apply to speak.</b></p></p>
          </v-card-text>
        </v-card>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<style scoped>
.v-card {
  height: 100%;
}
.video-container {
  position: relative;
  padding-bottom: 56.25%;
  padding-top: 30px;
  height: 0;
  overflow: hidden;
}

.video-container iframe,
.video-container object,
.video-container embed {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}
</style>

