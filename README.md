<!DOCTYPE html>
<html lang="en">
<head>
    <title>Document</title>
    <style>
        *{
            margin: 0px;
           padding: 0px;
           box-sizing:border-box;
        }
        .parent {
        background-color:rgb(199, 196, 196);
        background-size:150% 10000px;
        }
        .parent{
            width: 100%;
            height: 60px;
            background-color: rgb(249, 247, 247);
            text-align: center;
            justify-content: center;
            overflow: hidden;
        
        
        }
       .parent ul{
        display: inline-flex;
        list-style: none;
       }
       .parent ul li{
        padding: 8px;
       }
       a{
        text-decoration: none;
       }
       .hover:hover{
        color: red;
       }
       .list:hover{
        background-color: rgb(197, 195, 195);
        border-radius: 10px;
       }
       .img{
        background-color: aliceblue;
       }
       .parent1 ul{
        display: none;
       }
       .parent1 ul li{
        padding: 10px;
       }
       .parent ul li:hover .parent1{
        display: block;
       }
       .parent ul li:hover .parent1 ul{
        display: block;
        justify-content: center;
        text-align: center;
        background-color: white;
        position: absolute;
        margin-left: -20px;
        z-index: 10;
       }
       .list1:hover{
        background-color: rgb(192, 192, 198);
       }
       .l1:hover{
        background-color: gray;
        border-radius: 2px;
       }

        .image{
            background-image:url("https://images01.nicepagecdn.com/cd46d0ff82086185e4d7aa0f/983dd5d6893c550588ea7cff/coupon_28_sp23-1800-4df8.jpg");
            width: 100%;
            height: 170px;
        }
        .image3{
            width: 200px;
            height: 500px;
            position:absolute;
            padding: 0px;
            justify-content:right 10px;
        
        }
        .body1{
            width: 110%;
            height: 1000px;
            margin-right: 20px;
            
            
        }
        .image5{
            width: 100%;
            height: 1000px;
            position: absolute;
            padding:0px ;
            justify-content:end ;
        }
        .home{
            width: 100%;
            height: 70px;
            padding: 30px;
        }
       
        .heading-container{
            padding: 10px;
            position:relative;
            box-sizing:border-box ;
            display: flex;
            flex-direction:column ;
            align-items: center;
            justify-content: center;
             min-height: 350px;
            text-align: center;
             background-position: 50% 50%;
             border-radius: 10px;
             background-image: url(450.jpg);
        }
        .mainbody{
                border-radius: 100%;
                border-color: black 10px;
            }
        
      .body1{
            height: 150px;
             width: 250px;
             margin-left: 50px;
             border-radius: 10px;
             border: black 10px ; 
            
            
        }
        .body2{
            height: 150px;
             width: 250px;
             margin-top: -150px;
             margin-left: 350px;
             border:  black 10px;
             
             
        }
        .body3{
            height: 80px;
             width: 280px;
             margin-left: 650px;
             margin-top:-100px ;
             border: black 10px;
        }
        .body4{
            height: 150px;
             width: 200px;
             margin-left: 950px;
           margin-top: -100px;
           border: black 10px;
        }

      
       .container .heading-container{
        color: white;
       }
       .matter-container{
        margin-top: 206%;
        position:relative;
        box-sizing:border-box ;
        align-items: center;
        justify-content: center;
        text-align: justify;
        background-position: 50% 50%;
        border-radius: 10px;
        text-align: justify;
        background-color:whitesmoke;
       }
       .h1{
        text-align: center;
        justify-content: center;
        align-items: center;
       }
       .h5{
        text-align: justify;
       }
       
       
       #img{
        border-radius: 5px;
        cursor: pointer;
        transition: 0.3s;
        
       }
       #img:hover{
        opacity: 0.7;
        border-color: rgb(5, 5, 5);
        transform: skewY(-0deg) translatey(-40px);
       }
       .end{
            margin-left: -1100px;
            width: 1260px;
            height: 380px;
            position: relative;
            min-height: 2px;
            padding-left: 15px;
            padding-right: 15px;
            position: absolute;
            justify-content: center;
            text-align: center;
            background-color:rgb(28, 25, 25);
            color: white;
        }
        .end{
            display: inline-flex;
            text-align: center;
            text-decoration: white;
            margin-left: 0px;
            color:white;
        }
        .content:hover{
            position: relative;
            justify-content: center;
        
            text-decoration: red;
            text-align: center;
            color: white;
        }
        .content1:hover{
            position: relative;
    
            text-decoration: red;
            text-align: center;
            color: white;
        }
        .content2:hover{
            position: relative;
            
            text-decoration: red;
            text-align: center;
            color:white;
        }
        .content3:hover{
            position: relative;
            
            text-decoration: red;
            text-align: center;
            color:white;
        }
        .content4:hover{
            position: relative;
        
            text-transform: unset;
            text-decoration: red;
            text-align: center;
            color: white;
        }
        .last{
        background-color:rgb(53, 52, 52);
        width: 1260px;
        height: 120px;
        border-radius: 5px;
        margin-top: 29%;
       
        }
        .icon{
        display: inline-block;
        }
        #logo{
            margin-top: 10px;
            
            width: 30px;
            position: relative;
            height: 30px;
            border-radius: 30px;
        }
        .icon1{
        display: inline-block;
        }
        #logo1{
            margin-top: 10px;
            margin-left: 0px;
            width: 30px;
            position: relative;
            height: 30px;
            border-radius: 30px;
        }
        .icon2{
        display: inline-block;
        }
        #logo2{
            margin-top: 20px;
            margin-left: 0px;
            width: 30px;
            position: relative;
            height: 30px;
            border-radius: 30px;
        }
        .icon3{
        display: inline-block;
        }
        #logo3{
            margin-top: 20px;
            margin-left: 0px;
            width: 30px;
            position: relative;
            height: 30px;
            border-radius: 30px;
        }
        .text{
            position: relative;
            text-align: end;
            color: white;
        }
        .end{
            display: inline-flex;
        }
       
    </style>
