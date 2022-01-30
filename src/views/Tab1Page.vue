<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>FBMP</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">FBMP</ion-title>
        </ion-toolbar>
      </ion-header>

      <img src="../fb-stairs.png" alt="facebook pic"/>

      <!-- List of fbmp services -->
      <ion-list id="list">
        <ion-item>
          <ion-label>Post your inventory on FBMP</ion-label>
          <ion-icon name="checkmark-circle-outline">whats</ion-icon>
        </ion-item>
        <ion-item>
          <ion-label>Run Automotive Inventory Ads</ion-label>
        </ion-item>
        <ion-item>
          <ion-label>Answer Leads in Real Time</ion-label>
        </ion-item>
      </ion-list>

      <ion-button id="fb-button" fill="solid">Set up FBMP</ion-button>

      
      <!--<ExploreContainer name="Tab 1 page" />-->

    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent, IonIcon } from '@ionic/vue';
//import ExploreContainer from '@/components/ExploreContainer.vue';

export default  {
  components: { IonIcon, IonHeader, IonToolbar, IonTitle, IonContent, IonPage }
}
</script>

<style>

img {
  margin-top: 30px;
  height: 33%;
  margin-left: 30px;
}

#list {
  margin-top: 30px;
  margin-left: 20px;
  margin-right: 
}

#fb-button {
  align-items: center;
  margin-left: 33%;
  margin-top: 40px;
  color: white;
}

ion-icon {
  font-size: 64px;
}
</style>