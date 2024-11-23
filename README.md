# Amazon-Clone
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amazon</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css" integrity="sha512-Kc323vGBEqzTmouAECnVceyQqyqdsSiqLQISBL29aUW4U/M7pSPA/gEUZQqv1cwx4OnYxTxve5UMg5GT6L4JJg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="homepage.css">
  <style>
    *{
    margin: 0;
    font-family: Arial;
    border: border-box;
}

.navbar{
    height: 60px;
    background-color: #0f1111;
    color: white;
    display: flex;
    align-items: center;
    justify-content: space-evenly;
}
.nav-logo{
    height: 50px;
    width: 100px;
    
}
.logo{
    background-image: url("amazon_logo.png");
    background-size: cover;
    height: 50px;
    width: 100px;
}
.border{
    border: 2px solid transparent;
}
.border:hover{
    border: 1.5px solid white;
}
/* box2 */
.add-first{
    color: #cccccc;
    font-size: 0.8rem;
    margin-left: 15px;
}
.add-second{
    font-size: 1rem;
    margin-left: 3px;
}
.add-icon{
    display: flex;
    align-items: center;
}
/* box3 */
.nav-search{
    display: flex;
    justify-content: space-evenly;
    background-color: rgb(253, 250, 251);
    width: 620px;
    height: 40px;
    border-radius: 4px;
}

.search-select{
    background-color: #f3f3f3;
    width: 50px;
    text-align: center;
    border-top-left-radius: 4px;
    border-bottom-left-radius: 4px;
    border: none;
}

.search-input{
    width: 100px;
    font-size: 1rem;
    border: none;
}
.search-icon{
    width: 45px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 1.2rem;
    background-color: rgb(249, 193, 60);
    border-top-right-radius: 4px;
    border-bottom-right-radius: 4px;
    color: #0f1111;
}
.nav-search:hover{
    border: 2px solid orange;
}
/* box4 */
span{
    font-size: 0.7rem;
}
.nav-second{
    font-size: 0.05rem;
    font-weight: 700;
}
/* box6 */
.nav-cart i{
    font-size: 30px;
}
.nav-cart{
    font-size: 0.05;
    font-weight: 700;
}
/* Panel */
.panel{
    height: 39px;
    background-color: #222f3d;
    display: flex;
    color: rgb(249, 249, 249);
    align-items: center;
    justify-content: space-evenly;
}

.panel-opn p{
    display: inline;
    margin-left: 15px;
}
.panel-opn{
    width: 70%;
    font-size: 0.8rem;
}

.panel-deals{
    font-size: 0.9rem;
    font-weight: 700;
}
/* Hero section */
.hero-section{
    background-image: url("hero_image.jpg");
    background-size: cover;
    height: 350px;
    display: flex;
    justify-content: center;
    align-items: flex-end;
    
}
.hero-sms{
    background-color: white;
    color: black;
    height: 40px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 0.85rem;
    width: 80%;
    margin-bottom: 25px;
    
}
.hero-sms a{
    color: #008198;
}

/* Shop Section */
.shop-section{
    justify-content: space-evenly;
    display: flex;
    flex-wrap: wrap;
    background-color: #24393c70;
}
.box{
    height: 400px;
    width: 23%;
    /* border: 2px solid black; */
    background-color: white;
    padding: 20px 0px 15px;
    margin-top: 15px;
}
.box-img{
    height: 300px;
    background-size: cover;
    margin-top: 1rem;
    margin-bottom: 1rem;

}
.box-content{
    margin-left: 1rem;
    margin-right: 1rem;
}
.box-content p{
    color: #24393c70;
}

/* Footer */
.footer{
    margin-top: 15px;
}
.foot-panel1{
    background-color: #37475a;
    color: white;
    height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 0.85rem;
}

.foot-panel2{
    background-color: #00272d;
    color: rgb(251, 251, 251);
    height: 300px;
    display: flex;
    justify-content: space-evenly;
    

}
ul{
    margin-top: 20px;
}

ul a{
    display: block;
    color: white;
    font-size: 0.85rem;
    margin-top: 10px;
}
  </style>
