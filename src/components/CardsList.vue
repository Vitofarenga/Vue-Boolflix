<template>
  <div>
    <ul>
      <li>{{film.title}}</li>
      <li>{{film.original_title}}</li>
      <li>{{film.original_language}}</li>
      <li>{{film.vote_average}}</li>
    </ul>
  </div>
</template>

<script>
export default {
   data:function(lingua){
    if(lingua = "it" ){
      lingua = "https://www.google.com/imgres?imgurl=https%3A%2F%2Fm.media-amazon.com%2Fimages%2FI%2F71byT8ccGML.jpg&imgrefurl=https%3A%2F%2Fwww.amazon.it%2FSTICKERS-BANDIERA-ITALIANA-TRICOLORE-ADESIVA%2Fdp%2FB073BKBHWZ&tbnid=LuOjAQ77lLYWrM&vet=12ahUKEwi_-6G81Yz5AhWD-aQKHU9tBicQMygBegUIARD1AQ..i&docid=xX3Glr3JXOvjyM&w=1821&h=1285&q=bandiera%20italiana&ved=2ahUKEwi_-6G81Yz5AhWD-aQKHU9tBicQMygBegUIARD1AQ"
    }
    if(lingua = "fr"){
      lingua = "https://www.google.com/imgres?imgurl=https%3A%2F%2Fupload.wikimedia.org%2Fwikipedia%2Fcommons%2Fthumb%2Fb%2Fbc%2FFlag_of_France_%25281794%25E2%2580%25931815%252C_1830%25E2%2580%25931974%252C_2020%25E2%2580%2593present%2529.svg%2F280px-Flag_of_France_%25281794%25E2%2580%25931815%252C_1830%25E2%2580%25931974%252C_2020%25E2%2580%2593present%2529.svg.png&imgrefurl=https%3A%2F%2Fit.wikipedia.org%2Fwiki%2FBandiera_della_Francia&tbnid=S-UD1OvfiDsq1M&vet=12ahUKEwiU2KHA1Yz5AhVDtaQKHSB9DQQQMygAegUIARDyAQ..i&docid=_m0i_5eywhaINM&w=280&h=187&q=bandiera%20francia&ved=2ahUKEwiU2KHA1Yz5AhVDtaQKHSB9DQQQMygAegUIARDyAQ"
    }
    if(lingua = "en"){
      lingua = "https://www.google.com/imgres?imgurl=https%3A%2F%2Fupload.wikimedia.org%2Fwikipedia%2Fcommons%2Fthumb%2F8%2F83%2FFlag_of_the_United_Kingdom_%25283-5%2529.svg%2F280px-Flag_of_the_United_Kingdom_%25283-5%2529.svg.png&imgrefurl=https%3A%2F%2Fit.wikipedia.org%2Fwiki%2FBandiera_del_Regno_Unito&tbnid=tJIJYV4ihVNngM&vet=12ahUKEwiXlKLE1Yz5AhUIP-wKHcfgBvUQMygAegUIARD2AQ..i&docid=lptEYn3xZrrIsM&w=280&h=168&q=bandiera%20inghilterra&ved=2ahUKEwiXlKLE1Yz5AhUIP-wKHcfgBvUQMygAegUIARD2AQ"
    }
    else{
      lingua = lingua
    }
  },
}
</script>

<style>

</style>