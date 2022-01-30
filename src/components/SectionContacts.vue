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
    background-color: $bg-color-main;

    .sign-up{
        margin-left: 100px;

        button{
            background-color: rgb(48, 48, 48);
            border: none;
            border: 2px solid $tertiary-color;
            padding: 15px;
            margin: 20px;

            a{
                text-transform: uppercase;
                font-weight: bold;
                text-decoration: none;
                color: $secondary-color;
                font-size: 15px;
            }

            &:hover{
                background-color: $tertiary-color;
            }
        }
    }
    

    .icons-zone{
        display: flex;
        justify-content: space-around;
        margin-right: 300px;
        
        img {
           padding: 10px;
           width: 50px;
           height: 50px;
           cursor: pointer;


           &:hover{
               background-color: $secondary-color;
               border-radius: 50px 50px;
            }
        }

        span{
            color: $tertiary-color;
            font-weight: bold;
            font-size: 20px;
            text-transform: uppercase;
            margin: 15px 10px;
            cursor: pointer;

            &:hover{
                border-bottom: 1px solid $tertiary-color;
            }
        }
    }
}


</style>