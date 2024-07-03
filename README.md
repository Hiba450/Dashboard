Index file

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.15.4/css/all.css" integrity="sha384-DyZ88mC6Up2uqS4h/KRgHuoeGwBcD4Ng9SiP4dIRy0EXTlnuz47vAwmeGwVChigm" crossorigin="anonymous"/>
    <link rel="stylesheet" href="assets/css/style.css">
</head>
<body>
    <!--SideMenu-->     
    <section id="menu">
<div class="logo">
    <img src="assets/imgs/geometry.png" style="width: 40px;">
    <h2 style="color: white;">Dashboard</h2>

</div>
<div class="items">
    <li><i class="fas fa-chart-pie"></i><a href="#">Dashboard</a></li>
    <li><i class="fab fa-uikit"></i><a href="#">UI Elements</a></li>
    <li><i class="fas fa-edit"></i><a href="#">Forms</a></li>
    <li><i class="fas fa-chart-pie"></i><a href="#">Dashboard</a></li>
    <li><i class="fab fa-uikit"></i><a href="#">UI Elements</a></li>
    <li><i class="fas fa-edit"></i><a href="#">Forms</a></li>
</div>

    </section>
<!--Interface-->
<section id="interface">
    <div class="navigation">
        <!--search-->
        <div class="n1">
            <div class="search">
                <i class="fa-solid fa-magnifying-glass"></i>
                <form >
                    <input type="text" placeholder="search">
                </form>
            </div>
        </div>
        <!--profile-->
        <div class="profile">
            <i class="far fa-belt"></i>
            <img src="assets/imgs/logo.png" >
        </div>
    </div>
<!--Title-->
<h3 class="i-name">Dashboard</h3>
</section>



    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
</body>
</html>




Style.css



*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
}
body{
    width: 100%;
    background: grey;
    position: relative;
    display: flex;
}

/* SideMenu */
#menu{
    background: rgb(213, 213, 231);
    width: 300px;
    height: 100%;
}

#menu.logo img{
    width: 40px;
    margin-right: 50px;
}

#menu.logo{
    display: flex;
    align-items: center;
    color: white;
    padding: 30px 0 0 30px;
}

#menu.items{
    margin-top: 40px;
}
#menu.items li{
list-style: none;
padding: 15px 0;
transition: 0.3s ease;
}

#menu.items li i{
    color: white;
    width: 30px;
    height: 20px;
    line-height: 30px;
    text-align: center;
    font-size: 14px;
    margin: 0 10px 0 25px;
}
#menu.items li a{
    text-decoration: none;
    color: #B1A296;
    font-weight: 300;
    transition: 0.3s ease;
}
#menu.items li:hover{
    background: #aeb3be;
    cursor: pointer;
}
#menu.items li:nth-child(1){
    border-left: 4px solid #fff;
}
#menu.items li:hover i,
#menu.items li:hover a{
    color: #f2f4f6;
}

/*Interface*/
#interface{
    width: calc(100% - 300px);
}
#interface.navigation{
    display: flex;
    align-items: center;
    justify-content: space-between;
    background: #fff;
    padding: 15pc 30px;
    border-bottom: 3px solid #5D5C61;
}
#interface .navigation .search{
display: flex;
justify-content: flex-start;
align-items: center;
padding: 10px 40px;
border: 1px solid white;
border-radius: 4px;
}
#interface.navigation.search.input{
border: none;
outline: none;
font-size: 14px;
}

#interface.navigation.search i{
margin-right: 12px;
}
#interface.navigation.profile{
    display: flex;
    justify-content: flex-start;
    align-items: center;
}
#interface.navigation.profile i{
    margin-right: 20px;
    font-size: 19px;
    font-weight: 400;
}
#interface.navigation.profile img{
    width: 40px;
    height: 40px;
    object-fit: cover;
    border-radius: 50%;
}
