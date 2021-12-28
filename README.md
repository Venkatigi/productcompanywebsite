# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
~~~
Layout In CSS:

* {
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
}

body {
    background-color: rgb(255, 255, 255);
    color: #17421d;
}

.container {
    width: 1080px;
    margin-left: auto;
    margin-right: auto;
    border-width: 0px 0px 0px 0px;
    border-style: solid;
    box-shadow: 15px 15px 8px rgb(255, 255, 255);
}

.banner {
    display: block;
    width: 100%;
    height: auto;
    text-align: right;
    font-size: 60px;
    background-image: url("/static/img/banner1.jpg");
    background-size: 100% 100%;
    margin: 0px 0px 0px 0px;
    padding-top: 0px;
    color: #16d1ae;
}

.menu {
    display: inline-block;
    width: 80%;
    height: 50px;
    font-size: larger;
    background-color: #ffffff;
    text-align: left;
    padding-top: 0px;
    margin: 0px 0px 0px 0px;
    border-width: 1px;
}

.menuitem {
    display: inline-block;
    margin-left: 10px;
    margin-right: 10px;
}

.menuitemselected {
    display: inline-block;
    margin-left: 10px;
    margin-right: 10px;
    color: #16d1ae;
}

.menuitem a {
    text-decoration: none;
    color: #9c1018;
}

.content {
    display: block;
    width: 100%;
    background-color: #ffffff;
    min-height: 500px;
    margin: 0px 0px 0px 0px;
    border-width: 1px;
    border-color: rgb(126, 123, 123);
    border-style: none;
}

.homecontent {
    min-height: 500px;
    margin: 10px 10px 10px 10px;
}

.homecontent h1 {
    text-align: left;
}

.homecontent img {
    float: right;
    width: 400px;
    height: 300px;
    margin-left: 10px;
}

.contenttext {
    text-align: justify;
}

.productcontent {
    min-height: 500px;
    margin: 10px 10px 10px 10px;
}

.productcontent h1 {
    text-align: left;
}

.productitems {
    display: block;
    padding: 20px;
}

.productitem {
    display: inline-block;
    width: 45%;
    height: 250px;
    text-align: center;
}

.productitem img {
    width: 300px;
    height: 200px;
    display: block;
}

.productitem .itemimage {
    display: block;
    margin-left: auto;
    margin-right: auto;
    width: 100px;
    margin-bottom: 20px;
}

.productitem .itemname {
    display: block;
}

.productitem .itemprice {
    display: block;
}

.footer {
    display: block;
    width: 100%;
    height: 330px;
    background-color: #542b5b;
    text-align: center;
    padding-top: 275px;
    margin: 0px 0px 0px 0px;
    color: #ffffff;
}

.ll {
    border: none;
    background-color: #837c7c6e;
    color: #000000;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 0px 0px;
    cursor: pointer;
}

.ll:hover {
    background-color: #542b5b;
    color: #ffffff;
}

.ld {
    display: inline-block;
    width: 100%;
    height: 3px;
    background-color: black;
}

.banner1 {
    display: block;
    width: 100%;
    height: auto;
    text-align: left;
    font-size: 60px;
    background-image: url("/static/img/banner1.jpg");
    background-size: 100% 100%;
    margin: 0px 0px 0px 0px;
    padding-top: 0px;
    color: #16d1ae;
}

.footer1 {
    display: block;
    width: 100%;
    height: 100px;
    background-color: #542b5b;
    text-align: center;
    padding-top: 50px;
    margin: 0px 0px 0px 0px;
    color: #ffffff;
}

.footer2 {
    display: block;
    width: 100%;
    height: 310px;
    background-color: #542b5b;
    text-align: center;
    padding-top: 170px;
    margin: 0px 0px 0px 0px;
    color: #ffffff;
}
~~~
~~~
Home Page: 

<!DOCTYPE html>
<html lang="en">

<head>
    <title>Techrocs</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/1.png" type="image/x-icon" />
</head>

