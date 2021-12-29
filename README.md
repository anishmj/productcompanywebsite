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
### HomePage
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title></title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">ANI SECURITY SOFTWARE</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static\home.html">Home</a></div>
        <div class="menuitem"><a href="/static\products.html">Products</a></div>
        <div class="menuitem"><a href="/static\people.html">People</a></div>
        <div class="menuitem"><a href="/static\contact_us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/sec.png" alt="Building" />
          <div class="contenttext">
            Security software is any type of software that
             secures and protects a computer,
              network or any computing-enabled device.
               It manages access control, provides data protection,
                secures the system against viruses and network/Internet based intrusions
                , and defends against other system-level security risks.
            <br />
            Antivirus software was originally developed to detect 
            and remove computer viruses, hence the name. However
            , with the proliferation of other malware, antivirus software started to 
            protect from other computer threats. In particular, modern antivirus 
            software can protect users from malicious browser helper objects (BHOs), 
            browser hijackers, ransomware, keyloggers, backdoors, rootkits,
             trojan horses, worms, malicious LSPs, dialers, fraud tools, adware, 
             and spyware. Some products also include protection from other computer threats, 
             such as infected and malicious URLs, spam, scam and phishing attacks, online identity (privacy), 
             online banking attacks, social engineering techniques, advanced persistent threat (APT), and botnet DDoS attacks.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
           
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 ANI COMPANY LTD FOUNDER:ANISH M.J.
      </div>
    </div>
  </body>
</html>
```
### ProductsPage:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">ANI SECURITY SOFTWARE</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact_us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/avg logo.png" alt="product image">
                  </div>
                  <div class="itemname">AVG ANTI-VIRUS</div>
                  <div class="itemprice">Price: Rs.2500.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/avira.png"  alt="product image">
                  </div>
                  <div class="itemname">AVIRA ANTI-VIRUS</div>
                  <div class="itemprice">Price: Rs.2500.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/bitdefender.png"  alt="product image">
                </div>
                <div class="itemname">BITDEFENDER</div>
                <div class="itemprice">Price: Rs.2500.00 </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/bullguard.png"  alt="product image">
            </div>
            <div class="itemname">BULL GUARD</div>
            <div class="itemprice">Price: Rs.2500.00 </div>
          </div>  
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/eset.png"  alt="product image">
            </div>
            <div class="itemname">ESET ANTI-VIRUS</div>
            <div class="itemprice">Price: Rs.2500.00 </div>      
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/f-secure.png"  alt="product image">
        </div>
        <div class="itemname">F-SECURE</div>
        <div class="itemprice">Price: Rs.2500.00 </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/gdata.png"  alt="product image">
          </div>
          <div class="itemname">G-DATA ANTIVIRUS</div>
          <div class="itemprice">Price: Rs.2500.00 </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/kaspersky.png"  alt="product image">
            </div>
            <div class="itemname">KASPERSKY ANTIVIRUS</div>
            <div class="itemprice">Price: Rs.2500.00 </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/mcafee.png"  alt="product image">
              </div>
              <div class="itemname">MCAFEE ANTIVIRUS</div>
              <div class="itemprice">Price: Rs.2500.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/norton.png"  alt="product image">
                </div>
                <div class="itemname">NORTON ANTIVIRUS</div>
                <div class="itemprice">Price: Rs.2500.00 </div>
                </div>
                  <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/sophos.png"  alt="product image">
                    </div>
                    <div class="itemname">SOPHOS ANTIVIRUS</div>
                    <div class="itemprice">Price: Rs.2500.00 </div>
                    </div>
                    <div class="productitem"> 
                      <div class="itemimage">
                      <img src="/static/img/trend.png"  alt="product image">
                      </div>
                      <div class="itemname">TREND ANTIVIRUS</div>
                      <div class="itemprice">Price: Rs.2500.00 </div>
                      </div>
      <div class="footer">
        Copyright &#169; 2021 ANI COMPANY LTD, FOUNDER: ANISH M.J.
      </div>
    </div>
  </body>
</html>
```
### PeoplePage:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title></title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">ANI SECURITY SOFTWARE</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact_us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
            <h1>BEST PROGRAMMERS IN INDIA </h1>
            <div class="productitems">
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/kavyaa.jpg" alt="product image">
                    </div>
                    <div class="itemname">KAVYAA</div>
                    <div class="itemprice">CEO OF ANI SOFTWARE COMPANY</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/deepak.jpg"  alt="product image">
                    </div>
                    <div class="itemname">DEEPAK</div>
                    <div class="itemprice">SOFTWARE DEVELOPER-1</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/sakshi.jpg"  alt="product image">
                    </div>
                    <div class="itemname">SAKSHI</div>
                    <div class="itemprice">SOFTWARE DEVELOPER-2</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/jaswanth.jpg"  alt="product image">
                    </div>
                    <div class="itemname">EMPLOYEE</div>
                    <div class="itemprice">WORKING IN ANI SOFTWARE COMPANY</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/rakshana.jpg"  alt="product image">
                    </div>
                    <div class="itemname">EMPLOYEE</div>
                    <div class="itemprice">WORKING IN ANI SOFTWARE COMPANY</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/kohli.jpg"  alt="product image">
                    </div>
                    <div class="itemname">VIRAT KOHLI</div>
                    <div class="itemprice">SOFTWARE DEVELOPER</div>
                </div>

          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 SOFTWARE ltd, FOUNDER:ANISH M.J.
      </div>
    </div>
  </body>
</html>
```
### ContactPage:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>JAM RESTAU`</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">ANI SECURITY SOFTWARE</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contact_us.html">Contact Us</a></div>
      </div>
      <div class="content">
          <ul>
              <li>Address: CHENNAI <br></li>
              <li>Contact:44524378;<br></li>
              <li>mjanish19@gmail.com.com<br></li>
              <br>VERIFIED*
          </ul>    
        </div>
    </div>
    </div>
    </div>
      <div class="footer">
        Copyright &#169; ANI COMPANY LTD, FOUNDER:ANISH M.J.
      </div>
    </div>
  </body>
</html>
```
### css layout:
```
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: whitesmoke;
  color: #e01880;
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
  height: 300px;
  text-align: center;
  font-size: 75px;
  font-weight: 10000;
  background-image: url("/static/img/computer.png");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #0af11d;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #0a29da;
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
  color: #16d1ae;
}

.menuitem a {
  text-decoration: none;
  color: #9c1018;
}

.content {
  display: block;
  width: 100%;
  background-color: #f7071b;
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
  display: block;
  width: 100%;
  height: 40px;
  background-color: #5bb041;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #9c1018;
}
```



## OUTPUT:

### HomePage:
![output](/companywebsite/static/img/homeout.png)
### ProductPage:
![output](/companywebsite/static/img/productout.png)
### PeoplePage:
![output](/companywebsite/static/img/peopleout.png)
### ContactusPage:
![output](/companywebsite/static/img/contactout.png)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
