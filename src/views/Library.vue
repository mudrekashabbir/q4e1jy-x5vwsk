<template>
  <ion-page>
    <ion-content class="ion-padding">
      <ion-grid>
        <ion-row>
        <ion-col size="12" class="p-0">
        <ion-card class="p-0 m-0">
        <ion-card-content class="p-0">
        <ion-grid>
        <ion-row>
        <ion-col size="5" class="p-0">
        <ion-img
        src="https://docs-demo.ionic.io/assets/madison.jpg"
        alt="The Wisconsin State Capitol building in Madison, WI at night"
      ></ion-img></ion-col>
        <ion-col size="7" class="p-0">

        <ion-card-title class="text-left text-lg px-3 pb-1 "
        >Card TitleCard TitleCard TitleCar TitleCard Title</ion-card-title
      >
      <ion-card-subtitle class="text-left text-sm font-normal px-3 pb-1 "
        >Card TitleCard TitleCard TitleCar TitleCard Title</ion-card-subtitle
      >

      <ion-grid>
      <ion-row>
      <ion-col size="4" class="p-0 text-center"><ion-icon :icon="radio" color="#000" /></ion-col>
      <ion-col size="4" class="p-0 text-center">s</ion-col>
      <ion-col size="4" class="p-0 text-center">s</ion-col>
    </ion-row>
  </ion-grid>

        
        </ion-col>
        </ion-row>
        </ion-grid>
        
        
        </ion-card-content>
      
          
            
       
         
        </ion-card>
      </ion-col>

          <ion-col size="12">
            <ion-card>
              <ion-card-header>
                <ion-card-title>Card Title</ion-card-title>
                <ion-card-subtitle>Card Subtitle</ion-card-subtitle>
              </ion-card-header>

              <ion-card-content>
                Here's a small text description for the card content. Nothing
                more, nothing less.
              </ion-card-content>
            </ion-card>
          </ion-col>

          <ion-col size="12">
            <ion-card>
              <ion-card-header>
                <ion-card-title>Card Title</ion-card-title>
                <ion-card-subtitle>Card Subtitle</ion-card-subtitle>
              </ion-card-header>

              <ion-card-content>
                Here's a small text description for the card content. Nothing
                more, nothing less.
              </ion-card-content>
            </ion-card>
          </ion-col>

          <ion-col size="12">
            <ion-card>
              <ion-card-header>
                <ion-card-title>Card Title</ion-card-title>
                <ion-card-subtitle>Card Subtitle</ion-card-subtitle>
              </ion-card-header>

              <ion-card-content>
                Here's a small text description for the card content. Nothing
                more, nothing less.
              </ion-card-content>
            </ion-card>
          </ion-col>

          <ion-col size="12">
            <ion-card>
              <ion-card-header>
                <ion-card-title>Card Title</ion-card-title>
                <ion-card-subtitle>Card Subtitle</ion-card-subtitle>
              </ion-card-header>

              <ion-card-content>
                Here's a small text description for the card content. Nothing
                more, nothing less.
              </ion-card-content>
            </ion-card>
          </ion-col>

          <ion-col size="12">
            <ion-card>
              <ion-card-header>
                <ion-card-title>Card Title</ion-card-title>
                <ion-card-subtitle>Card Subtitle</ion-card-subtitle>
              </ion-card-header>

              <ion-card-content>
                Here's a small text description for the card content. Nothing
                more, nothing less.
              </ion-card-content>
            </ion-card>
          </ion-col>
        </ion-row>
      </ion-grid>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import {
  IonHeader,
  IonToolbar,
  IonTitle,
  IonContent,
  IonPage,
} from '@ionic/vue';

export default {
  components: { IonHeader, IonToolbar, IonTitle, IonContent, IonPage },
};
</script>
