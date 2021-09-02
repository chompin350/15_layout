<template>
  <div class="container">
    <div v-for="(personaje,index) in personajes" :key="index">
      <b-card
        style="min-width: 20rem"
        class="col-12 mb-3"
      >
        <img :src="personaje.imagen" alt="{{personaje.nombre">
        <b-card-text>
          {{ personaje.nombre }}
        </b-card-text>
      </b-card>
    </div>
  </div>
</template>

<script>
export default {
   data(){
    return {
      personajes: [
        {'id': 1,'nombre': 'Morty', 'imagen':'https://rickandmortyapi.com/api/character/avatar/2.jpeg'},
        {'id': 2,'nombre': 'Rick', 'imagen':'https://rickandmortyapi.com/api/character/avatar/1.jpeg'},
        {'id': 3,'nombre': 'Summer', 'imagen':'https://rickandmortyapi.com/api/character/avatar/3.jpeg'},
        {'id': 4,'nombre': 'Beth', 'imagen':'https://rickandmortyapi.com/api/character/avatar/4.jpeg'},
        {'id': 5,'nombre': 'Jerry', 'imagen':'https://rickandmortyapi.com/api/character/avatar/5.jpeg'},
        {'id': 6,'nombre': 'Abadango Cluster Princess', 'imagen':'https://rickandmortyapi.com/api/character/avatar/6.jpeg'},
        {'id': 7,'nombre': 'Abradolf Lincler', 'imagen':'https://rickandmortyapi.com/api/character/avatar/7.jpeg'},
        {'id': 8,'nombre': 'Adjudicator Rick', 'imagen':'https://rickandmortyapi.com/api/character/avatar/8.jpeg'},
        {'id': 9,'nombre': 'Agency Director', 'imagen':'https://rickandmortyapi.com/api/character/avatar/9.jpeg'},
      ]
    }
  }
}
</script>
<style scope>
.container{
  padding-top: 1rem;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}
.b-card-text{
  padding-top: .5rem;
  font-weight: bold;
}
</style>