</head>
<body>
    <div class="parent">
        <ul>
            <img src="https://csite.nicepage.com/Images/logo-w.png" alt="">
          &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
          &nbsp; &nbsp; &nbsp; &nbsp; 
           
          <ul>
            <li class="list">Download</li>
            <li class="list">400+ Feutures</li>
            <li class="list">10000+ Templates▾
                <div  class="parent1">
                    <ul>
                        <li class="l1">Website Templates</li>
                        <li class="l1">website Themes</li>
                        <li class="l1">Wordpress Thesmes</li>
                        <li class="l1">Joomula Templates</li>
                        <li class="l1">HTML Templates</li>
                    </ul>
                </div>
            </li>
            <li class="list">Website Builders▾
                <div  class="parent1">
                    <ul>
                    <li class="l1">HTML Website Builder</li>
                    <li class="l1">WordPress website Builder</li>
                    <li class="l1">Joomula Page Builder</li>
                </ul>
            </div>
            </li>
            <li class="list">Premium</li>
            <li class="list">Forms</li>
            <li class="list">Blog</li>
            <li class="list">Help▾
                <div  class="parent1">
                    <ul>
                    <li class="l1">Documentation</li>
                    <li class="l1">Contact Support</li>
                </ul>
            </div> 
            </li>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <li class="list">EN▾
                <div class="parent1">
                    <ul>
                        <li class="l1">EN</li>
                        <li class="l1">DE</li>
                        <li class="l1">NL</li>
                        <li class="l1">FR</li>
                        <li class="l1">IT</li>
                        <li class="l1">ES</li>
                        <li class="l1">PL</li>
                        <li class="l1">PT</li>
                        <li class="l1">TR</li>    
                        <li class="l1">RU</li>
                        <li class="l1">HU</li>
                        <li class="l1">CS</li>
                        <li class="l1">SV</li>
                    </ul>
            </div>
            </li>
            <li class="list">Sign in</li>
            <li class="list">Register</li>
        </ul>
    </div>
    
  <div class="image">
    <ul>
        <li class="image1">

        </li>
    </ul>
  </div>
  <div class="home">
    &nbsp &nbsp &nbsp <a href="#">Home</a>&nbsp&nbsp/&nbsp&nbsp<a href="#">Templates</a>&nbsp;/ Food & Restuarent
