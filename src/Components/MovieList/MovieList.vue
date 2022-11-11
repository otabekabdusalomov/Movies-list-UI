<template>
    <ul class="movies-list list-group">
        <MovieListItem v-for="movie in movies" :movie="movie" />
    </ul>
</template>

<script>
import MovieListItem from '../Movie-list-item/MovieListItem.vue'
export default {
    components: {
        MovieListItem,   
    },   

     data() {
        return {
            movies: [
                {
                    name: "Avatar",
                    viewers: 811,
                    favourite: false,
                    like: true
                },
                {
                    name: "Oamar",
                    viewers: 411,
                    favourite: false,
                    like: true
                },
                {
                    name: "Ertugrul",
                    viewers: 450,
                    favourite: true,
                    like: false,
                },
                {
                    name: "Dasturchi",
                    viewers: 423,
                },
                
            ],
        }
     }
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