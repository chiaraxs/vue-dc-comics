<template>
    <footer>
        <div class="footer-left">
            
            <ul>
                <li><h3>dc comics</h3></li>
                <li><a href="#">Characters</a></li>
                <li><a href="#">Comics</a></li>
                <li><a href="#">Movies</a></li>
                <li><a href="#">Tv</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Videos</a></li>
                <li><a href="#">News</a></li>
            </ul>

            
            <ul>
                <li><h3>shop</h3></li>
                <li><a href="#">Shop DC</a></li>
                <li><a href="#">Collectibles</a></li>
            </ul>
                    
                
                   
            
            <ul>
               <li><h3>dc</h3></li>
                <li><a href="#">Terms Of Use</a></li>
                <li><a href="#">Privacy policy (New)</a></li>
                <li><a href="#">Ad Choices</a></li>
                <li><a href="#">Advertising</a></li>
                <li><a href="#">Jobs</a></li>
                <li><a href="#">Subscriptions</a></li>
                <li><a href="#">Talent Workshops</a></li>
                <li><a href="#">CPSC Certificates</a></li>
                <li><a href="#">Ratings</a></li>
                <li><a href="#">Shop Help</a></li>
                <li><a href="#">Contact Us</a></li>
            </ul>
                    

                   
            
            <ul>
                <li><h3>sites</h3></li>
                <li><a href="#">DC</a></li>
                <li><a href="#">MAD Magazine</a></li>
                <li><a href="#">DC Kids</a></li>
                <li><a href="#">DC Universe</a></li>
                <li><a href="#">DC Power Visa</a></li>
            </ul>
                    
        </div>  

        <div class="footer-right-logo">
            <img src="../assets/dc-logo-bg.png" alt="">
        </div> 
        
    </footer>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';

footer{
    display: flex;
    background-image: $img-footer;
    background-size: cover;
    overflow: hidden;

    .footer-left{
        display: flex;
        padding: 70px;
        margin-left: 20px;
        
        

        ul{
            margin: 10px 15px 10px 30px;
            

            li{
            
            list-style: none;
            margin-left: 20px;
            line-height: 30px;
           
                h3{
                    color: $text-secondary-color;
                    text-transform: uppercase;
                }

                a{
                    text-decoration: none;
                    color: grey;
                           
                    &:hover{
                        color: $text-secondary-color;
                    }
                }

            }
        }
    }

    .footer-right-logo{
       margin: 10px 200px;
    
       img{
        margin: -80px 0;
       }
    }
}


</style>