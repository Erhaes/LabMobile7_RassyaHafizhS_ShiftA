<template>
  <ion-page>
    <ion-header :translucent="true">
      <ion-toolbar>
        <ion-buttons slot="start">
          <ion-menu-button color="primary"></ion-menu-button>
        </ion-buttons>
        <ion-title>To Do List</ion-title>
      </ion-toolbar>
    </ion-header>

    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">To Do List</ion-title>
        </ion-toolbar>
      </ion-header>

      <div id="container">
        <ion-searchbar show-clear-button="focus"></ion-searchbar>
        <ion-card>
          <ion-card-header>
            <ion-card-title>Jogging</ion-card-title>
            <ion-card-subtitle>06.00 - 06.15</ion-card-subtitle>
          </ion-card-header>

          <ion-card-content>
            Jogging 15 menit sepanjang kompleks.
          </ion-card-content>
        </ion-card>
        <ion-card>
          <ion-card-header>
            <ion-card-title>Sarapan</ion-card-title>
            <ion-card-subtitle>06.20 - 06.45</ion-card-subtitle>
          </ion-card-header>

          <ion-card-content>
            sarapan pagi supaya tidak kelaparan.
          </ion-card-content>
        </ion-card>
        <ion-card>
          <ion-card-header>
            <ion-card-title>Mandi & Ganti Baju</ion-card-title>
            <ion-card-subtitle>06.45 - 07.00</ion-card-subtitle>
          </ion-card-header>

          <ion-card-content>
            Mandi dan berpakaian rapi
          </ion-card-content>
        </ion-card>
        <ion-card>
          <ion-card-header>
            <ion-card-title>Berangkat Kuliah</ion-card-title>
            <ion-card-subtitle>07.00 - 07.30</ion-card-subtitle>
          </ion-card-header>

          <ion-card-content>
            Berangkat kuliah dari rumah.
          </ion-card-content>
        </ion-card>
      </div>
    </ion-content>
  </ion-page>
</template>

<script setup lang="ts">
import { IonButtons, IonContent, IonHeader, IonMenuButton, IonPage, IonTitle, IonToolbar, IonSearchbar,
  IonCard, IonCardContent, IonCardHeader, IonCardSubtitle, IonCardTitle
 } from '@ionic/vue';
</script>

<style scoped>
#container strong {
  font-size: 20px;
  line-height: 26px;
}

#container p {
  font-size: 16px;
  line-height: 22px;
  color: #8c8c8c;
  margin: 0;
}

#container a {
  text-decoration: none;
}

ion-content {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100%;
  padding: 16px;
  box-sizing: border-box;
}

#container {
  width: 100%;
  max-width: 600px; 
  margin: auto;
}

ion-card{
  border-radius: 10px;
}

ion-card-title,
ion-card-subtitle,
ion-card-content {
  text-align: left; 
}

ion-searchbar {
  margin-bottom: 16px;
  border-radius: 10px;
}
</style>
