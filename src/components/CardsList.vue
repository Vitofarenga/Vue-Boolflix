<template>
  <div>
    <ul>
      <li>{{film.title}} - {{film.original_title}} - {{film.original_language}} - {{film.vote_average}}</li>
    </ul>
  </div>
</template>

<script>
export default {
    props : ['film']
    
}
</script>

<style>

</style>