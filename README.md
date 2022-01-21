#html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personality Test</title>
    <link rel="stylesheet" type="text/css" href="personality.css">
    <link href="https://use.fontawesome.com/releases/v5.6.3/css/all.css" rel="stylesheet" integrity="sha384-UHRtZLI+pbxtHCWp1t77Bi1L4ZtiqrqD80Kn4Z8NTSRyMA2Fd33n5dQ8lWUE00s/" crossorigin="anonymous">
</head>
<body>
    <div class="contain">
        <div class="menu">
            <div class="left-menu">
                <a href="personality.html">
                    <img class="person" src="https://static.neris-assets.com/images/system/logo.svg">
                </a>
            </div>    
            <div class="right-menu">
                <ul>
                    <li>PERSONALITY TYPES</li>
                    <li>PREMIUM PROFILES</li>
                    <li>TOOL KITS</li>  
                    <li>TEAM</li>

                </ul>
            </div> 
        </div>
        <div class="text">
            <h1>FREE PERSONALITY TEST</h1>
            <h4>NERIS Type Explorer®</h4>
            <button id="button1">Copy Link</button>
            <button id="button2">Share on</button>
            <div>
                <ul class="horizontal-list text-centre  social-icons">
                    <li>
                        <a href="#">

                            <i class="fab fa-instagram"></i>  
                        </a> 
                    <li>
    
                        <a href="#">
                            <i class="fab fa-facebook"></i>
                        </a> 
                
                    <li>
                         <a href="#">
                            <i class="fab fa-facebook-messenger"></i>
    
    
                             </a> 
                    <li>
                        <a href="#">
                            <i class="fab fa-twitter"></i>  
                         </a> 
                    <li>
                        <a href="#">
                            <i class="fab fa-whatsapp"></i>
                        </a>
                    </li>     
                 </ul>
                </div>
                <section id="personality">
                    <div id="type">

                        <h1 id="heading">
                        WHAT's YOUR PERSONALITY TYPE
                        </h1>
                        
                        <img class="img" src="https://blog.adioma.com/wp-content/uploads/2019/05/16-personality-types-infographic.jpg">
                    </div>
                </section>       
    
            
            <main>
                <section id="premium">

                </section>
            </main>
        
           
        </div>
    </div>
   
</body>
</html>


#css
*{
    margin: 0px;
    padding: 0px;
}
.contain{
    background-image: url("https://ik.imagekit.io/ikmedia/backlit.jpg");
    background-size: 100% 110%;
    width: 100%;
    height: 100vh;
}
.menu{
    width: 100%;
    height: 100px;
    background-color: lightgrey;
}
.left-menu{
    width: 20%;
    line-height: 80px;
    float: left;
}
.left-menu a{
    padding-left: 70px;

}    
.person{
        height: 200px;
        width: 200px;
        margin-top: -50px;
}
.right-menu{
    width: 75%;
    height: 100px;
    float: right;
}
.right-menu ul{
    margin-left: 200px;
}
.right-menu ul li{
    display: inline-block;
    list-style: none;
    font-size: 15px;
    color: darkmagenta;
    font-weight: bold;
    line-height: 100px;
    margin-left: 40px;
    text-transform: uppercase;
}    
.right-menu ul li:hover{
    color: orange;
}
.text{
    width: 100%;
    margin-top: 185px;
    text-transform: uppercase;
    text-align: center;
    color: white;
}
.text h1{
    font-size: 45px;
    font-weight:bold;
    margin: 20px 0px;
    word-spacing: 15px;
}
.text h4{
    font-size: 20px;
    word-spacing: 15px;
}
#button1{
    background-color: white;
    border: none;
    font-size: 15px;
    font-weight: bold;
    text-transform: uppercase;
    line-height: 40px;
    width: 150px;
    margin-top: 25px;
    border: 3px solid white;
}
#button2{
    background-color: transparent;
    border: none;
    text-transform: uppercase;
    font-weight: bold;
    line-height: 40px;
    border: 3px solid white;
    width: 150px;
}
.horizontal-list{
    list-style: none;
    padding-left: 0px;
    margin: 0px;
}
.horizontal-list li{
    display: inline-block;
    margin: 0px 20px 20px 0px;
}
.horizontal-list li a{
    color: white;
    text-decoration: none;
}
.social-icons li a i{
    padding: 10px;
    font-size: 1.4rem;
    border-radius: 50%;
    transition: 1s;
    margin-top: 30px;
}       
.social-icons li a i:hover{
    box-shadow: 0px 0px 6px 4px yellowgreen; 
}       
section{
    width: 100%;
    height: 170vh;
    display: flex;
    flex-direction: column;
    align-items: center;
}
section:nth-child(2n){
    background-color: white;
}
section:nth-child(2n+1){
    background-color: lightgrey;
}
#heading{
    width: auto;
    padding: 20px 10px 10px;
    margin: 10px auto;
    font-weight: 600;
    word-spacing: 15px;
    color: black;
}

.img{
    width: 100%;
    height: 150vh;
    display: flex;
    flex-direction: column;
    align-items: center;
}
#personality{
    background-color: white;
}
