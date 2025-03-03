
[Uploading contact me.html…]()<html>
    <head>
        <title>CONTACT ME</title>
    </head>
    <body>
        <h1>ini contact saya</h1>
    </body>
</html>
*,
html {
    margin: 0;
    padding: 0;
}

.container {
    height: 100vh;
}

body {
    background-color: rgb(249, 249, 206);
}

.container-navbar {
    background-color: rgb(246, 255, 125);
    width: 100%;
    height: 10vh;
}

.ul-navbar {
    height: 60px;
    display:  flex;
    justify-content: center;
    align-items: center;
}

.li-navbar {
    list-style-type: none;
    padding: 10px;
    margin: 5px;
    font-size: 30px;
}

.li-navbar:hover {
    background-color: bisque;
    transition: .5s ease-in-out;
    transition-delay: .3s;
    border-radius: 8px;
}

.a-navbar {
    color: black;
    text-decoration: none;
}

.container-content {
    background-color: black;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 80vh;
}

.img-content {
    width: 200px;
    height: 200px;
    border: 1px solid;
    padding: 10px;
    box-shadow: 5px 10px rgb(255, 255, 255);
  
}



.a-content {
    color: white;
    display: flex;
    flex-direction: column-reverse;
    justify-content: space-evenly;
    align-items: center;
    text-decoration: none;


}

.a-paragraf {
    color: white;
    display: flex;
    justify-content: center;
    align-items: center;
    list-style-type: none;
}
.container-footer {
    height: 10vh;
    background-color: rgb(241, 200, 138);
    display: flex;
    justify-content: center;
    align-items: center;
}

.h1-footer {
    font-size: 30px;
}
<html>
    <head>
        <title>SMA NEGERI 2 SLEMAN</title>
        <link rel="stylesheet" href="style.css" />
    </head>
    <body>
        <div class="container">
        <!-- NAVBAR -->
         <div class="container-navbar">
            <ul class="ul-navbar">
                <li class="li-navbar">
                    <a href="#" class="a-navbar">HOME</a>
                </li>
                <li class="li-navbar">
                    <a href="about.html" class="a-navbar">ABOUT ME</a>
                </li>
                <li class="li-navbar">
                    <a href="contact me.html" class="a-navbar">CONTACT ME</a>
                </li>
            </ul>
         </div>
        <!-- NAVBAR SELESAI -->

        <!-- CONTENT -->
         <div class="container-content">
            <a href="https://www.sman2sleman.sch.id/"
            class="a-content">
                <img src="logo-kecil.png" class="img-content"/>
                <p class="a-content">KLIK GAMBAR DIBAWAH INI!!</p>
            </a>
         </div>
        <!-- CONTEN END -->

        <!-- FOOTER -->
         <div class="container-footer">
            <h2 class="h1-footer">THANKYOU FOR VISITING MY WEBSITE </h2>
         </div>
        <!-- FOOTER -->
        </div>
    </body>
</html>
<html>
    <head>
        <title>ABOUT ME</title>
    </head>
    <body>
        <h1>HAI INI AKU</h1>
    </body>
</html>
