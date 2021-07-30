<template>
  <div>

    <Header />
  
   <div class="container">
     <div class="col">
       <div class="row">
         <main>
           
           <router-view></router-view>
         </main>
       </div>
     </div>
   </div>
  </div>
</template>

<script>
import Header from './components/Header.vue'
export default {
  name: 'App',

  components: {
    Header
  }
}
</script>

<style lang="scss">
   @import '../sass/frontoffice/global';
  
</style>