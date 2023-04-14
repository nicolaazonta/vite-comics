<script>
import siteHeader from './components/siteHeader.vue'
import siteMain from './components/siteMain.vue'
import siteFooter from './components/siteFooter.vue'


export default {
  name: 'app',
  components: {
      siteHeader,
      siteMain,
      siteFooter
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
