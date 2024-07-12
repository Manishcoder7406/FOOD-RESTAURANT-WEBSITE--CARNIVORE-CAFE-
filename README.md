# FOOD-RESTAURANT-WEBSITE--CARNIVORE-CAFE-


********HTML CODE********

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Carnivore Cafe</title>
    <link rel="stylesheet" href="css/style.css">
    <link href='https://fonts.googleapis.com/css?family=Bree Serif' rel='stylesheet'>
    <link href='https://fonts.googleapis.com/css?family=Baloo Bhai' rel='stylesheet'>
</head>
<body>
    <section class="menu">
        <div class="nav">
            <div class="logo"><h1>CARNIVORE<b>CAFE</b></h1></div>
            <ul>
                <li><a class="active" href="#">Home</a></li>
                <li><a href="#">Menu</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">About us</a></li>
                <li><a href="#">gallery</a></li>
            </ul>
            <div>
                <input type="submit" class="signin" value="Sign in" name="signin">
                <input type="submit" class="signup" value="Sign up" name="signup">             

        </div>
    </section>
    <section class="grid">
        <div class="content">
            <div class="content-left">
                <div class="info">
                    <h2>Indulge in our<br>Juicy grilled Perfection.</h2>
                    <p>Hey, Our delicious food is waiting for you, <br>
                       We are always near to you with fresh item of food </p>
                </div>
                <button>Explore food</button>
            </div>
            <div class="content-right">
                <img src="img2/ipl.png" alt="">
            </div>
        </div>
    </section>
    <section class="category">
        <div class="list-items">
            <h3>Popular Dishes</h3>
            <div class="card-list">
                <div class="card">
                    <img src="img2/burger2.png" alt="">
                    <div class="food-title">
                        <h1>Chicken Burger</h1>
                    </div>
                    <div class="desc-food">
                        <p>"Sink your teeth into our ultimate chicken burger"</p>
                    </div>
                    <div class="price">
                        <span>Rs.70</span>
                    </div>
                </div>
                <div class="card">
                    <img src="img2/chicken.png" alt="">
                    <div class="food-title">
                        <h1>Chicken Drumsticks</h1>
                    </div>
                    <div class="desc-food">
                        <p>"Savor the flavor of our juicy chicken drumsticks."</p>
                    </div>
                    <div class="price">
                        <span>Rs.450</span>
                    </div>
                </div>
                <div class="card">
                    <img src="img2/fries.png" alt="">
                    <div class="food-title">
                        <h1>Peri-Peri Fries</h1>
                    </div>
                    <div class="desc-food">
                        <p>"Spice up your day with our irresistible peri-peri fries."</p>
                    </div>
                    <div class="price">
                        <span>Rs.150</span>
                    </div>
                </div>
                <div class="card">
                    <img src="img2/chnuggets.png" alt="">
                    <div class="food-title">
                        <h1>Chicken Nuggets</h1>
                    </div>
                    <div class="desc-food">
                        <p>"Irresistible crispy chicken nuggets-bbite-sized bliss!"</p>
                    </div>
                    <div class="price">
                        <span>Rs.350</span>
                    </div>
                </div>
            </div>
        </div>
    </section>
</body>
</html>


********CSS CODE********

 
 
::after,::before{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
 }

 body{
    margin: 0 100px;
    background-color: #Add8e6;
 }


 /* Menu  */
 .nav{
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 30px 0;
 }

 /* active  */

 .nav{
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 30px 0;
 }

 .nav .logo h1{
    font-weight: 600;
    font-family: sans-serif;
    color: black;
 }

 .nav .logo b{
    color: red;
 }

 .nav ul{
    display: flex;
    list-style: none;
 }

 .nav ul li{
    margin-right: 30px;

 }

 .nav ul li a{
    text-decoration: none;
    color: black;
    font-weight: 500;
    font-family: sans-serif;
    font-size: 17px;

 }

 /* Active  */
 
 .nav ul .active::after{
    content:'';
    width: 50%;
    height: 3px;
    background-color: red;
    display:flex;
    position:relative;
    margin-left: 10px;
 }

 /* input  */

 input{
    padding: 10px 20px;
    cursor: pointer;
    font-weight: 600;

 }
 .signin{
    background:transparent;
    border: none;
 }

 .signup{
    background-color: red;
    color: #ffffff;
    border: none;
    border-radius: 5px;
 }


 /* content  */

 .content{
    display: grid;
    grid-template-columns: 50% auto;
    gap: 30px;
    align-items: center;
    justify-content: space-between;
    width: 100%;
 }
 

 /* content text  */
 /* text left side  */

 .content .content-left{
    display: block;
    width: 100%;
 }

 .content  .content-left   .info{
    max-width: 100%;
    display: flex;
    flex-direction: column;
 }

 .content  .content-left  .info  h2{
    font-size: 60px;
    font-family: Baloo Bhai;
    margin-bottom: 30px;
 }
 .content  .content-left  .info  p{
    font-size: 20px;
    line-height: 2pc;
    margin-bottom: 30px;
    font-family: sans-serif;
 }

 /* Content  */
 /* button  */

 .content .content-left button{
    padding: 10px 23px;
    background-color: red;
    color: #ffffff;
    border-radius: 5px;
    border: none;
    cursor: pointer;
 }
 

 /* content image right side  */
 .content  .content-right{
    display: block;
    width: 100%;
 }

 .content .content-right img{
    width: 600px;
    height: auto;
    position: relative;
    user-select: none;
    animation: rotate 10s linear infinite;
 }

 /* content animation  */
 
 @keyframes rotate{
    0%{
        transform: rotate(0deg);

    }
    100%{
        transform: rotate(360deg);
    }
 }

 /* cards  */
 .category{
    width: 100%;
    display: flex;
    justify-content: center;
    margin-bottom: 50px;
 }

 .category  .list-items{
    width: 90%;
    position: relative;
    margin-top: 100px;

 }
 .category  .list-items h3{
    font-size: 20px;
    font-weight: 600;
    font-family: sans-serif;
    margin-bottom: 80px;
 }

 .category .list-items .card-list{
    display: grid;
    grid-template-columns: repeat(4,1fr);
 }

 .category .card-list .card{
    width: 200px;
    height: auto;
    display: block;
    padding: 10px;
    border-radius: 10px;
    position: relative;
    background: #ffffff;
    outline: 2px solid red;
 }

 .category .card-list .card img{
    width: 100px;
    height: auto;
    bottom: 195px;
    left:50px;
    object-fit: cover;
    object-position: center;
    background-repeat: no-repeat;
    position: absolute;
    box-shadow: 0 20px 20px red;
    border-radius:50%;
 }

 .category .card-list .card .food-title{
    padding: 40px 0 10px;
 }
  
 .category .card-list .card .food-title h1{
    text-align: center;
    font-weight: bold;
    font-size: 16px;
    font-family: Bree Serif;
 }
 .category .card .desc-food p{
    font-size: 13px;
    text-align: center;
    font-weight: bold;
    margin-bottom: 20px;
    font-family: sans-serif;
 }

 .category .card .price span{
   display:flex ;
   align-items: center;
   font-weight: bolder;
   justify-content: space-between;
 }


 





