# Sample-Page
Sample Page of webpage
HTML
<html>
<head>
    <link rel="icon" href="/asserts/DLogo.jpg" type="image/x-icon">
    <title>web by Dstudio</title>
    <link rel="stylesheet" href="page.css">
</head>
<body>
    <center>
    <div class="box">
        <div class="st">
            <img src="/asserts/istockphoto-864313346-612x612.jpg" alt="">
            <p>/ apply@startcard.au</p>
        </div>
        <div class="button">
            <label for="product">Product</label>
            <label for="resources">Resources</label>
            <label for="blogs">Blogs</label>
            <label for="Pricing">Pricing</label>
        </div>
        <div class="en">
            <label for="en">En</label>
        </div>
        <div class="earth">
            <img src="/asserts/earthlogo.jpg" alt="">
        </div>
        <div class="login">
            <label for="LOGIN">Login</label>
            <button type="button">Get Started-It's Free</button>
        </div>
        <div class="wstar">
            <img src="/asserts/white-star.png" alt="">
        </div>
        <div class="astar">
            <b>5.0</b>
            <p>Rated on Trustpilot</p>
        </div>
        <div class="credit">
            <h1>Credit</h1>
            <h2>~</h2>
        </div>
        <div class="pic">
            <img src="/asserts/web2.png" alt="">
        </div>
        <div class="bcard">
            <b>Buisness Card</b>
            <p>Spent limits, merchant restrictions</p>
            <p2>easier way.</p2>
        </div>
        <div class="ccard">
            <b>Corporate Card</b>
            <p>Most powerful corporate credit</p>
            <p2>card experience.</p2>
        </div>
        <div class="Logos">
            <label for="rakuten">Rakuten</label>
            <label for="ncr">NCR</label>
            <label for=".monday.com">//.monday.com</label>
            <label for="disnep">Disnep</label>
            <label for="dropbox">Dropbex</label>
        </div>
        <div class="hlast">
        <div class="last">
            <label for="controlyourspends">Control Your Spends</label>
            <label for="∗">∗</label>
            <label for="cashback">2.5% Cashback</label>
            <label for="↗">↗</label>
            <label for="getsupport">Get 24/7 Support</label>
            <label for="∗">∗</label>
            <label for="compliantwithease">Compliant With Ease</label>
            <label for="↗">↗</label>
            <label for="applynow">Apply Now</label>
        </div>
        </div>
    </div>
    </center>
</body>
</html>









CSS
body{
    background-color: black;
    margin: 0;
    padding: 0;
    font-family: "Mona Sans", "Helvetica Neue", Helvetica, Arial, sans-serif;
}
.box{
    margin-top: 20px;
    background-color: rgba(255, 255, 255, 0.918);
    width: 811px;
    height: 608px;
}

.st{
    width: 100%;
    height: 50px;
    align-items: center;
}
.st img{
    display: block;
    height: 30px;
    width: 30px;
    padding-top: 10px;
    padding-right: 740px;
}
.st p{
    margin-top: -23px;
    padding-right: 550px;
    font-size: 15px;
}
.button{
    display: flex;
    justify-content: center;
    align-items: center;
    margin-right: 30px;
    gap: 18px;
    font-size: 12;
    font-weight: lighter;
    padding: 8px 0px 8px 0px;
    margin-top: -40px;
}
.button label:hover{
    color: rgb(255, 36, 36);
}
.en{
    padding-left: 300px;
    margin-top: -23px;
    font-size: 14px;
}
.earth img{
    width: 18px;
    padding-left: 340;
    margin-top: -16px;
}
.login{
    margin-top: -27px;
    padding-left: 130px;
}
.login label{
    padding-left: 470px;
    font-size: 13;
}
.login button{
    height:35px;
    border-radius: 9px;
    margin-left: 20px;
    color: white;
    background-color: black;
}
.login button:hover{
    color: rgb(230, 9, 9);
}
.wstar{
    margin-right: 600px;
    margin-top: 70px;
    width: 40px;
    height: 40px;
    background-color: black;
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 15px;
}
.wstar img{
    
    width: 20px;
    height: 20px;
}
.astar p{
    margin-top: 3;
    font-size: 12px;
    display: flex;
    margin-left: 135px;
}
.astar b{
    font-size: 20;
    font-weight: lighter;
    display: flex;
    margin-left: 135px;
    margin-top: -41;
}
.credit h1{
    font-size: 75px;
    font-family: "Mona Sans", "Helvetica Neue", Helvetica, "Bell MT";
    font-weight: lighter;
    padding-right: 450px;
}
.credit h2{
    padding-right: 150px;
    font-size: 63px;
    font-weight: lighter;
    margin-top: -118px;
}
.pic img{
    height: 320px;
    width: 300px;
    padding-left: 400px;
    margin-top: -225px;
}
.bcard p{
    margin-top: 8;
    font-size: 11px;
    display: flex;
    margin-left: 90px;
}
.bcard p2{
    margin-top: -8;
    font-size: 11px;
    display: flex;
    margin-left: 92px;
}
.bcard b{
    font-size: 16;
    display: flex;
    margin-left: 90px;
    margin-top: -107;
}
.ccard b{
    font-size: 16;
    display: flex;
    margin-left: 290px;
    margin-top: -53;
}
.ccard p{
    font-size: 11px;
    padding-right: 80px;
    margin-top: 8px;
}
.ccard p2{
    margin-top: -8px;
    font-size: 11px;
    display: flex;
    padding-left: 293px;
}
.logos{
    display: flex;
    justify-content: center;
    font-size: 18px;
    font-weight: bolder;
    font-family: Arial, Helvetica, sans-serif;
    gap: 100px;
    padding-top: 20px;
    margin-top: 100px;
}
.hlast{
    background-color: rgb(76, 100, 233);
    height: 55px;

}
.last{
    display: flex;
    justify-content: center;
    font-size: 16px;
    font-weight: bolder;
    font-family: Arial, Helvetica, sans-serif;
    gap: 15px;
    margin-top: 30px;
    padding-top: 17px;
}
.last:hover{
    color: white;
}
