<template>
    <main> 
        <div class="current-series">current series</div>
            
        <div class="cards-box"> 
            <div v-for="(card, index) in cards" :key="index" class="cards">
                <img :src="card.thumb">
                <h3>{{card.series}}</h3>
            </div>
        </div>

        <button>load more</button> 
    </main>
</template>

<script>

export default {
    props: {
       cards: Array,
    },
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';

main{
    background-color: $bg-color-main;
    position: relative;
    text-transform: uppercase;
    color: $secondary-color;
    text-align: center;
    font-size: 13px;
    font-weight: bold;

    .current-series{
        position: absolute;
        margin: -20px 250px;
        width: 200px;
        background-color: $tertiary-color;
        padding:  10px 10px;
        font-size: 18px;
    }

    .cards-box{
       width: 70%;
       margin: 0 auto;
       display: flex;
       justify-content: space-around;
       flex-wrap: wrap;
       

        .cards{
            margin-top: 30px;
            width: 200px;
            padding: 10px;
           
            
            img{
                width: 100%;
                cursor: pointer;

                &:hover{
                    transition: 0,5s;
                    transform: scale(1.03);
                    opacity: 50%;
                }
            }

            h3{
                margin-top: 5px;
            }
        }
   
    }

    button{
            background-color: $tertiary-color;
            border: none;
            padding: 15px 50px;
            margin: 20px auto;
            color: $secondary-color;
            text-transform: uppercase;
            font-weight: bold;
            font-size: 15px;
            cursor: pointer;
            
            &:hover{
                background-color: $primary-color;
            }
            
        }
}

</style>