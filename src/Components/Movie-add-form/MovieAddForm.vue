<template>
    <div class="movie-add-form">
      <h1>Add new movies </h1>

      <form class="add-form d-flex">
        <input class="add-form-label form-control" type="text" placeholder="What movies?">
        <input class="add-form-label form-control" type="text" placeholder="Seen how many times?">

        <button class="btn btn-outline-dark" type="submit">Add</button>
      </form>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
.movie-add-form {
    margin-top: 2rem;
    padding: 1.5rem;
    background-color: #fcfaf5;
    border-radius: 4px;
    box-shadow: 15px 15px 15px rgba(0, 0, 0, 0.15);
}
</style>