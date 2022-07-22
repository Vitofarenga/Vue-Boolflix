<template>
  <div id="app">
   <HeaderCli @search = "getFilms"/>
   <MainCli :films="films" />
   <FooterCli />
  </div>
</template>

<script>

import HeaderCli from './components/HeaderCli.vue';
import MainCli from './components/MainCli.vue';
import FooterCli from './components/FooterCli.vue';
import axios from 'axios';

export default {
  name: 'App',
  components: {
    HeaderCli,
    MainCli,
    FooterCli,
  },
  data:function(){
    return{
      films: [],
      apiUrl : 'https://api.themoviedb.org/3/search/movie?api_key=c18cf7224de4f7650fa675de8757d068&query='
    }
  },
  methods:{
      getFilms: function(query){
        axios.get(this.apiUrl + query)
        .then((result)=>{
          console.log(result.data.results);
          this.films = result.data.results
        })
      },
      
  },
}
</script>
<style lang="scss">
@import 'bootstrap';

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
