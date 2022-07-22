<template>
    <header>
        <input type="text" class="form-control rounded" placeholder="Search" 
        aria-label="Search" aria-describedby="search-addon" v-model="search"/>
        <button @click="$emit('search', search)">Search</button>
    </header>
</template>

<script>
export default {

}
</script>

<style scoped>
header{
    width: 100%;
    height: 5rem;
    background-color: black;
}

</style>