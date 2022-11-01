<template>
  <div class="app">
    <div class="content">
      <AppInfo />
      <div class="search-panel">
        <SearchPanel />
        <AppFilter />
      </div>
      

      <MovieList />
      <MovieAddForm />
    </div>
    
    
    
        
    <!-- <starter-information /> -->
    
  </div>
</template>


<script>
import StarterInformation from './Course all/StarterInformation.vue'
import AppInfo from './Components/app-info/AppInfo.vue'
import SearchPanel from './Components/SearchPanel/SearchPanel.vue'
import AppFilter from './Components/App-filter/AppFilter.vue'
import MovieList from './Components/MovieList/MovieList.vue'
import MovieAddForm from './Components/Movie-add-form/MovieAddForm.vue'



export default {
  components: { 
    StarterInformation,
    AppInfo,
    SearchPanel,
    AppFilter,
    MovieList,
    MovieAddForm,
    
  },
  
}
</script>
<style>
.app {
  height: 100vh;
  color: black;
}
.content {
  width: 1000px;
  min-height: 700px;
  background-color: #FFF;
  margin: 0 auto;
  padding: 5rem 0;
}
.search-panel {
  margin-top: 2rem;
  padding: 1.5rem;
  background-color: #fcfaf5;
  box-shadow: 15px 15px 15px rgba(0, 0, 0, 0.15);
}
</style>