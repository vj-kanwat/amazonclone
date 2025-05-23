# amazonclone
I build a amazon clone by HTML and CSS and it is my first project in web-development field.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amazon.com</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css" integrity="sha512-Evv84Mr4kqVGRNSgIGL/F/aIDqQb7xQ2vcrdIwxfjThSH8CSR7PBEakCr51Ck+w+/U6swU2Im1vVX0SVk9ABhg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
    <div class="navbar">
                      <div class="nav-logo border">
                        <div class="logo"></div>
                      </div>
                      <div class="div-address border">
                        <p class="add-frist">Deliver to</p>
                        <div class="add-icon">
                            <i class="fa-solid fa-location-dot"></i>
                            <p class="add-sec">India</p>
                        </div>
                      </div>
                      <div class="nav-search">
                        <select class="search-select colors">
                            <option><p>All</p></option>
                            <option> himanshu</option>
                             </select>
                            <input placeholder="Search Amazon" class="search-input">
                            <div class="search-icon">
                            <i class="fa-solid fa-magnifying-glass"></i>
                            </div>
                      </div>
                     
                      <div class="nav-lang">
                        <div class="nav-sec border">
                         <div class="lang-logo "></div>
                         <div class="lang-frist"><P><B>EN</B></P></div></div>
                        <select class="lang">
                          <option></option>
                        </select>

                      </div>
                      <div class="signin border">
                        <p><span>Hello, sign in</span></p>
                        <p class="nav-frist">Account & Lists</p>
                      </div>
                      <div class="returns border">
                        <p><span>Returns</span></p>
                        <p class="nav-frist">& Orders</p>
                      </div>
                      <div class="nav-cart border">
                        <i class="fa-solid fa-cart-shopping"></i>
                        Cart
                      </div>
    </div>
    <div class="pannel">
              <div class="pannel-menu border">
                <i class="fa-solid fa-bars"></i>
                All
              </div>
              <div class="pannel-ops">
                <p>Today's Deals</p>
                <p>Registry</p>
                <p>Prime Video</p>
                <P>Gift Cards</P>
                <p>Customer Service</p>
                <P>Sell</P>
              </div>
              <div class="pannel-deals border">
                Soap deals in Electronics
              </div>
    </div>
    </header>
    <div class="hero-section">
      <div class="hero-message">
        <P>You are on amazon.com. You can also shop on Amazon India for millions of products with fast local delivery. <a class="hero-link" href="https://www.amazon.in" target="_main"> Click here to go to amazon.in</a></P>
      </div>
    </div>
    <div class="content">
      <div class="box1 box ">
          <h2>Get your game on</h2>
          <div class="box1-content">
        <div class="box1-image"></div>
        <a class="box1-link" href="#">Shop gaming</a></div>
      </div>
      <div class="box2 box">
          <h2>Gifts for Dad under $25</h2>
          <div class="box2-content">
        <div class="box2-image"></div>
        <a class="box2-link" href="#">See all deals</a>
      </div>
      </div>
      <div class="box3 box">
        <h2>Toy's under $25</h2>
          <div class="box3-content">
        <div class="box3-image"></div>
        <a class="box3-link" href="#">Shop now</a></div>
      </div>
      <div class="box4 box">
        <h2>Shop deals in Fashion</h2>
        <div class="box4-images">
          <div class="bargin"><div class="box4-image1"></div><div class="image-text">Jeans under $50</div></div>
          <div class="bargin"><div class="box4-image2"></div><div class="image-text">Tops under $25</div></div>
          <div class="bargin"><div class="box4-image3"></div><div class="image-text">Dresses under $30</div></div>
          <div class="bargin"><div class="box4-image4"></div><div class="image-text">Shoes under $50</div></div>
        </div>
        <div ><a class="box4-link" href="#">See all deals</a></div>
      </div>
      <div class="box5 box">
        <h2>New home arrivals under $50</h2>
        <div class="box5-images">
          <div class="bargin"><div class="box5-image1"></div><div class="image-text">Kitchen & Dining</div></div>
          <div class="bargin"><div class="box5-image2"></div><div class="image-text">Home Improvememt</div></div>
          <div class="bargin"><div class="box5-image3"></div><div class="image-text">Decor</div></div>
          <div class="bargin"><div class="box5-image4"></div><div class="image-text">Bedding & Bath</div></div>
        </div>
        <div ><a class="box5-link" href="#">Shop the letest from Home</a></div>
      </div>
      <div class="box6 box">
        <h2>Refresh your space</h2>
        <div class="box6-images">
          <div class="bargin"><div class="box6-image1"></div><div class="image-text">Dining</div></div>
          <div class="bargin"><div class="box6-image2"></div><div class="image-text">Home</div></div>
          <div class="bargin"><div class="box6-image3"></div><div class="image-text">Kitchen</div></div>
          <div class="bargin"><div class="box6-image4"></div><div class="image-text">Health & Beauty</div></div>
        </div>
        <div ><a class="box6-link" href="#">See more</a></div>
      </div>
      <div class="box7 box">
         <h2>Gaming accessories</h2>
        <div class="box7-images">
          <div class="bargin"><div class="box7-image1"></div><div class="image-text">Headsets</div></div>
          <div class="bargin"><div class="box7-image2"></div><div class="image-text">Keyboards</div></div>
          <div class="bargin"><div class="box7-image3"></div><div class="image-text">Computer mice</div></div>
          <div class="bargin"><div class="box7-image4"></div><div class="image-text">Chairs</div></div>
        </div>
        <div ><a class="box7-link" href="#">See more</a></div>
      </div>
      <div class="box8 box">
        <h2>Most-loved watches</h2>
        <div class="box8-images">
          <div class="bargin"><div class="box8-image1"></div><div class="image-text">Women</div></div>
          <div class="bargin"><div class="box8-image2"></div><div class="image-text">Men</div></div>
          <div class="bargin"><div class="box8-image3"></div><div class="image-text">Girls</div></div>
          <div class="bargin"><div class="box8-image4"></div><div class="image-text">Boys</div></div>
        </div>
        <div ><a class="box8-link" href="#">Discover more</a></div>
      </div>
      <br>
    </div>
    <footer>
      <div class="foot-pennel1">
        Back to Top
      </div>
      <div class="foot-pennel2">
        <ul>
          <p><b>Get to Know Us</b></p>
