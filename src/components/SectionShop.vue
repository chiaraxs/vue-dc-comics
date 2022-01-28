<template>
    <section>
        <div class="shop-zone">

            <ul>
                <li>
                    <div class="comics">
                        <img src="../assets/buy-comics-digital-comics.png" alt="">
                        <span>digital comics</span> 
                    </div> 
                </li>
                <li>
                    <div class="merchandise">
                        <img src="../assets/buy-comics-merchandise.png" alt="">
                        <span>dc merchandise</span>
                    </div> 
                </li>
                <li>
                    <div class="subscription">
                        <img src="../assets/buy-comics-subscriptions.png" alt=""> 
                        <span>subscription</span>
                    </div> 
                </li>
                <li>
                    <div class="local-shop">
                        <img src="../assets/buy-comics-shop-locator.png" alt="">
                        <span>local shop</span>
                     </div> 
                </li>
                <li>
                    <div class="visa">
                        <img src="../assets/buy-dc-power-visa.svg" alt="">
                        <span>dc power visa</span>
                    </div> 
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
    background-color: $bg-color-shop-section;
    text-transform: uppercase;

    .shop-zone{
    margin: 0px 200px;

        ul{
        display: flex;
        justify-content: space-around;
        align-items: center;
        text-transform: uppercase;

            li{
                color: $text-secondary-color;
                list-style: none;
                padding: 20px;
                cursor: pointer;
                
                img{
                    width: 40px;
                    margin-right: 10px;
                }

                &:hover{
                    text-decoration: underline;
                }

            } 
        }
        
        .local-shop img{
            width: 30px;
        }

        .visa img{
            width: 47px;
            margin-top: 13px;

        }
    }
}

</style>