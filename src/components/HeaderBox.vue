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
    props: {
       navbar: Array,
    },
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
                        color: $tertiary-color;
                        border-bottom: 5px solid $tertiary-color;
                    }

                    a{
                        text-decoration: none;
                        color: $primary-color;
                    }
                }
            }
        }
    }
};

</style>