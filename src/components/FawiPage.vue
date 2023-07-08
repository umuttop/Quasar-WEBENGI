<template>
  <div class="FawiPage">
    <h1>Willkommen bei der Fawi!</h1>
    <p>
     Fawi steh für Finanzielle Anreicherung und Wohlstand im Internet.
    </p>
    <h3>Navigation hua hua</h3>
    <ul>
      <li><a href="#">Anmeldung/Login</a></li> <!--Hier muss noch ein Link rein-->
      <li><a href="#">Ersti Fahrt(Absturz)!</a></li> <!--Hier muss noch ein Link rein-->
      <li><a href="#">News News News!!!</a></li> <!--Hier muss noch ein Link rein-->
      <li><a href="#">Kalender(Ersti Fahrt/aktueller Stundenplan)</a></li> <!-- Hier muss noch ein Link rein-->
      <li><a href="#">Bildergalerie(fawigram)</a></li> <!--Hier muss noch ein Link rein-->
      <li><a href="#">Send Bitcoin get altklausuren</a></li> <!-- Hier muss noch ein Link rein-->
    </ul>
  </div>
</template>

<script>
//import { firebase } from '@firebaseConfig';
//import { db } from '@/firebase';

export default {
  name: 'FawiPage',
  props: {
    msg: String
  }
}
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
