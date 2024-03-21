<template>
  <ion-page>
    <ion-menu content-id="main-content">
      <ion-header>
        <ion-toolbar>
          <ion-title>Hello header</ion-title>
        </ion-toolbar>
      </ion-header>
    </ion-menu>
    <ion-content class="ion-padding">
      <h1>Hello Content</h1>
    </ion-content>
    <ion-footer>
      <ion-title>Hello footer</ion-title>
    </ion-footer>
  </ion-page>
</template>

<script setup lang="ts">
import { IonContent, IonHeader, IonPage, IonTitle, IonToolbar, IonFooter } from '@ionic/vue';
</script>

<style scoped></style>
