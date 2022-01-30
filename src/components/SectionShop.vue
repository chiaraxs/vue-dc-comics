<template>
    <section>
        <div class="shop-zone">

            <ul>
                <li>
            
                    <img src="../assets/buy-comics-digital-comics.png" alt="">
                    <span>digital comics</span> 
                    
                </li>
                <li>
                    
                    <img src="../assets/buy-comics-merchandise.png" alt="">
                    <span>dc merchandise</span>
                    
                </li>
                <li>
                    
                    <img src="../assets/buy-comics-subscriptions.png" alt=""> 
                    <span>subscription</span>
                    
                </li>
                <li>
                    
                    <img class="shop-locator" src="../assets/buy-comics-shop-locator.png" alt="">
                    <span>comic shop locator</span>
                     
                </li>
                <li>
                   
                    <img class="visa" src="../assets/buy-dc-power-visa.svg" alt="">
                    <span>dc power visa</span>
                   
                </li>
               
            </ul>
            
        </div>
    </section>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';

section{
    background-color: $tertiary-color;
    text-transform: uppercase;

    .shop-zone{
    margin: 0px 200px;

        ul{
        display: flex;
        justify-content: space-around;
        align-items: center;
        text-transform: uppercase;

            li{
                display: flex;
                align-items: center;
                color: $secondary-color;
                list-style: none;
                padding: 20px;
                cursor: pointer;
                
                img{
                    width: 40px;
                    margin-right: 15px;
                }

                &:hover{
                    text-decoration: underline;
                }

            } 
        }
        
        .shop-locator{
            width: 28px;
        }

        .visa {
            width: 40px;
        }
    }
}

</style>