<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BStore</title>
    <link rel="stylesheet" href="styleb.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,200;1,300;1,400;1,700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="htpps://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
<link
      rel="stylesheet"
      href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css"
      integrity="sha384-wvfXpqpZZVQGK6TAh5PVlGOfQNHSoD2xbE+QkPxCAFlNEevoEH3Sl0sibVcOQVnN"
      crossorigin="anonymous"
    />
    <link
      href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@1,300&display=swap"
      rel="stylesheet"
    />
    <link
    href="https://fonts.googleapis.com/css2?family=Roboto+Condensed:wght@300&display=swap"
    rel="stylesheet"
  />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta2/css/all.min.css" integrity="sha512-YWzhKL2whUzgiheMoBFwW8CKV4qpHQAEuvilg9FAn5VJUDwKZZxkJNuGM4XkWuk94WCrrwslk8yWNGmY1EduTA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>
<div class="header">
<div class="container">
   <div class="navbar">
       <div class="logo">
           <img src="logoB.png" alt="logo img" width="125">
       </div>
       <nav>
          
           <ul id="MenuItems">
               <li> <a href="">Home</a> </li>
               <li> <a href="about.html">About</a> </li>
               <li> <a href="contact.html">Contact</a> </li>
               <li> <a href="account.html">Account</a> </li>
           </ul>
           <img src="shopping bag.png" width="30px" height="30px">
           <img src="menu.png" class="menu" onclick="menutoggle()">
       </nav>
   </div>
   <div class="row">
       <div class="col-2">
           <h1>Give Your Wardrobe <br> A New Style!</h1>
           <p>It???s hard to be nice if you don???t feel comfortable. <br>Shop Your Style.</p>
               <a href="" class="btn">Explore Now &#8594 </a>
       </div>
       <div class="col-2">
           <img src="slider-2.png" alt="">
       </div>
   </div>
</div>
</div>
<div class="categories">
    <div class="small-container">
        <div class="row">
            <div class="col-3">
                <a href="products.html"><img src="cat-1.jpg" alt=""></a>
                <h6>Women's</h6>
            </div>
            <div class="col-3">
                <img src="cat-2.jpg" alt="">
                <h6>Men's</h6>
            </div>
            <div class="col-3">
                <img src="handbags.jpg" alt="" height="160px" width="320px">
                <h6>Accesories</h6>
            </div>
        </div>
    </div>
</div>
<div class="small-container">
    <h2 class="title">Featured Products</h2>
    <div class="row">
        <div class="col-4">
            <img src="p-9.png">
            <h4>Red-Black half&half T-shirt</h4>
            <div class="rating">
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star-o"></i>
            </div>
            <p>$50.0</p>
        </div>
        <div class="col-4">
            <img src="p-3.png">
            <h4>Grey-black checked pullover</h4>
            <div class="rating">
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star-o"></i>
            </div>
            <p>$50.0</p>
        </div>
        <div class="col-4">
            <img src="p-5.png">
            <h4>White-Peach half&half shirt</h4>
            <div class="rating">
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star-o"></i>
            </div>
            <p>$50.0</p>
        </div> <br>
        <div class="col-4">
            <img src="p-7.png">
            <h4>Navy Blue white pattern Polo neck T-shirt</h4>
            <div class="rating">
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star-o"></i>
            </div>
            <p>$50.0</p>
        </div>
    </div>
    <h2 class="title">Latest Products</h2>
    <div class="col-5">
        <img src="k1.jpg">
        <h4>Jackets</h4>
        <div class="rating">
            <i class="fa fa-star"></i>
            <i class="fa fa-star"></i>
            <i class="fa fa-star"></i>
            <i class="fa fa-star"></i>
            <i class="fa fa-star-o"></i>
        </div>
        <p>$150.0</p>
    </div>
    <div class="col-5">
        <img src="k2.jpg">
        <h4>Dresses</h4>
        <div class="rating">
            <i class="fa fa-star"></i>
            <i class="fa fa-star"></i>
            <i class="fa fa-star"></i>
            <i class="fa fa-star"></i>
            <i class="fa fa-star-o"></i>
        </div>
        <p>$150.0</p>
    </div>
    <div class="col-5">
        <img src="k5.jpg">
        <h4>Party Wear</h4>
        <div class="rating">
            <i class="fa fa-star"></i>
            <i class="fa fa-star"></i>
            <i class="fa fa-star"></i>
            <i class="fa fa-star"></i>
            <i class="fa fa-star-o"></i>
        </div>
        <p>$150.0</p>
    </div>
   <br><br><br><br><br><br><br><br>