</div>
</div>

<div class="container">
    <div class="heading-container"> <h1><h1>450 Food & Restaurant Website <br> Designs</h1></h1><br><br>
   <div class="search">
    <input type="search" placeholder="Enter KeyWords" size="50">
    <i class="fa fa searchbar"></i><br><br>
    <div class="container"> <h4>If you need a food-related website, you can get our mobile and SEO-friendly website <br> templates for a restaurant, cafe, pizzeria, and any other cooking topic and place for free. All <br> templates are absolutely user-friendly and look perfect on any device.</h4></div>
</div>

</div>

<div class="parent">
    <ul >
        <button><li class="list" ><a href="#" class="hover">food</a></li></button>
        <button><li class="list"><a href="#" class="hover">restuarent</a></li></button>
        <button><li class="list"><a href="#" class="hover">menu</a></li></button>
        <button><li class="list"><a href="#" class="hover">agriculture</a></li></button>
        <button><li class="list"><a href="#" class="hover">coffee</a></li></button>
        <button><li class="list"><a href="#" class="hover">bakery</a></li></button>
        <button><li class="list"><a href="#" class="hover">water</a></li></button>
        <button><li class="list"><a href="#" class="hover">pizza</a></li></button>
        <button><li class="list"><a href="#" class="hover">farm</a></li></button>
        <button><li class="list"><a href="#" class="hover">wine</a></li></button>
        <button><li class="list"><a href="#" class="hover">cafe</a></li></button>
        <button><li class="list"><a href="#" class="hover">cake</a></li></button>
        <button><li class="list"><a href="#" class="hover">bar</a></li></button>
        <button><li class="list"><a href="#" class="hover">receipe</a></li></button>
        <button><li class="list"><a href="#" class="hover">kitchen</a></li></button>
        <button><li class="list"><a href="#" class="hover">nutrition</a></li></button>
        <button><li class="list"><a href="#" class="hover">receips</a></li></button>
        <button><li class="list"><a href="#" class="hover">organic</a></li></button>
        <button><li class="list"><a href="#" class="hover">diet</a></li></button>
        <button><li class="list"><a href="#" class="hover">honey</a></li></button>
        <button><li class="list"><a href="#" class="hover">apple</a></li></button>
        <button><li class="list"><a href="#" class="hover">tea</a></li></button>
        <button><li class="list"><a href="#" class="hover">fish</a></li></button>
        <button><li class="list"><a href="#" class="hover">farming</a></li></button>
        <button><li class="list"><a href="#" class="hover">cooking</a></li></button>
        <button><li class="list"><a href="#" class="hover">super market</a></li></button>
        <button><li class="list"><a href="#" class="hover">meet</a></li></button>
        <button><li class="list"><a href="#" class="hover">fastfood</a></li></button>
        <button><li class="list"><a href="#" class="hover">fruit</a></li></button>
        <button><li class="list"><a href="#" class="hover">catering</a></li></button> 
    </ul>