</head>
<body>
    <header>
        <div class="navbar">
            <div class="nav-logo border">
                <div class="logo"></div>
            </div>
            
            <div class="nav-address border">
                <p class="add-first">Deliver to</p>
                <div class="add-icon">
                    <i class="fa-solid fa-location-dot"></i>
                    <p class="add-second">India</p>
                </div>
            </div>
            
            <div class="nav-search">
                <select class="search-select">
                    <option>All</option>
                </select>
                <input placeholder="Search Amazon" class="search-input">
                <div class="search-icon">
                    <i class="fa-solid fa-magnifying-glass"></i>
                </div>
            </div>
       
        <div class="nav-singin border">
            <p><span>Hello, sing in</span></p>
            <p class="nav-second">Account & Lists</p>
        </div>

        <div class="nav-return border">
            <p><span>returns</span></p>
            <p class="nav-second">& Orders</p>
        </div>

        <div class="nav-cart border">
            <i class="fa-solid fa-cart-shopping"></i>
            Cart
        </div>
    </div>

    <div class="panel">
        <div class="panel-all">
                <i class="fa-solid fa-bars"></i>
                All
            </div>
            <div class="panel-opn">
                <p>Today's Deals</p>
                <p>Customer Service</p>
                <p>registry</p>
                <p>Gift Cards</p>
                <p>Sell</p>
            </div>

            <div class="panel-deals">
                shop deals in electronics
            </div>
        </div>
    </header>
    <div class="hero-section">
        <div class="hero-sms"><p>We wish you a merry xmas<a> click here to go to Amazon</a></p></div>
    </div>

    <div class="shop-section">
        <div class="box1 box">
           <div class="box-content">
            <h2>Health & personal care</h2>
            <div class="box-img" style="background-image: url('box1_image.jpg');"></div>
            <p>See more</p>
           </div>
        </div>
        <div class="box2 box">
            <div class="box-content">
                <h2>cloths </h2>
                <div class="box-img" style="background-image: url('box2_image.jpg');"></div>
                <p>See more</p>
               </div>
        </div>
        <div class="box3 box">
            <div class="box-content">
                <h2>furniture</h2>
                <div class="box-img" style="background-image: url('box3_image.jpg');"></div>
                <p>See more</p>
               </div>
        </div>
        <div class="box4 box">
            <div class="box-content">
                <h2>electronics</h2>
                <div class="box-img" style="background-image: url('box4_image.jpg');"></div>
                <p>See more</p>
               </div>
        </div>
        <div class="box5 box">
            <div class="box-content">
             <h2>Mekup & beutypic</h2>
             <div class="box-img" style="background-image: url('box5_image.jpg');"></div>
             <p>See more</p>
            </div>
         </div>
         <div class="box6 box">
             <div class="box-content">
                 <h2>Dog food</h2>
                 <div class="box-img" style="background-image: url('box6_image.jpg');"></div>
                 <p>See more</p>
                </div>
         </div>
         <div class="box7 box">
             <div class="box-content">
                 <h2>toy </h2>
                 <div class="box-img" style="background-image: url('box7_image.jpg');"></div>
                 <p>See more</p>
                </div>
         </div>
         <div class="box8 box">
             <div class="box-content">
                 <h2>Fation Treinds</h2>
                 <div class="box-img" style="background-image: url('box8_image.jpg');"></div>
                 <p>See more</p>
                </div>
         </div>

    </div>

    <footer>
        <div class="foot-panel1">
            Back to Top
        </div>
        <div class="foot-panel2">
            <ul>
                <p>Get to know us</p>
                <a href="">careers</a>
                <a href="">Blog</a>
                <a href="">AmazonAbout </a>
                <a href="">Investor Relations</a>
                <a href=""> Amazon Devices</a>
                <a href="">amazon Science</a>   
            </ul>

            <ul>
                <p>Get to know us</p>
                <a href="">careers</a>
                <a href="">Blog</a>
                <a href="">AmazonAbout </a>
                <a href="">Investor Relations</a>
                <a href=""> Amazon Devices</a>
                <a href="">amazon Science</a>   
            </ul>

            <ul>
                <p>Get to know us</p>
                <a href="">careers</a>
                <a href="">Blog</a>
                <a href="">AmazonAbout </a>
                <a href="">Investor Relations</a>
                <a href=""> Amazon Devices</a>
                <a href="">amazon Science</a>   
            </ul>

            <ul>
                <p>Get to know us</p>
                <a href="">careers</a>
                <a href="">Blog</a>
                <a href="">AmazonAbout </a>
                <a href="">Investor Relations</a>
                <a href=""> Amazon Devices</a>
                <a href="">amazon Science</a>   
            </ul>
        </div>

    </footer>
</body>
</html>
