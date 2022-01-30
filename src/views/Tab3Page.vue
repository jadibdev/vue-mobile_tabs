<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>CRM</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">CRM</ion-title>
        </ion-toolbar>
      </ion-header>
      
     <img src="../tablet.png" alt="facebook pic"/>

      <!-- List of fbmp services -->
      <ion-list id="list">
        <ion-item>
          <ion-label>Sales Process Organized</ion-label>
          <ion-icon name="checkmark-circle-outline">whats</ion-icon>
        </ion-item>
        <ion-item>
          <ion-label>Schedules and Tasks reminders</ion-label>
        </ion-item>
        <ion-item>
          <ion-label>Better Decisions with Analytics.</ion-label>
        </ion-item>
      </ion-list>

      <ion-button id="fb-button" fill="solid">Set up CRM</ion-button>

      <!-- <ExploreContainer name="Tab 3 page" /> -->
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';
//import ExploreContainer from '@/components/ExploreContainer.vue';

export default  {
  components: { IonHeader, IonToolbar, IonTitle, IonContent, IonPage }
}
</script>

<style>

img {
  margin-top: 0px;
  height: 35%;
  margin-left: 15%;
}

#list {
  margin-top: 30px;
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