<a>Careers</a>
<a>Blog</a>
<a>About Amazon</a>
<a>Investor Relations</a>
<a>Amazon Devices</a>
<a>Amazon Science</a>
</ul>
 <ul>
          <p>Get to Know Us</p>
<a>Careers</a>
<a>Blog</a>
<a>About Amazon</a>
<a>Investor Relations</a>
<a>Amazon Devices</a>
<a>Amazon Science</a>
</ul>
 <ul>
          <p>Get to Know Us</p>
<a>Careers</a>
<a>Blog</a>
<a>About Amazon</a>
<a>Investor Relations</a>
<a>Amazon Devices</a>
<a>Amazon Science</a>
</ul>
 <ul>
          <p>Get to Know Us</p>
<a>Careers</a>
<a>Blog</a>
<a>About Amazon</a>
<a>Investor Relations</a>
<a>Amazon Devices</a>
<a>Amazon Science</a>
</ul>
      </div>
      <div class="foot-pennel3">
        <div class="logo1"></div>
      </div>
      <div class="foot-pennel4">
        <div class="foottext1">
          <a href="#">Condition of Use</a>
          <a href="#">Privacy Notice</a>
          <a href="#">Consumer Health Data Privacy Disclosure</a>
          <a href="#">Your Ads Privacy Choice</a>
        </div>
        <div class="foottext2">
          <p>© 1996-2025, Amazon.com, Inc. or its affiliates</p>
        </div>
      </div>
      
    </footer>
</body>
</html>
 css =>
 *{
   margin: 0px;
   padding: 0px;
    border: border-box;
}
.navbar{
    height: 60px;
    background-color: #0f1111;
    font-family: Arial, Helvetica, sans-serif;
    color: white;
    display: flex;
    align-items: center;
    justify-content: space-evenly;
}
.nav-logo{
    height: 50px;
    width: 100px;
    padding-left: 6px;
    padding-right: 6px;
}
.logo{
    background-image: url("https://logos-world.net/wp-content/uploads/2020/04/Amazon-Emblem.jpg");
    background-size: cover;
    height: 50px;
    width: 100%;
}
.border{
    border: 1.5px solid transparent;
}
.border:hover{
    border: 1.5px solid white;
}
.add-frist{
    color: #cccccc;
    font-size: 0.85rem;
}
.add-sec{
    color: white;
    font-size: 1rem;
}
.add-icon{
    display: flex;
    color: #cccccc;
}
.div-address{
    padding-left: 16px;
    padding-top: 10px;
}

