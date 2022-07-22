<template>
  <div>
    <p>{{film.title}}</p>
    <p>{{film.original_title}}</p>
    <p>{{film.original_language}}</p>
    <p>{{film.vote_average}}</p>
  </div>
</template>

<script>
export default {
    props : ['film']
    
}
</script>

<style>

</style>