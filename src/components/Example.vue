<template>
  <ion-page>
    <div class="ion-page" id="main-content"></div>
    <ion-tabs>
      <ion-router-outlet></ion-router-outlet>

      <ion-header>
        <ion-toolbar>
          <ion-buttons slot="start">
            <ion-menu-button></ion-menu-button>
          </ion-buttons>
          <ion-title>Menu</ion-title>
          <ion-buttons slot="end">
            <ion-icon :icon="settingsOutline" color="primary"></ion-icon>
          </ion-buttons>
        </ion-toolbar>
      </ion-header>

      <ion-menu contentId="main-content">
        <ion-header>
          <ion-toolbar>
            <ion-title>Menu Content</ion-title>
          </ion-toolbar>
        </ion-header>
        <ion-content class="ion-padding"
          ><ion-list>
            <ion-item>
              <ion-label>Pokémon Yellow</ion-label>
            </ion-item>
            <ion-item>
              <ion-label>Mega Man X</ion-label>
            </ion-item>
            <ion-item>
              <ion-label>The Legend of Zelda</ion-label>
            </ion-item>
            <ion-item>
              <ion-label>Pac-Man</ion-label>
            </ion-item>
            <ion-item>
              <ion-label>Super Mario World</ion-label>
            </ion-item>
          </ion-list></ion-content
        >
      </ion-menu>

      <ion-tab-bar slot="bottom">
        <ion-tab-button tab="home" class="bg-black" href="/home">
          <ion-icon :icon="playCircle" />
          <ion-label>Listen now</ion-label>
        </ion-tab-button>

        <ion-tab-button
          tab="radio"
          class="bg-black"
          href="https://www.example.com"
          target="_blank"
        >
          <ion-icon :icon="radio" />
          <ion-label>Radio</ion-label>
        </ion-tab-button>

        <ion-tab-button tab="library" class="bg-black" href="/library">
          <ion-icon :icon="library" />
          <ion-label>Listen now</ion-label>
        </ion-tab-button>
      </ion-tab-bar>
    </ion-tabs>
  </ion-page>
</template>

<script lang="ts">
import {
  IonPage,
  IonTabs,
  IonRouterOutlet,
  IonTabBar,
  IonTabButton,
  IonLabel,
  IonIcon,
} from '@ionic/vue';

import { settingsOutline } from 'ionicons/icons';

import { playCircle, radio, library, search } from 'ionicons/icons';

export default {
  components: {
    IonPage,
    IonTabs,
    IonRouterOutlet,
    IonTabBar,
    IonTabButton,
    IonLabel,
    IonIcon,
  },
  data() {
    return {
      playCircle,
      radio,
      library,
      settingsOutline,
      search,
    };
  },
};
</script>