.nav-search{
    display: flex;
    color: white;
    width: 900px;
    height: 40px;
    border-radius: 5px;
     ;
    
}
.search-input{
    font-size: 1rem;
    border: none;
    flex-grow: 1;
}
.search-icon{
    width: 45px;
    display: flex;
    align-items: center;
    justify-content: center;
    background-color: #febd68;
    border-top-right-radius: 5px ;
    border-bottom-right-radius: 5px ;
    color: #0f1111;
    font-size: 20px;
}
.search-select{
    border-top-left-radius: 5px ;
    border-bottom-left-radius: 5px ;
    background-color: #f3f3f3;
    width: 50px;
    text-align: center;
    border: none;
    color: rgb(95, 92, 92)
}
.colors:hover{
    color: black;
}
.botton{
        width: 45px;
        height: 40px;
        background-color:#febd68 ;
        border: none;
        border-top-right-radius: 5px ;
    border-bottom-right-radius: 5px ;
    background-image: url("https://www.pinclipart.com/picdir/big/356-3566063_search-icon-vector-png-clipart.png");
    border: border-box;
    background-size: contain;
    
}
.color-button:hover{
    background-color: #c0883e;
}
.lang{
    background-color: #0f1111;
    color: #cccccc;
    border:none;
    
}
.nav-lang{
    display: flex;
}
.lang-logo{
    background-image: url("https://www.pixelstalk.net/wp-content/uploads/2016/05/American-Flag-iphone-Background-Images.jpg");
    background-size: cover;
    height: 16.2px;
    width: 21px;
    margin-right: 4px;
}
.lang-option{
    font-weight: 100;
}
.nav-sec{
    display: flex;
}
.nav-frist{
    font-weight: 700;
    line-height: 15px;
     font-size: 0.85rem;
}
span{
    font-size: 0.7rem;
}
.nav-search:hover{
    border: 2px solid orange;
}
.nav-cart i{
    font-size: 30px;
}
.nav-cart{
    font-size: 0.85rem;
    font-weight: 700;
}
.pannel{
     height: 39px;
    display: flex;
    background-color: #222f3d;
    color: white;
    align-items: center;
    justify-content: space-evenly;
}
.pannel-ops p{
       display: inline;
       font-weight: 700;
       margin: 10px;
}
.pannel-ops p:hover{
    border: 1.5px solid white;
}
.pannel-ops{
    width: 1250px;
    font-size: 0.85rem;
}
.pannel-deals{
    font-size: 0.9rem;
    font-weight: 700;
}
.hero-section{
    display: flex;
    align-items: flex-end;
    justify-content: center;
    background-image: url("https://m.media-amazon.com/images/I/71h15GsHkvL._SX3000_.jpg");
    background-size: cover;
    height: 600px;
    width: 99%;
    margin-left: 7px;
    
}
.hero-message{
    display: flex;
    height: 40px;
    background-color: #f5f6f6;
    color: #0f1111;
    align-items: center;
    justify-content: center;
    width: 97%;
    margin-bottom: 310px;
}
.hero-link{
    text-decoration: none;
    color: #2162a1;
}
.hero-link:hover{
    text-decoration: underline;
}
.content{
    position: relative;
    bottom: 300px;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
    height: 950px;
    align-items: center;
    background-color: #e2e7e6;
}
.box{
     height: 420px; 
    width: 22.4%;
    background-color: white;
     padding: 20px 0px 15px;
}

