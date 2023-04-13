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
              <span class="">characters</span>
              <div class="line_bottom"></div>  
            </li>
            <li class="">
              <span class="">comics</span>
              <div class="line_bottom"></div>  
            </li>
            <li class="">
              <span class="">movies</span>
              <div class="line_bottom"></div>  
            </li>
            <li class="">
              <span class="">tv</span>
              <div class="line_bottom"></div>  
            </li>
            <li class="">
              <span class="">games</span>
              <div class="line_bottom"></div>  
            </li>
            <li class="">
              <span class="">collectibles</span>
              <div class="line_bottom"></div>  
            </li>
            <li class="">
              <span class="">videos</span>
              <div class="line_bottom"></div>  
            </li>
            <li class="">
              <span class="">fans</span>
              <div class="line_bottom"></div>  
            </li>
            <li class="">
              <span class="">news</span>
              <div class="line_bottom"></div>  
            </li>
            <li class="">
              <span class="">shop</span>
              <div class="line_bottom"></div>  
            </li>
           
          </ul>
    </div>
  </header> 
  
  <main>
    <div class="primary_section">
      <div class="container d-flex align-items-center">
        <h2>---------content here---------</h2>
      </div>
    </div>

    <div class="secondary_section ">
      <div class="container d-flex justify-content-around align-content-center">

        <section class="d-flex align-items-center">
          <img class="img-fluid" src="./assets/img/buy-comics-digital-comics.png" alt="">
          <span>digital comics</span>  
        </section>

        <section class="d-flex align-items-center">
          <img class="img-fluid" src="./assets/img/buy-comics-merchandise.png" alt="">
          <span>dc merchandise</span>  
        </section>

        <section class="d-flex align-items-center">
          <img class="img-fluid" src="./assets/img/buy-comics-subscriptions.png" alt="">
          <span>subscription</span>  
        </section>

        <section class="d-flex align-items-center">
          <img class="img-fluid" src="./assets/img/buy-comics-shop-locator.png" alt="">
          <span>comic schop locator</span>  
        </section>

        <section class="d-flex align-items-center">
          <img class="img-fluid" src="./assets/img//buy-dc-power-visa.svg" alt="">
          <span>dc power visa</span>  
        </section>

      </div>
     
      
    </div>
  </main>
<!-- 
  <siteHeader></siteHeader>
  <siteMain></siteMain>
  <siteFooter></siteFooter> -->

</template>


<style>
/* #region---------header */
ul>li{
  padding: 0 1rem;
  display: flex;
  flex-direction: column;
  align-items: center;
}
li>span{
  justify-self: center;
}
li>div{
  justify-self: end;
}
*{
  list-style: none;
  font-family: 'Oswald', sans-serif;
}
header{
  background-color: #ffffff;
}
.active{
  color: #0282F9;  
}
.line_bottom{
  background-color: #0282F9;
  height: 2px;
  width: 80%;
}
/* #endregion---------header */

/* #region---------main */
main>.primary_section{
  color: white;
  background-color: #1C1C1C;
  height: 8rem;
}
main>.secondary_section{
  background-color: #0282F9;
  height: 8rem;
}
main .secondary_section img{
  color: white;
  width: 3rem;
}
main .container{
  height: 100%;
}
/* #endregion---------main */



main{
  height: 7rem;
}
</style>
