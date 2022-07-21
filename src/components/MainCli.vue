<template>
  <main>
    <CardsList v-for="(film, index) in films" :key="index"/>
  </main>
</template>

<script>

import CardsList from './/CardsList.vue'

export default {
    props:{
    'films' : {
        required: true,
        type: Array,
    },
},
    components:{
    CardsList,
}
}
</script>

<style>

</style>