.box1-image{
    height: 320px;
    background-image: url("https://images-na.ssl-images-amazon.com/images/G/01/AmazonExports/Events/2024/Stores-Gaming/FinalGraphics/Fuji_Gaming_store_Dashboard_card_1x_EN._SY304_CB564799420_.jpg");
    background-size: cover;
}
.box1-content{
    margin:14px 10px 10px 10px;
}
h2{
    margin-left: 15px;
}
.box1-link{
    text-decoration: none;
    display: inline-block;
    margin-top: 30px;
}
.box2-image{
    height: 320px;
    background-image: url("https://images-na.ssl-images-amazon.com/images/G/01/AmazonExports/Events/2025/AIS_FathersDay_25/Fuji_SingleImageCard_FathersDay25_1x._SY304_CB795634726_.jpg");
    background-size: cover;
}
.box2-content{
    margin:14px 10px 10px 10px;
}
h2{
    margin-left: 15px;
}
.box2-link{
    text-decoration: none;
    display: inline-block;
    margin-top: 30px;
}
.box3-image{
    height: 320px;
    background-image: url("https://images-na.ssl-images-amazon.com/images/G/01/AmazonExports/Events/2024/DskBTFQuadCards/Fuji_BTF_Quad_Cards_1x_Action_figure._SY116_CB558654384_.jpg");
    background-size: cover;
}
.box3-content{
    margin:14px 10px 10px 10px;
}
h2{
    margin-left: 15px;
}
.box3-link{
    text-decoration: none;
    display: inline-block;
    margin-top: 30px;
}
.box4-images{
    height: 320px;
    width: 310px;
    /* border: 2px solid black; */
    margin: 10px;
    display: flex;
    flex-wrap: wrap;
    align-items: flex-start;
    justify-content: space-between;
}
.bargin{
    height: 115px;
    width: 145px;
    /* border: 2px solid black; */
    /* margin: 20px; */
}
.image-text{
    position: relative;
    top: 3px;
    color: #0f1111;
    font-size: 13px;
    font-family: Arial, Helvetica, sans-serif;
}
.box4-image1{
    height: 115px;
    width: 145px;
    background-image: url("https://images-na.ssl-images-amazon.com/images/G/01/AMAZON_FASHION/2022/SITE_FLIPS/SPR_22/GW/DQC/DQC_APR_TBYB_W_BOTTOMS_1x._SY116_CB624172947_.jpg");
    background-size: cover;
}
.box4-image2{
    height: 115px;
    width: 145px;
    background-image: url("https://images-na.ssl-images-amazon.com/images/G/01/AMAZON_FASHION/2022/SITE_FLIPS/SPR_22/GW/DQC/DQC_APR_TBYB_W_TOPS_1x._SY116_CB623353881_.jpg");
    background-size: cover;
}
.box4-image3{
    height: 115px;
    width: 145px;
    background-image: url("https://images-na.ssl-images-amazon.com/images/G/01/AMAZON_FASHION/2022/SITE_FLIPS/SPR_22/GW/DQC/DQC_APR_TBYB_W_DRESSES_1x._SY116_CB623353881_.jpg");
    background-size: cover;
}
.box4-image4{
    height: 115px;
    width: 145px;
    background-image: url("https://images-na.ssl-images-amazon.com/images/G/01/AMAZON_FASHION/2022/SITE_FLIPS/SPR_22/GW/DQC/DQC_APR_TBYB_W_SHOES_1x._SY116_CB624172947_.jpg");
    background-size: cover;
}
.box4-link{
    text-decoration: none;
    display: inline-block;
    margin-top: 30px;
}
.box5-images{
    height: 320px;
    width: 310px;
    /* border: 2px solid black; */
    margin: 10px;
    display: flex;
    flex-wrap: wrap;
    align-items: flex-start;
    justify-content: space-between;
}
.bargin{
    height: 115px;
    width: 145px;
    /* border: 2px solid black; */
    /* margin: 20px; */
}
.image-text{
    position: relative;
    top: 3px;
    color: #0f1111;
    font-size: 13px;
    font-family: Arial, Helvetica, sans-serif;
}
.box5-image1{
    height: 115px;
    width: 145px;
    background-image: url("https://images-na.ssl-images-amazon.com/images/G/01/DiscoTec/2024/HomeLifestyle/HomeSummerFlip/Homepage/QuadCards/Home_Flip_Summer_2024_315_HP_NewArrivals_QuadCard_D_01_1x._SY116_CB555960040_.jpg");
    background-size: cover;
}
.box5-image2{
    height: 115px;
    width: 145px;
    background-image: url("https://images-na.ssl-images-amazon.com/images/G/01/DiscoTec/2024/HomeLifestyle/HomeSummerFlip/Homepage/QuadCards/Home_Flip_Summer_2024_316_HP_NewArrivals_QuadCard_D_02_1x._SY116_CB555960040_.jpg");
    background-size: cover;
}
.box5-image3{
    height: 115px;
    width: 145px;
    background-image: url("https://images-na.ssl-images-amazon.com/images/G/01/DiscoTec/2024/HomeLifestyle/HomeSummerFlip/Homepage/QuadCards/Home_Flip_Summer_2024_317_HP_NewArrivals_QuadCard_D_03_1x._SY116_CB555960040_.jpg");
    background-size: cover;
}
.box5-image4{
    height: 115px;
    width: 145px;
    background-image: url("https://images-na.ssl-images-amazon.com/images/G/01/DiscoTec/2024/HomeLifestyle/HomeSummerFlip/Homepage/QuadCards/Home_Flip_Summer_2024_318_HP_NewArrivals_QuadCard_D_04_1x._SY116_CB555960040_.jpg");
    background-size: cover;
}
.box5-link{
    text-decoration: none;
    display: inline-block;
    margin-top: 30px;
}
.box6-images{
    height: 320px;
    width: 310px;
    /* border: 2px solid black; */
    margin: 10px;
    display: flex;
    flex-wrap: wrap;
    align-items: flex-start;
    justify-content: space-between;
}
.bargin{
    height: 115px;
    width: 145px;
    /* border: 2px solid black; */
    /* margin: 20px; */
}
.image-text{
    position: relative;
    top: 3px;
    color: #0f1111;
    font-size: 13px;
    font-family: Arial, Helvetica, sans-serif;
}
.box6-image1{
    height: 115px;
    width: 145px;
    background-image: url("https://images-na.ssl-images-amazon.com/images/G/01/launchpad/2023/Gateway/January/DesktopQuadCat_186x116_LP-HP_B08MYX5Q2W_01.23._SY116_CB619238939_.jpg");
    background-size: cover;
}
.box6-image2{
    height: 115px;
    width: 145px;
    background-image: url("https://images-na.ssl-images-amazon.com/images/G/01/launchpad/2023/Gateway/January/DesktopQuadCat_186x116_home_B08RCCP3HV_01.23._SY116_CB619238939_.jpg");
    background-size: cover;
}
.box6-image3{
    height: 115px;
    width: 145px;
    background-image: url("https://images-na.ssl-images-amazon.com/images/G/01/launchpad/2023/Gateway/January/DesktopQuadCat_186x116_kitchen_B0126LMDFK_01.23._SY116_CB619238939_.jpg");
    background-size: cover;
}
.box6-image4{
    height: 115px;
    width: 145px;
    background-image: url("https://images-na.ssl-images-amazon.com/images/G/01/launchpad/2023/Gateway/January/DesktopQuadCat_186x116_health-beauty_B07662GN57_01.23._SY116_CB619238939_.jpg");
    background-size: cover;
}
.box6-link{
    text-decoration: none;
    display: inline-block;
    margin-top: 30px;
}
.box7-images{
    height: 320px;
    width: 310px;
    /* border: 2px solid black; */
    margin: 10px;
    display: flex;
    flex-wrap: wrap;
    align-items: flex-start;
    justify-content: space-between;
}
.bargin{
    height: 115px;
    width: 145px;
    /* border: 2px solid black; */
    /* margin: 20px; */
}
.image-text{
    position: relative;
    top: 3px;
    color: #0f1111;
    font-size: 13px;
    font-family: Arial, Helvetica, sans-serif;
}
.box7-image1{
    height: 115px;
    width: 145px;
    background-image: url("https://images-na.ssl-images-amazon.com/images/G/01/AmazonExports/Fuji/2021/June/Fuji_Quad_Headset_1x._SY116_CB667159060_.jpg");
    background-size: cover;
}
.box7-image2{
    height: 115px;
    width: 145px;
    background-image: url("https://images-na.ssl-images-amazon.com/images/G/01/AmazonExports/Fuji/2021/June/Fuji_Quad_Keyboard_1x._SY116_CB667159063_.jpg");
    background-size: cover;
}
.box7-image3{
    height: 115px;
    width: 145px;
    background-image: url("https://images-na.ssl-images-amazon.com/images/G/01/AmazonExports/Fuji/2021/June/Fuji_Quad_Mouse_1x._SY116_CB667159063_.jpg");
    background-size: cover;
}
.box7-image4{
    height: 115px;
    width: 145px;
    background-image: url("https://images-na.ssl-images-amazon.com/images/G/01/AmazonExports/Fuji/2021/June/Fuji_Quad_Chair_1x._SY116_CB667159060_.jpg");
    background-size: cover;
}
.box7-link{
    text-decoration: none;
    display: inline-block;
    margin-top: 30px;
}
.box8-images{
    height: 320px;
    width: 310px;
    /* border: 2px solid black; */
    margin: 10px;
    display: flex;
    flex-wrap: wrap;
    align-items: flex-start;
    justify-content: space-between;
}
.bargin{
    height: 115px;
    width: 145px;
    /* border: 2px solid black; */
    /* margin: 20px; */
}
.image-text{
    position: relative;
    top: 3px;
    color: #0f1111;
    font-size: 13px;
    font-family: Arial, Helvetica, sans-serif;
}
.box8-image1{
    height: 115px;
    width: 145px;
    background-image: url("https://images-na.ssl-images-amazon.com/images/G/01/AmazonExports/Events/2024/BAU2024Aug/WomenWatches_1x._SY116_CB564394432_.jpg");
    background-size: cover;
}
.box8-image2{
    height: 115px;
    width: 145px;
    background-image: url("https://images-na.ssl-images-amazon.com/images/G/01/AmazonExports/Events/2024/BAU2024Aug/MenWatches_1x._SY116_CB564394432_.jpg");
    background-size: cover;
}
.box8-image3{
    height: 115px;
    width: 145px;
    background-image: url("https://images-na.ssl-images-amazon.com/images/G/01/AmazonExports/Events/2024/BAU2024Aug/GirlWatches_1x._SY116_CB564394432_.jpg");
    background-size: cover;
}
.box8-image4{
    height: 115px;
    width: 145px;
    background-image: url("https://images-na.ssl-images-amazon.com/images/G/01/AmazonExports/Events/2024/BAU2024Aug/BoyWatches_1x._SY116_CB564394432_.jpg");
    background-size: cover;
}
.box8-link{
    text-decoration: none;
    display: inline-block;
    margin-top: 30px;
}
.footer{
    position: relative;
    
}