<body>
    <div class="container">
        <div class="banner">
            <a href="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite\static\home.html">
                <img src="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite\static\img\1.png">
            </a>
        </div>

        <div class="menu">
            <div class="menuitem"><a href="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite\static\home.html"><button class="ll">Home</button></a></div>
            <div class="menuitem"><a href="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite\static\products.html"><button class="ll">Products</button></a></div>
            <div class="menuitem"><a href="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite\static\people.html"><button class="ll">People</button></a></div>
            <div class="menuitem"><a href="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite\static\contactus.html"><button class="ll">Contact Us</button></a></div>
        </div>
        <div class="ld">

            <div class="content">
                <div class="homecontent">
                    <h1>About Us</h1>
                    <img src="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite\static\img\2.png" width="100" height="100" alt="Building" />
                    <div class="contenttext">
                        Techrocs is an American multinational technology company which focuses on e-commerce, cloud computing, digital streaming, and artificial intelligence. It is one of the Big Five companies in the U.S. information technology industry, along with Alphabet
                        (Google), Apple, Meta (Facebook), and Microsoft.The company has been referred to as "one of the most influential economic and cultural forces in the world", as well as the world's most valuable brand.
                        <ul>
                            <li>Techrocs Cloud</li>
                            <li>Techrocs Store</li>
                            <li>Techrocs Drive</li>
                            <li>Prime Techro</li>
                        </ul>
                    </div>
                </div>
            </div>

        </div>
        <div class="footer">
            Copyright &#169; 2021 Techrocs, Developed by Venkatesh E.
        </div>
    </div>
</body>

</html>
~~~
~~~
Product Page:

<!DOCTYPE html>
<html lang="en">

<head>
    <title>Techrocs</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/1.png" type="image/x-icon" />
</head>

<body>
    <div class="container">
        <div class="banner">
            <a href="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite\static\home.html">
                <img src="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite\static\img\1.png">
            </a>
        </div>

        <div class="menu">
            <div class="menuitem"><a href="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite\static\home.html"><button class="ll">Home</button></a></div>
            <div class="menuitem"><a href="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite\static\products.html"><button class="ll">Products</button></a></div>
            <div class="menuitem"><a href="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite\static\people.html"><button class="ll">People</button></a></div>
            <div class="menuitem"><a href="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite\static\contactus.html"><button class="ll">Contact Us</button></a></div>
        </div>
        <div class="ld">
            <div class="content">
                <div class="productcontent">
                    <h1>Our Premium Products</h1>
                    <div class="productitems">
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite/static/img/4(88k).png" alt="product image">
                            </div>
                            <div class="itemname"> HP ProBook 440 G8 Notebook PC</div>
                            <div class="itemprice">Price: Rs.89,000.00 </div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite/static/img/3(47k).png" alt="product image">
                            </div>
                            <div class="itemname">HP All-in-One 24-df1669in PC</div>
                            <div class="itemprice">Price: Rs.47,000.00 </div>
                        </div>

                    </div>
                    <div class="productitems">
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite/static/img/5(99k).png" alt="product image">
                            </div>
                            <div class="itemname"> Dell New Latitude 15 5520 Laptop</div>
                            <div class="itemprice">Price: Rs.99,000.00 </div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite/static/img/6(60k).png" alt="product image">
                            </div>
                            <div class="itemname">Dell Inspiron 15 3000 laptop</div>
                            <div class="itemprice">Price: Rs.60,000.00 </div>
                        </div>

                    </div>
                    <div class="productitems">
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite/static/img/flip.png" alt="product image">
                            </div>
                            <div class="itemname"> Samsung Galaxy Z Flip </div>
                            <div class="itemprice">Price: Rs.84,000.00 </div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite/static/img/fold.png" alt="product image">
                            </div>
                            <div class="itemname">Samsung Galaxy Z Fold3 5G </div>
                            <div class="itemprice">Price: Rs.1,50,000.00 </div>
                        </div>

                    </div>
                    <div class="productitems">
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite/static/img/ear1.png" alt="product image">
                            </div>
                            <div class="itemname"> Xiaomi TWS 3 Pro True Wireless Earbuds</div>
                            <div class="itemprice">Price: Rs.8,000.00 </div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite/static/img/jaba.png" alt="product image">
                            </div>
                            <div class="itemname">Jabra Elite 3 True Wireless Stereo (TWS) Earphones</div>
                            <div class="itemprice">Price: Rs.6,000.00 </div>
                        </div>

                    </div>
                    <div class="productitems">
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite/static/img/re.png" alt="product image">
                            </div>
                            <div class="itemname">Royal Enfield Meteor 350 </div>
                            <div class="itemprice">Price: Rs.2,80,000.00 </div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite/static/img/him.png" alt="product image">
                            </div>
                            <div class="itemname">Royal Enfield Himalayan 411</div>
                            <div class="itemprice">Price: Rs.2,10,000.00 </div>
                        </div>

                    </div>
                    <div class="productitems">
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite/static/img/app.png" alt="product image">
                            </div>
                            <div class="itemname">Apple 140W USB-C Power Adapter</div>
                            <div class="itemprice">Price: Rs.9,000.00 </div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite/static/img/xi.png" alt="product image">
                            </div>
                            <div class="itemname">XIAOMI 120W QUICK CHARGE USB WALL CHARGER</div>
                            <div class="itemprice">Price: Rs.6,000.00 </div>
                        </div>

                    </div>
                </div>
            </div>
        </div>
        <div class="footer1">
            Copyright &#169; 2021 Techrocs, Developed by Venkatesh E.
        </div>
    </div>
