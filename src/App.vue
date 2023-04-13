<script>



  export default {
    data(){
      return{

      }
    }
  }
</script>




<template>
  <header>
    <div class="container d-flex justify-content-between align-items-center">
      <div class="left_group">
        <div class="logo">
          <img class="img-fluid" src="./assets/img/dc-logo.png" alt="">
        </div>
      </div>
          <ul class="right_group d-flex align-items-center text-uppercase list-style-none">
            <li class="active">
              <span class="self-align-center">characters</span>
              <div class="line_bottom justify-self-end"></div>  
            </li>
            <li class="px-1">comics</li>
            <li class="px-1">movies</li>
            <li class="px-1">tv</li>
            <li class="px-1">games</li>
            <li class="px-1">collectibles</li>
            <li class="px-1">videos</li>
            <li class="px-1">fans</li>
            <li class="px-1">news</li>
            <li class="px-1">shop</li>
          </ul>
    </div>
  </header>  
<!-- 
  <siteHeader></siteHeader>
  <siteMain></siteMain>
  <siteFooter></siteFooter> -->

</template>


<style>
ul>li{
  padding: 0 1rem;
  display: flex;
  flex-direction: column;
  align-items: center;
}
*{
  list-style: none;
  font-family: 'Oswald', sans-serif;
}
header{
  background-color: rgb(179, 166, 166);
}
.active{
  color: #0282F9;  
}
.line_bottom{
  background-color: #0282F9;
  height: 2px;
  width: 80%;
}
</style>
