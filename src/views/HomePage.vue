<template>
<ion-page>
  <ion-menu content-id="main-content">
    <ion-header>
      <ion-toolbar>
        <ion-title>Menu Content</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content class="ion-padding">This is the menu content.</ion-content>
  </ion-menu>
  <ion-content class="ion-padding">
    <h1>HOME</h1>
  </ion-content>
</ion-page>
</template>

<script setup lang="ts">
import { IonMenu, IonContent, IonHeader, IonPage, IonTitle, IonToolbar } from '@ionic/vue';
</script>

<style scoped>

</style>