</body>

</html>
~~~
~~~
People Page :

<!DOCTYPE html>
<html lang="en">

<head>
    <title>Techrocs</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/1.png" type="image/x-icon" />
</head>

<body>
    <div class="container">
        <div class="banner">
            <a href="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite\static\home.html">
                <img src="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite\static\img\1.png">
            </a>
        </div>

        <div class="menu">
            <div class="menuitem"><a href="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite\static\home.html"><button class="ll">Home</button></a></div>
            <div class="menuitem"><a href="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite\static\products.html"><button class="ll">Products</button></a></div>
            <div class="menuitem"><a href="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite\static\people.html"><button class="ll">People</button></a></div>
            <div class="menuitem"><a href="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite\static\contactus.html"><button class="ll">Contact Us</button></a></div>
        </div>
        <div class="ld">
            <div class="content">
                <div class="productcontent">
                    <h1>Our COO (Chief Operating Officers)</h1>
                    <div class="productitems">
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite/static/img/tata.png" alt="product image">
                            </div>
                            <div class="itemname"> Ratan Tata</div>
                            <div class="itemprice">COO of Strategy</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite/static/img/warren.jpg" alt="product image">
                            </div>
                            <div class="itemname">Warren Buffett</div>
                            <div class="itemprice">COO of Investing</div>
                        </div>

                    </div>
                    <div class="productitems">
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite/static/img/mukaesh.png" alt="product image">
                            </div>
                            <div class="itemname">Mukesh Ambani</div>
                            <div class="itemprice">COO of Telecom</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite/static/img/elon.png" alt="product image">
                            </div>
                            <div class="itemname">Elon Musk</div>
                            <div class="itemprice">COO of Space</div>
                        </div>

                    </div>
                    <div class="productitems">
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite/static/img/mark.png" alt="product image">
                            </div>
                            <div class="itemname">Mark Zuckerberg</div>
                            <div class="itemprice">COO of Social Marketting and Manipulator</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite/static/img/bill.png" alt="product image">
                            </div>
                            <div class="itemname">Bill Gates</div>
                            <div class="itemprice">COO of Health Affairs</div>
                        </div>

                    </div>
                </div>
            </div>
        </div>
        <div class="footer1">
            Copyright &#169; 2021 Techrocs, Developed by Venkatesh E.
~~~
~~~
Contact Us Page:

<!DOCTYPE html>
<html lang="en">

<head>
    <title>Techrocs</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/1.png" type="image/x-icon" />
</head>

<body>
    <div class="container">
        <div class="banner">
            <a href="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite\static\home.html">
                <img src="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite\static\img\1.png">
            </a>
        </div>

        <div class="menu">
            <div class="menuitem"><a href="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite\static\home.html"><button class="ll">Home</button></a></div>
            <div class="menuitem"><a href="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite\static\products.html"><button class="ll">Products</button></a></div>
            <div class="menuitem"><a href="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite\static\people.html"><button class="ll">People</button></a></div>
            <div class="menuitem"><a href="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite\static\contactus.html"><button class="ll">Contact Us</button></a></div>
        </div>
        <div class="ld">

            <div class="content">
                <div class="homecontent">
                    <h1>Contact Us</h1>
                    <img src="D:\ggg\clg\Documents\Web Tech\productcompanywebsite\companywebsite\static\img\2.png" width="100" height="100" alt="Building" />
                    <div class="contenttext">
                        <h2>Address:</h2>
                        <p>23-344 Roan square,<br>New York,<br>United States-344 3422 22</p>
                        <h2>Phone:</h2>
                        <p>Toll Free No:<br>+1 12345 09876<br>+1 54321 67890</p>
                        <h2>E-Mail:</h2>
                        <p>techrocs@chan.im</p>
                    </div>
                </div>
            </div>

        </div>
        <div class="footer2">
            Copyright &#169; 2021 Techrocs, Developed by Venkatesh E.
        </div>
    </div>
</body>

</html>
~~~
## OUTPUT:


### Home Page:

![Home](1.jpg)

### Product Page:

![Products1](121.png)
![Products2](122.png)


### People Page:

![People](5.jpg)

### Contact Page:

![contactus](6.jpg)

## Result:

Thus a website is designed for the software product company and the HTML ,  CSS code are validated.
