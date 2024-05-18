<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>landing page</title>
    <link rel="stylesheet" href="landing_page.css">
</head>
  <style>
    body{
    margin: 0px;
    padding: 0px;
    box-sizing: border-box;
}
.main{
    width: 100%;
}
nav{
    width: 100%;
    height: 80px;
    line-height: 80px;
    display: flex;
    justify-content: space-between;
  background-color: black;
}
.logo a{
    font-size: 40px;
    color: rgb(168, 40, 40);
    font-weight: bold;
    margin-left: 100px;
}
a{
    text-decoration: underline;
    color: white;
    font-size: 19px;
    transition: 0.5s all ease;
}
ul{
    margin: 0px;
    margin-right:100px ;
}
ul li{
    float: left;
    padding: 0px 10px;
    list-style: none;
}
ul li a:hover{
    color: white;


}
.header{
    background-image: url('https://www.shutterstock.com/image-vector/shop-now-message-neon-light-260nw-1826396891.jpg');
    background-position: center ;
    background-size: cover;
    height:100vh ;
    background-repeat: repeat;
    padding-top:30px;
}
.content{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    color:white;
   text-align: center;
  
}
.content h1{
    font-size: 45px;
    color: white;

}
.content p{
    padding: 0px 100px;
    font-size: 20px;
}
button{
    background: none;
    border: 1px solid white;
    color: rgb(237, 221, 221);
    font-size: 18px;
    padding: 10px 25px;
    border-radius: 6px;
}
button:hover{
    background: black;
    color: white;
}
.overlay{
    background: rgba(0,0,0,0.7);
    height: 100vh;
}
.overlay p{
    font-size: 18px;
    color: rgba(231, 222, 222, 0.895);
}
  </style>
<body>
    <div class="main">
        <div class="wrapper">
            <div class="header">
                <nav>
                    <div class="logo">
                        <a href="">SHOPSY</a>
                    </div>
                    <ul>
                        <li><a href="">FOOD</a></li>
                        <li><a href="">GROCERIES</a></li>
                        <li><a href="">MEDICINES</a></li>
                        <li><a href="">HELP</a></li>
                        <li><a href="">CONTACT</a></li>
                    </ul>
                </nav>
                <div class="overlay">
                <div class="content">
                    <h1>WELCOME TO<br> SHOPSY</h1>
                    <p><br>SHOP TILL YOU DROP<br>Get 20% off on your first order.</p>
                    <button>ORDER NOW</button>
                </div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
