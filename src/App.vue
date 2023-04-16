<script>
import siteHeader from './components/siteHeader.vue'
import siteMain from './components/siteMain.vue'
import siteFooter from './components/siteFooter.vue'
import comic from './components/comic.vue'



export default {
  name: 'app',
  components: {
      siteHeader,
      siteMain,
      siteFooter,
      comic
    }
  }
</script>




<template>
  
  <siteHeader></siteHeader>
  <siteMain></siteMain> 
  <siteFooter></siteFooter> 

</template>


<style>
*{
  list-style: none;
  font-family: 'Oswald', sans-serif;
}
</style>
