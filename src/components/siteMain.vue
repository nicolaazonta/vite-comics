<script>
    import comic from '../components/comic.vue'
    import comics from '../data/comics'
    export default {
        name: 'siteMain',
        components: {
            comic
        },
        data() {
            return{
                comics: comics
            }
            
        }
    }
</script>


<template>
    <main>
        <div class="primary_section">
            <div class="container w-75">
                <div class="row flex-wrap py-4">
                    
                    <comic v-for="comic in comics" :img="comic.thumb" :text="comic.series"/>
                                          

                </div>
                
            </div>
        </div>
    
        <div class="secondary_section ">
            <div class="py-3 container d-flex justify-content-around align-content-center">
    
                <section class="d-flex align-items-center">
                    <img class="img-fluid" src="../assets/img/buy-comics-digital-comics.png" alt="">
                    <span>digital comics</span>
                </section>
    
                <section class="d-flex align-items-center">
                    <img class="img-fluid" src="../assets/img/buy-comics-merchandise.png" alt="">
                    <span>dc merchandise</span>
                </section>
    
                <section class="d-flex align-items-center">
                    <img class="img-fluid" src="../assets/img/buy-comics-subscriptions.png" alt="">
                    <span>subscription</span>
                </section>
    
                <section class="d-flex align-items-center">
                    <img class="img-fluid" src="../assets/img/buy-comics-shop-locator.png" alt="">
                    <span>comic shop locator</span>
                </section>
    
                <section class="d-flex align-items-center">
                    <img class="img-fluid" src="../assets/img//buy-dc-power-visa.svg" alt="">
                    <span>dc power visa</span>
                </section>
            </div>
        </div>
    </main>
</template>


<style lang="scss" scoped>

</style>