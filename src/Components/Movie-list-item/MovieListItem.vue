<template>
    <li class="movies-list-item d-flex justify-content-between">
        <span class="movies-list-item-label">Legioner</span>
        <input class="movies-list-item-input" type="number" defaultValue="811">

        <div class="d-flex justify-content-center align-items-center">
              <button class="btn-cookie btn-sm">
                <i class="fas fa-cookie"></i>
              </button>

              <button class="btn-trash btn-sm">
                <i class="fas fa-trash"></i>
              </button>

              <button class="btn-star btn-sm">
                <i class="fas fa-star"></i>
              </button>
              
        </div>
    </li>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.movies-list-item {
  padding: 15px 20px;
  border: none;
  border-bottom: 1px solid #3d5a80;
}
.movies-list-item:last-child {
  border-bottom: none;
}
.movies-list-item-label {
  line-height: 35px;
  font-size: 20px;
  cursor: pointer;
  width: 550px;
}
.movies-list-item-input {
  line-height: 35px;
  font-size: 20px;
  text-align: center;
  border: 0;
  outline: none;
}
.movies-list-item button {
  width: 35px;
  height: 35px;
  margin: 3px;
  font-size: 17px;
  border: none;
  cursor: pointer;
}
.movies-list-item .btn-cookie {
  color: #e89f3e;
}
.movies-list-item .btn-trash {
  color: #e5383b;
}
.movies-list-item .btn-star {
  color: #ffd700;
} 
.movies-list-item.favourite .movies-list-item-label {
  color: #e09f3e;
}  
.movies-list-item.favourite .movies-list-item-input {
  color: #e09f3e;
}


</style>