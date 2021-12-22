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
```
### Home Page coding:

<!DOCTYPE html>
<html lang="en">
  <head>
    <title> LimitJRed</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon1.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">JR Limited</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/book.jpg" alt="book"/>
          <div class="contenttext">
            Welcome to JR Limited!
             JR is an online bookstore with a mission to financially support local, 
             independent bookstores.
             We believe that bookstores are essential to a healthy culture. 
             They where authors can connect with readers, 
             where we discover new writers, where children get hooked on the thrill of 
             reading that can last a lifetime. There also anchors for our downtowns and communities.
            <br />
            We hope that Bookshop can help strengthen the fragile ecosystem and margins around bookselling 
            and keep local bookstores an integral part of our culture and communities.
            Bookshop is a benefit corporation - a corporation dedicated to the public good.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Note worthy books </li>
              <li>Anywhere, anytime access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 EduSoft Private Limited, Developed by Jainson Raphael.V
      </div>
    </div>
  </body>
</html>

### Product coding:

<!DOCTYPE html>
<html lang="en">
  <head>
    <title> LimitJRed</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon1.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">JR Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected"><a href="/static/products.html">Products</a></div>  
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/tally_gold.png" alt="product image">
                  </div>
                  <div class="itemname">Tally Gold</div>
                  <div class="itemprice">Price:Rs.10,000</div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/tally_silver.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Silver</div>
                  <div class="itemprice">Price:Rs.8999</div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/b1.png"  alt="product image">
                  </div>
                  <div class="itemname">The special AI</div>
                  <div class="itemprice">Price: Rs.7599 </div>
              </div>

              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/b2.jpg"  alt="product image">
                </div>
                <div class="itemname">System Software</div>
                <div class="itemprice">Price: 5599 </div>
            </div>

            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/b3.jpg"  alt="product image">
              </div>
              <div class="itemname">arithemetic operations</div>
              <div class="itemprice">Price: Rs.700.00 </div>
          </div>

          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/b5.jpg"  alt="product image">
            </div>
            <div class="itemname">Software enginerring design</div>
            <div class="itemprice">Price: Rs.859 </div>
        </div>

        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/b6.jpg"  alt="product image">
          </div>
          <div class="itemname">electronics and design AI</div>
          <div class="itemprice">Price: Rs.500.00 </div>
      </div>

      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/b7.jpg"  alt="product image">
        </div>
        <div class="itemname">software testing</div>
        <div class="itemprice">Price: Rs.759 </div>
    </div>

    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/b8.jpg"  alt="product image">
      </div>
      <div class="itemname">AI&ML</div>
      <div class="itemprice">Price: Rs.1999 </div>
    </div>

    <div class="productitem"> 
       <div class="itemimage">
       <img src="/static/img/b9.jpg"  alt="product image">
       </div>
       <div class="itemname">patterns of AI</div>
       <div class="itemprice">Price: Rs.2229.00 </div>
    </div>
    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/b10.jpg"  alt="product image">
    </div>
       <div class="itemname">arithemeticdesign </div>
       <div class="itemprice">Price: Rs.789 </div>
    </div>

    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/b11.jpg"  alt="product image">
     </div>
        <div class="itemname">Jaans AI</div>
        <div class="itemprice">Price: Rs.2559 </div>
      </div>
    </div>
  </div>        
  </div>
    <div class="footer">
      Copyright &#169; 2021 EduSoft Private Limited, Developed by Jaison Raphael.V
    </div>
  </div>
 </body>
</html>

### People coding:

<!DOCTYPE html>
<html lang="en">
  <head>
    <title> LimitJRed</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon1.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">JR Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>  
        <div class="menuitemselected"><a href ="/static/people.html"></a>People</a></div>
        <div class="menuitem"><a href="/static/contact us.html">Contact Us</a></div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/s1.jpg"  alt="product image">
      </div>
         <div class="itemname">HEAD of the company
           <br>
           (dean ambrose)
         </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/s2.jpg"  alt="product image">
      </div>
         <div class="itemname">Manager
           <br>
           (Elon)
         </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/s3.jpg"  alt="product image">
      </div>
         <div class="itemname">Assistant Manager <br>(Tony Stark)</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/4.jpg"  alt="product image">
      </div>
         <div class="itemname">Product Department Head <br> (steve rogers)</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/s5.jpg"  alt="product image">
      </div>
         <div class="itemname">Deliver Department Head <br> (chris evans)</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/s6.jpg"  alt="product image">
      </div>
         <div class="itemname">Chennai Branch Head <br> (jelena bidan)</div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 EduSoft Private Limited, Developed by Jainson Raphael.V
      </div>
    </div>
  </body>
</html>

### Contact us:

<!DOCTYPE html>
<html lang="en">
  <head>
    <title> LimitJRed</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon1.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">JR Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>  
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contact us.html">Contact Us</a></div>
      </div>
      
        <div class="contact content">
           <h1>Our Contact Address</h1>  
        
          <div class="contacttext">
           Phone:9486443639
           <br>Eamail-address:jrliitet@gmail.com
          </div>
        </div>

     
<div class="footer">
  Copyright &#169; 2021 EduSoft Private Limited, Developed by Jainson Raphael.V
</div>
</div>
</body>
</html>

### Layout css coding:

*{
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: whitesmoke;
  color: #17421d;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px gray;
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-image: url("/static/img/banner.jpg");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: black;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color:black;
  text-align: center;
  padding-top: 15px;
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
  color:rgb(114, 14, 114);
}

.menuitem a {
  text-decoration: none;
  color: #9c1018;
}

.content {
  display: block;
  width: 100%;
  background-color:white;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
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
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.productitem img {
  width: 100px;
  height: 100px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
}
.productitem .itemprice {
  display: block;
}

.footer {
  display: inline-block;
  width: 100%;
  height: 40px;
  background-color:black;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #9c1018;
}

.contact content{
  display: block;
  width: 100%;
  background-color:white;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.contacttext{
  text-align: justify;
  font-style: normal;
  font-size: larger;
}
.people content{
  display: block;
  width: 100%;
  background-color:white;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}

```
## OUTPUT:

### Home Page:

![output](./images/Homepage.png)

### Product Page:

![output](./images/Productpage.png)

### People Page:

![output](./images/Peoplepage.png)

### Contact Us Page:

![output](./images/Contactpage.png)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