.foot-pennel1{
    background-color: #37475a;
    color: white;
    height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 0.85rem;
    font-family: Arial, Helvetica, sans-serif;
}
.foot-pennel2{
    background-color: #222f3d;
    color: white;
    height: 300px;
    display: flex;
    justify-content: space-evenly;
}
.foot-pennel2 a{
    display: block;
} 
Ul{
    margin-top: 30px;
}
ul a{
    font-family: Arial, Helvetica, sans-serif;
    font-size: 0.85rem;
    margin-top: 10px;
    color: #dddddd;
}
.foot-pennel3{
    background-color: #222f3d;
    color: white;
    border-top: 0.5px solid white;
    height: 60px;
    display: flex;
    justify-content: center;
    align-items: center;
}
.logo1{
    background-image: url("https://static.vecteezy.com/system/resources/previews/019/017/542/original/amazon-logo-free-png.png");
    background-size: cover;
    height: 70px;
    width: 100px;
    color: white;
    }
.foot-pennel4{
    background-color: #131a22;
    color: #dddddd;
    height: 76px;
    line-height: 20px;
    /* display: flex; */
    /* justify-content: center; */
    /* align-items: center; */
}
.foottext1 a{
    height: 30px;
    margin: 12px;
    font-size: 0.8rem;
    color: #dddddd;
    text-decoration: none ;
}
.foottext1 a:hover{
    text-decoration: underline;
}
.foottext2{
    text-align: center;
}
.foottext1{
    text-align: center;
    padding: 12px;
}