</div>
<div class="offer">
    <div class="small-container">
        <div class="row">
            <div class="col-2">
                <img src="Xiaomi Mi watch.png" class="offer-img">
            </div>
            <div class="col-2">
            <p>Exclusively Available on Bstore.</p>
            <h1>Xiaomi Mi Watch Lite</h1>
            <small>The Xiaomi Mi Watch Lite is a good fitness tracker, but a very basic smartwatch. If you're after the Mi Band experience and would like the benefits of a larger display, Xiaomi's latest budget smartwatch is a fine option.</small>
            <a href="" class="btn">Buy Now &#8594; </a>
            </div>
        </div>
    </div>
</div>
    <div class="testimonial">
        <div class="small-container">
            <div class="row">
                <div class="col-3">
                    <i class="fa fa-quote-left"></i>
                    <p>"I am a regular BStore customer. Been to the parties, the store, warehouse and shopped online. I keep coming back because of how easy it is to set up my wardrobe. The website is easy to use and the flat postage rate makes it an affordable way to shop. They have great specials and of course I love their clothes and accessories!</p>
                
                 <div class="rating">
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star-o"></i>
                    <i class="fa fa-star-o"></i>
                 </div>
                <img src="pic-2.png">
                <h3>Sean Parker</h3>
                </div>
                <div class="col-3">
                    <i class="fa fa-quote-left"></i>
                    <p>I can always bank on finding a great new addition to my wardrobe.You are not going to get better service or a better price anywhere.</p>
                
                 <div class="rating">
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star-o"></i>
                    <i class="fa fa-star-o"></i>
                 </div>
                <img src="user-img.png">
                <h3>John Doe</h3>
                </div>
                <div class="col-3">
                    <i class="fa fa-quote-left"></i>
                    <p>This shirt is so soft and comfortable. I was a bit worried about the size running small, but I normally wear a medium and it fits great. It???s so comfortable and breathable, I can wear it to bed or to the gym, and it looks great day-to-day too.</p>
                
                 <div class="rating">
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star-o"></i>
                    <i class="fa fa-star-o"></i>
                 </div>
                <img src="pic-4.png">
                <h3>Mabel Joe</h3>
                </div>
            </div>
        </div>
    </div>
<div class="brands">
    <div class="small-container">
        <div class="row">
            <div class="col-6">
                <img src="instagramlogo.png">
            </div>
            <div class="col-6">
                <img src="fblogo.png">
            </div>
            <div class="col-6">
                <img src="twitterlogo.png">
            </div>
        </div>
    </div>
</div>
<div class="footer">
    <div class="small-container">
        <div class="row">
            <div class="footer-col-1">
                 <h3>Download our App</h3>
                 <p>Download our app for android and ios mobile phone.</p>
                 <div class="app-logo">
                     <img src="android.png">
                     <img src="ios.png">
                 </div>
            </div>
            
            <div class="footer-col-3">
                <h3>Useful links</h3>
                <ul>
                    <li>Coupons</li>
                    <li>Blog post</li>
                    <li>Return Policy</li>
                    <li>Join Affiliate</li>
                </ul>
           </div>
           <div class="footer-col-4">
            <h3>Follow Us</h3>
            <ul>
                <li>Facebook</li>
                <li>Instagram</li>
                <li>Twitter</li>
                <li>Youtube</li>
            </ul>
       </div>
        </div>
        <hr>
    </div>
</div>

<script>
    var MenuItems = document.getElementById("MenuItems");
    MenuItems.style.maxHeight= "0px";

    function menutoggle(){
        if(MenuItems.style.maxHeight=="0px")
        {
            MenuItems.style.maxHeight = "200px";
        }
        else{
            MenuItems.style.maxHeight = "100px";
        }
    }
</script>
</body>
</html>
