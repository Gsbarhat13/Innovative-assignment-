*{
    margin: 0%;
    padding: 0%;
}
body{
    background-image: url("https://www.freecodecamp.org/news/content/images/2022/09/jonatan-pie-3l3RwQdHRHg-unsplash.jpg");
    background-repeat:no-repeat;
    background-size: cover;
}
h2{
    text-align: center;
    color: #fff;
}
.logo{
    width: 500px;
    height: 500px;
    margin: auto;
    position: relative;
}
.instagram{
    width: 50%;
    height: 50%;
    position: absolute;
    background: radial-gradient(circle at 25% 109%,
    #f2e665 0%,
    #f2e665 15%, 
    #f04b4a 45%,
    #d52bb1 60%,
    #5748db 87%);
border-radius: 20%;                                                                                                                                                                                                                                                                                                                                                                                                                                     
left:25%;
top: 25%;
}
.outline{
    width: 60%;
    height: 60%;
    position: absolute;
    top:13%;
    left:13.5%;
    border-radius: 20%;
    border: 18px solid #fff;
}
.inside{
    width: 40%;
    height: 40%;
    border-radius: 50%;
    position: absolute;
    left:18%;
    top:20%;
    border: 18px solid #fff;
}
.circle{
    background-color: #fff;
    width: 7%;
    height: 7%;
    border-radius: 50%;
    position: absolute;
    left: 76%;
    top:7%;
    border: 5px solid #fff;
}

<!DOCTYPE html>

<head>
    <title>INSTAGRAM LOGO</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <br>
    <br>
    <h2>INSTAGRAM LOGO</h2><br><br>
    <hr>
    <br><br>
    <div class="logo">
        <div class="instagram">>
            <div class="outline">
                <div class="inside"></div>
                <div class="circle"></div>
            </div>
        </div>
    </div>
    <hr>
</body>

</html>
