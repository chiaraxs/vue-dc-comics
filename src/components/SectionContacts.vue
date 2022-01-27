<template>
    <section>
        <div class="contacts">
            <div class="sign-up">
                <button>SIGN-UP NOW!</button>
            </div>

                <div class="icons-zone">
                    <span>FOLLOW US</span>
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
        }
    

    .icons-zone{
        text-align: center;

        margin-right: 200px;
        img {
           padding: 10px;
        }
    }
}


</style>