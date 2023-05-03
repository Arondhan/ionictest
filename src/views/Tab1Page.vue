<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Tab 1</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
        </ion-toolbar>
      </ion-header>

      <img src="https://sun6-22.userapi.com/s/v1/ig2/QgQyJjOHyuA9j-rGIILVHlINP4ESODIUqq0n8W21Gk0V2YlZmoywlF4i0hVPORrd8vtO4JG6ZTXfOzR2VuPStFQg.jpg?size=662x662&quality=95&crop=83,18,662,662&ava=1" style="display:block; background-color:transparent; margin:0 auto; max-width:40%; margin-top:1vh; width:20%" />
      <ion-grid>
  <ion-row>
    <ion-col size="12" size-md="6" offset-md="3" class="text-center ion-text-center">
      <ion-list style="margin-top: 50%;">
        <ion-item>
          <ion-label position="floating">Имя пользователя</ion-label>
          <ion-input type="text" size="3" style="font-size:16px;"></ion-input>
        </ion-item>
        <ion-item>
          <ion-label position="floating">Пароль</ion-label>
          <ion-input type="password" size="3" style="font-size:16px;"></ion-input>
        </ion-item>
      </ion-list>
      <ion-button expand="block" color="primary" @click="login">Войти</ion-button>
    </ion-col>
  </ion-row>
</ion-grid>
    </ion-content>
  </ion-page>
</template>

<script setup lang="ts">
const login = () => {
  // здесь можно добавить код для проверки учетных данных и выполнения входа
  console.log('Выполняем вход');
}
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';
import ExploreContainer from '@/components/ExploreContainer.vue';
</script>
