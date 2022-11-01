<template>
    <ul class="movies-list list-group">
        <movie-list-item />
        <movie-list-item />
        <movie-list-item />
    </ul>
</template>

<script>
import MovieListItem from '../Movie-list-item/MovieListItem.vue'
export default {
    components: {
        MovieListItem,
        
    },
    
}
</script>

<style scoped>
.movies-list {
    margin-top: 2rem;
    padding: 1.5rem;
    background-color: #fcfaf5;
    box-shadow: 15px 15px 15px rgba(0, 0, 0, 0.15); 
}
</style>