</div>
    <div class="mainbody">
        <div class="body1">
            <img id="img" src="https://images01.nicepagecdn.com/page/52/37/website-design-52372.jpg" alt="">burger food <br><br> 
            <img id="img" src="https://images01.nicepagecdn.com/page/36/87/website-design-36877.jpg"> Organic Natural Food<br><br>
            <img id="img" src="https://images01.nicepagecdn.com/page/47/13/website-design-4713195.jpg" alt=""> Our Pizza Menu<br><br>
            <img id="img" src="https://images01.nicepagecdn.com/page/57/16/website-design-57161.jpg" alt=""> Organic Green Eating<br><br>
            <img id="img" src="https://images01.nicepagecdn.com/page/10/07/website-design-100768.jpg" alt=""> See Found Menu<br><br>
            <img id="img" src="https://images01.nicepagecdn.com/page/13/98/website-design-139887.jpg" alt="">Gallary Food<br><br>
            <img id="img" src="https://images01.nicepagecdn.com/page/20/67/website-design-2067546.jpg" alt="">Coffee Ceromones<br><br>
             
        </div>
    </div>
    <div class="mainbody">
        <div class="body2">
            <img id="img" src="https://images01.nicepagecdn.com/page/50/53/website-design-50537.jpg" alt="">
            Fantastic Freshly Made Pizza
            <img id="img" src="https://images01.nicepagecdn.com/page/23/17/website-design-23176.jpg" alt="a"> Fine Oriental Restuarent<br><br>
            <img id="img" src="https://images01.nicepagecdn.com/page/33/89/website-design-338987.jpg" alt="a"> Romantic Evening..<br><br>
            <img id="img" src="https://images01.nicepagecdn.com/page/44/98/website-design-44981.jpg" alt="a"> Ice Cream,And Frozon Treats<br><br>
            <img id="img" src="https://images01.nicepagecdn.com/page/16/72/website-design-1672675.jpg" alt=""> Snacks and Aperitifs<br><br>
            <img id="img" src="https://images01.nicepagecdn.com/page/28/16/website-design-2816697.jpg" alt=""> Green Tea Hostory Benifits<br><br>
            <img id="img" src="https://images01.nicepagecdn.com/page/84/15/website-design-841597.jpg" alt="">Coffee Traditions<br><br>
            <img id="img" src="https://images01.nicepagecdn.com/page/61/02/website-design-61028.jpg" alt="">Be Better Then Yourself<br><br>
            <img id="img" src="https://images01.nicepagecdn.com/page/38/01/website-design-38011.jpg" alt="">Eating Essential  For Food<br><br>
            <img id="img" src="https://images01.nicepagecdn.com/page/92/46/website-design-92461.jpg" alt="">Cakes And Sweats
            
        </div>
    </div>
    <div class="mainbody">
            <div class="body3">
            <img id="img" src="https://images01.nicepagecdn.com/page/38/14/website-design-3814297.jpg" alt="">Hot and Delisious<br><br>
            <img id="img" src="https://images01.nicepagecdn.com/page/11/07/website-design-110798.jpg" alt="">Fresh Juice Drink<br><br>
            <img id="img" src="https://images01.nicepagecdn.com/page/65/68/website-design-65683.jpg" alt="">Get Delicious Meals <br><br>
            <img id="img" src="https://images01.nicepagecdn.com/page/14/52/website-design-145210.jpg" alt="">Healthy Bread<br><br>
            <img id="img" src="https://images01.nicepagecdn.com/page/17/22/website-design-17223.jpg" alt="">StarBucks Coffee<br><br>
            <img id="img" src="https://images01.nicepagecdn.com/page/76/47/website-design-76470.jpg" alt="">Breakfast Smoothie.. <br><br>
            <img id="img" src="https://images01.nicepagecdn.com/page/76/45/website-design-76457.jpg" alt=""> Healthy Eating..<br><br>
            <img id="img" src="https://images01.nicepagecdn.com/page/17/54/website-design-175480.jpg" alt=""><br><br> Coconut Cocktails..
            
        </div>
    </div>
    <div class="mainbody">
        <div class="body4">
            <img id="img" src="	https://images01.nicepagecdn.com/page/19/81/website-design-19813.jpg" alt="">Tasty And Fresh Food<br><br>
            <img id="img" src="https://images01.nicepagecdn.com/page/53/15/website-design-531575.jpg" alt="">Fresh & Healthy Food<br><br><br>
            <img id="img" src="https://images01.nicepagecdn.com/page/91/38/website-design-91384.jpg" alt="">During on The Lake<br><br>
            <img id="img" src="https://images01.nicepagecdn.com/page/27/59/website-design-2759407.jpg" alt="">COme to Ice Cafe<br><br>
            <img id="img" src="https://images01.nicepagecdn.com/page/81/87/website-design-81871.jpg" alt="">Italian Recieps.<br><br><br>
            <img id="img" src="https://images01.nicepagecdn.com/page/29/73/website-design-29734.jpg" alt="">Finest Grill House Restuarent.<br><br>
            
        </div>
    </div>

        <div class="matter-container">
            <center><h1>Food & Restaurant Website Templates</h1><br><br></center>
            <h5> &nbsp;&nbsp;&nbsp; The Food & Restaurant Website Templates are also available for unlimited downloads. If you only now start selling, the responsive restaurant template is to help you. Find the best free restaurant website templates on Nicepage. With WordPress plugins, you can do things you've never even thought. Business WordPress themes are equipped with all the necessary sections you might need in a website's functionality. You can put an online ordering system on one page, sound effects, food menu, and restaurant menu on another, also. Don't forget about the landing pages either. The HTML restaurant templates use a creative design that will differentiate you from the competitors. A fully responsive one page restaurant website template based on Bootstrap 4, allows anyone to create beautiful professional websites in minutes. Free WordPress themes with responsive web design include practical premium plugins. Responsive restaurant menu templates allow you to display your content intuitively. Download from our site bistro HTML template, restaurant online ordering HTML template, layout for the food menu, ordering system template, HTML restaurant template with video assets, food delivery template with colorful design, cake shop responsive website template, and so on. Like a cafe and restaurant template, food online ordering allows you to install a demo version with a single click food delivery wtih reservation form. </h5><br>

             <h5>&nbsp;&nbsp;&nbsp;   By choosing HTML template restaurant website templates, you will impress and anticipate the expectations of your restaurant's cafe visitors and customers! HTML templates fully developed with the latest web design trends. The HTML restaurant templates use a creative design that will differentiate you from the competitors. Restaurant HTML templates guarantee a responsive website displays on a variety of devices and have everything you need to create food website templates. A responsive HTML website looks amazing on any device, especially with effects templates. If you are looking for top responsive restaurant website templates, you can find them on our website. You can give your fans an interesting experience with restaurants html5 website templates 2022. Explore popular categories of responsive restaurant templates, where will be stunning video backgrounds and innovative parallax effects. Elixir restaurant HTML layout with an editor makes it easy to create or customize pages because it uses advanced Drag and Drop technology. Responsive HTML gourmet restaurant and food template have several demonstrations, each of which is imported in a mouse press. </h5><br>
                
              <h5>&nbsp;&nbsp;&nbsp;  Popular categories of website templates are restaurant web templates. coffee shop, fast food restaurant template, food delivery service, cafe, and restaurant owners have the opportunity with refined and mouthwatering web design assets to make a good bid. The cafe and restaurant design templates focus on versatility and ease of use for developers and end-users alike. Restaurant website template available for unlimited downloads. If you only now start selling, restaurant template and food website are to help you. Compared to real estate site templates, restaurants & cafes templates look appetite. Modern cafe and restaurant website online templates compatible with portable devices and all web browsers. A bootstrap modern restaurant HTML template can impress the target audience. A responsive restaurant HTML template comes with an unusual drag-and-drop constructor.</h5>
        </div><br>
   
        <div class="end">
            <div class="content">
               <br><h2> Company</h2><br>
                <ul>
                <h4> <li><a href="https://nicepage.com/doc/frequently-asked-questions-16656">FAQ</a></li><br>
                    <li><a href="https://nicepage.com/Terms">Terms of Use</a></li><br>
                    <li><a href="https://nicepage.com/Privacy">Privacy Policy</a></li><br>
                    <li><a href="https://nicepage.com/Agreement">License Agreement</a></li><br>
                    <li><a href="https://nicepage.com/About">About Us</a></li><br>
                    <li><a href="https://nicepage.com/partners">Partners</a></li><br>
                    <li><a href="https://nicepage.com/Abuse">Abuse</a></li><br>
                    <li><a href="https://nicepage.com/Forum/Topic/Create">Contact Support</a></li></h4>                </ul>
            </div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <div class="content1">
                <br><h2>Product</h2><br>
                <ul>
                <h4><li><a href="https://nicepage.com/download">Download</a></li><br>
                    <li><a href="https://nicepage.com/features">400+ Features</a></li><br>
                    <li><a href="https://nicepage.com/nicepage-review">Review</a></li><br>
                    <li><a href="https://nicepage.com/affiliates">Affiliates</a></li><br>
                    <li><a href="https://nicepage.com/doc">Documentation</a></li><br>
                    <li><a href="https://nicepage.com/forum">Forum</a></li><br>
                    <li><a href="https://nicepage.com/blog">Blog</a></li></h4>
                </ul>
            </div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <div class="content2">
               <br> <h2>Themes & Templates</h2><br>
                <ul>
                <h4><li><a href="https://nicepage.com/website-templates">Website Templates</a></li><br>
                    <li><a href="https://nicepage.com/wordpress-themes">WordPress Themes</a></li><br>
                    <li><a href="https://nicepage.com/html-templates">HTML Templates</a></li><br>
                    <li><a href="https://nicepage.com/css-templates">CSS Templates</a></li><br>
                    <li><a href="https://nicepage.com/joomla-templates">Joomla Templates</a></li><br>
                    <li><a href="https://nicepage.com/woocommerce-theme">WooCommerce Themes</a></li><br>
                    <li><a href="https://nicepage.com/html5-template">HTML5 Templates</a></li><br>
                    <li><a href="https://nicepage.com/one-page-template">One Page Templates</a></li></h4>
                </ul>
            </div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <div class="content3">
               <br> <h2>Nicepage</h2><br>
                <ul>
                <h4><li><a href="https://nicepage.com/website-builder">Website Builder</a></li><br>
                    <li><a href="https://nicepage.com/html">HTML Website Builder</a></li><br>
                    <li><a href="https://nicepage.com/wordpress">WordPress Website Builder</a></li><br>
                    <li><a href="https://nicepage.com/joomla">Joomla Page Builder</a></li><br>
                    <li><a href="https://nicepage.com/wysiwyg-html-editor">WYSIWYG HTML Editor</a></li><br>
                    <li><a href="https://nicepage.com/static-site-generator">Static Site Generator</a></li><br>
                    <li><a href="https://nicepage.com/html-code">HTML Code Generator</a></li></h4>
                </ul>
            </div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <div class="content4">
               <br> <h2>Web Design</h2><br>
                <ul>
                <h4><li><a href="https://nicepage.com/website-design">Website Designs</a></li><br>
                    <li><a href="https://nicepage.com/web-page-design">Web Page Designs</a></li><br>
                    <li><a href="https://nicepage.com/web-design">Web Design</a></li><br>
                    <li><a href="https://nicepage.com/web-page-designer">Web Page Designer</a></li><br>
                    <li><a href="https://nicepage.com/landing-page">Landing Pages</a></li><br>
                    <li><a href="https://nicepage.com/homepage-design">Homepage Designs</a></li><br>
                    <li><a href="https://nicepage.com/website-mockup">Website Mockup</a></li></h4>
                </ul>
            </div>
    </div>
    <div class="last">
        <div class="icon">
            <ul>
                <li>
                   <img id="logo" src="data:image/jpeg;base64,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" alt=""> <a href="https://facebook.com/nicepageapp">facebook</a>
                </li>
            </ul>
        </div>
        <div class="icon1">
            <ul>
                <li>
                   <img id="logo1" src="data:image/png;base64,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" alt=""> <a href="https://twitter.com/NicepageApp">twitter</a>
                </li>
            </ul>
        </div>
        <div class="icon2">
            <ul>
                <li>
                   <img id="logo2" src="data:image/png;base64,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" alt=""> <a href="https://youtube.com/nicepage?sub_confirmation=1">youtube</a>
                </li>
            </ul>
        </div>
        <div class="icon3">
            <ul>
                <li>
                   <img id="logo3" src="data:image/png;base64,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" alt=""> <a href="https://www.pinterest.com/nicepagecom/pins">pinterest</a>
                </li>
            </ul>
        </div>
        <div class="text">© 2023 Nicepage Free Website Builder Software - All Rights Reserved &nbsp;&nbsp;&nbsp;&nbsp;</div>
    </div>
    <div class="end">
        <ul>
            <h1>Team Members</h1 ><hr><hr><br>
            <li>Mr.Sunil Kumar</li><br>
            <li>Mr. Vinay Kumar</li><br>
            <li>Mr.Das </li><br>
            <li>Mr.Sai </li><br>
            <li>Mr.Dileep Kumar(Lead)</li><br>
            <li>Mr.Ajay</li>
        </ul>
    </div>
</body>
</html>
