<template>
  <main>
    <CardsList v-for="(film, index) in films" :key="index"
    :film= "film"/>
    <SeriesList v-for="(serie, index) in series" :key="index"
    :serie= "serie"/>
  </main>
</template>

<script>

import CardsList from './/CardsList.vue'
import SeriesList from './/SeriesList.vue'

export default {
    props:{
    'films' : {
        required: true,
        type: Array,
    },
    'series' : {
        required: true,
        type: Array,
    },
},
    components:{
    CardsList,
    SeriesList,
}
}
</script>

<style>

</style>
