<template>
    <header> 
        <div class="header-container">
            <div class="logo">
                <img src="@/assets/dc-logo.png" alt="logo">
            </div>
            <nav class="header-navbar">
                <ul>
                    <li v-for="item in navbar" :key="item.id">
                    
                    <a :href="item.url"> {{item.label}} </a> 
                    
                    
                    </li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<script>


export default {
    data() {
        return {
            navbar: [
                {
                    id: "3297503881",
                    label: "characters",
                    url: "#"
                },
                {
                    id: "1442072319",
                    label: "movies",
                    url: "#"
                },
                {
                    id: "5626500757",
                    label: "tv",
                    url: "#"
                },
                {
                    id: "7052945048",
                    label: "games",
                    url: "#"
                },
                {
                    id: "9177724316",
                    label: "collectibles",
                    url: "#"
                },
                {
                    id: "3550652004",
                    label: "videos",
                    url: "#"
                },
                {
                    id: "6313878905",
                    label: "fans",
                    url: "#"
                },
                {
                    id: "7986549430",
                    label: "news",
                    url: "#"
                },
                {
                    id: "3847282382",
                    label: "shop",
                    url: "#"
                },
                {
                    id: "0950959029",
                    label: "comics",
                    url: "#"
                }
            ],
        }
    }
}
</script>

<style lang="scss" scoped>  
@import '@/style/variables.scss';

header{
    
    .header-container{
        margin: 0 auto;
        display: flex;
        justify-content: space-around;
        align-items: center;

        .logo{
            margin: 15px 10px;
        }

        .header-navbar{
            
            ul{
                display: flex;

                li {
                    
                    padding: 15px;
                    list-style: none;
                    text-transform: uppercase;
                    font-weight: bold;
                    cursor: pointer;
                    
                    &:hover{
                        color: $text-tertiary-color;
                        border-bottom: 5px solid $text-tertiary-color;
                    }

                    a{
                        text-decoration: none;
                        color: $text-primary-color;
                    }
                }
            }
        }
    }
};

</style>