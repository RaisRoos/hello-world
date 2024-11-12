<template>
  <ion-page class="container">
    
    <MainHeader />

    <ion-content :fullscreen="true">
      <h1 align="center">Hello World!</h1>
    </ion-content>
  </ion-page>
</template>

<script setup>
import { IonContent,IonPage } from '@ionic/vue';
import MainHeader from '@/components/MainHeader.vue';
</script>

<style scoped>
</style>
