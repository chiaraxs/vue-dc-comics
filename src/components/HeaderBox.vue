<template>
    <header> 
        <div class="header-container">
            <div class="logo">
                <img src="@/assets/dc-logo.png" alt="logo">
            </div>
            <nav class="header-navbar">
                <ul>
                    <li><a href="#"></a>characters</li>
                    <li><a href="#"></a>comics</li>
                    <li><a href="#"></a>movies</li>
                    <li><a href="#"></a>tv</li>
                    <li><a href="#"></a>games</li>
                    <li><a href="#"></a>collectibles</li>
                    <li><a href="#"></a>videos</li>
                    <li><a href="#"></a>fans</li>
                    <li><a href="#"></a>news</li>
                    <li><a href="#"></a>shop</li>
                    
                </ul>
            </nav>
        </div>
    </header>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>  

header{
    
    .header-container{
        // max-width: 1200px;
        margin: 0 auto;
        display: flex;
        justify-content: space-around;
        align-items: center;

        .logo{
            margin: 15px 10px;
            
            img{
                width: 80px;
            }
        }

        .header-navbar{
            
            ul{
                display: flex;

                li {
                    color: #484646;
                    padding: 15px;
                    list-style: none;
                    text-transform: uppercase;
                    font-weight: bold;
                    cursor: pointer;
                    
                    &:hover{
                        color:#1e86ed ;
                        border-bottom: 4px solid #1e86ed;
                    }
                }
            }
        }
    }
}

</style>