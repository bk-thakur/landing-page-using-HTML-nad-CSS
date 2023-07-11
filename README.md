# landing-page-using-HTML-nad-CSS
landing page project using HTMLM and CSS  ,palteform :- VS Code editor 22.0 version. task given by #octanet

HTML CODE

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>navigation</title>
</head>
<body style="background-image: pexels-alexander-grey-1209843;" >
    <header>
        <nav class="navbar">
        <ul>
            <li><a href="">Home</a></li>
            <li><a href="">About</a></li>
            <li><a href="">Services</a></li>
            <li><a href="">Contact us</a></li>
            <div class="search">
                <input type="text" name="search" id="search" placeholder="search about this websitr">
               
            </div>
        </ul>
    </nav>
    </header>

    
</body>

</html>

CSS CODE

.navbar{
    background-color: black;
    border-radius: 36px;

}
 .navbar ul{
     overflow: auto;
 }
 .navbar li a{
     padding: 3px 3px;
     text-decoration: none;
     color: white;
 }
 .navbar li{
     float:left;
      list-style: none;
      margin: 13px 36px;
      
 }
 .navbar li a:hover{
     color: red;
 }
 .search{
     float: right;
     margin: center;
     margin: 12px 40px;
     color: black;
 }
 .Register a:hover{
    color: red;
    text-decoration: none;

 }
 .Register a{
    float: right;
    margin: center;
    margin: 12px 50px;
    border-radius: 36px; 
    color: white;
    text-decoration: none;
    
    
}
 .navbar input{
     border: 2px solid black;
     border-radius: 14px;
     padding: 2px 30px;
     
 }
 .form button{
    width: 60px;
 }
 .h-text{
    max-width: 650px;
    position: absolute;
    top: 50%;
    left: 35%;
    transform: translate(-50%,-50);
    text-align: center;
    color:black;
 }
 .h-text span{
    letter-spacing: 3px;
 }
 .h-text{
    font-size: 1.5em;
 }
.h-text a{
    text-decoration: none;
    background:indianred;
    padding: 10px 20px;
    letter-spacing: 2px;
}
.h-text a:hover{
    color: red;
    text-decoration: none;
}
footer {
    background-color: #333;
    color: #fff;
    padding: 20px;
    text-align: center;
  }
