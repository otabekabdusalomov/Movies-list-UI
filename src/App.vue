<template>
  <div class="app">
    <div class="content">
      <app-info />
    </div>
    <!-- <starter-information /> -->
    
  </div>
</template>


<script>
import AppInfo from './Components/app-info/AppInfo.vue'
import StarterInformation from './Course all/StarterInformation.vue'
export default {
  components: { 
    StarterInformation,
    AppInfo,
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
</style>