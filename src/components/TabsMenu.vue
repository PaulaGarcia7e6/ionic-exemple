<template>
    <ion-page>
        <ion-tabs>
            <ion-router-outlet></ion-router-outlet>
            <ion-tab-bar slot="bottom">
                <ion-tab-button tab="home" href="/home">
                
                </ion-tab-button>
                <ion-tab-button tab="library" href="/library">
                
                </ion-tab-button>
                <ion-tab-button tab="search" href="/search">
                    
                </ion-tab-button>
                <ion-tab-button tab="radio" href="/radio">
                    
                </ion-tab-button>
            </ion-tab-bar>
        </ion-tabs>
    </ion-page>
</template>

<script setup lang="ts">
import {IonPage,IonRouterOutlet, IonTabBar, IonTabs, IonTabButton} from '@ionic/vue'
</script>

<style scoped>

</style>