<template>
<div>
  <div class="connexion">
    <ion-item>
      <ion-label position="floating">Adresse e-mail</ion-label>
      <ion-input ></ion-input>
    </ion-item>
    <ion-item>
      <ion-label position="floating">Mot de Passe</ion-label>
      <ion-input></ion-input>
    </ion-item>
    <ion-button href="/tabs/tab1">Continuer sans se connecter</ion-button>
  </div>

</div>

</template>

<script lang="ts">
import { IonButton, IonInput, IonItem, IonLabel } from '@ionic/vue';
export default {
  name: 'Connexion',
  props: {
    name: String
  },
  components : {IonButton, IonInput, IonItem, IonLabel }
}
</script>

<style scoped>
.connexion{
  width: 80%;
  margin: 0 10%;
}

</style>
