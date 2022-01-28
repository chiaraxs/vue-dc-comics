<template>
    <section>
        <div class="contacts">
            <div class="sign-up">
                <button><a href="#">sign-up now!</a></button>
            </div>

                <div class="icons-zone">
                    <span>follow us</span>
                    <img src="../assets/footer-facebook.png" alt="">
                    <img src="../assets/footer-twitter.png" alt="">
                    <img src="../assets/footer-youtube.png" alt="">
                    <img src="../assets/footer-pinterest.png" alt="">
                    <img src="../assets/footer-periscope.png" alt="">
                </div>
        </div>
    </section>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';

.contacts{
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #303030;

    .sign-up{
        margin-left: 100px;

        button{
            background-color: rgb(48, 48, 48);
            border: none;
            border: 2px solid $text-tertiary-color;
            padding: 10px;
            margin: 20px;

            a{
                text-transform: uppercase;
                text-decoration: none;
                color: $text-secondary-color;
            }
        }
    }
    

    .icons-zone{
        display: flex;
        justify-content: space-around;
        margin-right: 200px;
        
        img {
           padding: 10px;
           width: 50px;
           height: 50px;


           &:hover{
               background-color: $text-secondary-color;
               border-radius: 50px 50px;
            }
        }

        span{
            color: $text-tertiary-color;
            font-weight: bold;
            font-size: 20px;
            text-transform: uppercase;
            margin: 15px 10px;

            &:hover{
                border-bottom: 1px solid $text-tertiary-color;
            }
        }
    }
}


</style>