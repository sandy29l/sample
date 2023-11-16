# Ex.07 Software Product Company Website
## Date:09.11.23

## AIM:
To develop a static company website to display the softwares and services provided by the company.

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

### Step 7:
Publish the website in the given URL.

## PROGRAM:
## Home
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            Home Page
        </title>
        <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/styles.css">
    <style>
    .text{
        color:rgb(191, 133, 215);
        font-family:'Lucida Sans';
        font-size: 30px;
        text-align:center;
    }
    img{
        height: 150px;
        width: 150px;
        align-items:center;
    }
    </style>

    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: rgb(242, 187, 214)) text-decoration: none;"><b>Home</b></a></div>
                    <div class="prod">
                        <a href="product.html" title="Products" style="color: rgb(173, 204, 237)48); text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:rgb(202, 159, 208); text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:rgb(185, 203, 138); text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>NIZSO SOFTWARE COMPANY</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <marquee><b>Rasing Software Developer</b></marquee>
                    <p style="color:rgb(173, 222, 228)8) 195, 238); font-family:'Tahoma'; font-size:20px;"> This is the Official Website of our Software company!</p>
                    </div>
                    <p>Leading software developer <span style="background-color:rgb(180, 236, 180)">Nizso solutions</span>
                         GST Billing software | Supermarket software | Mobile shops | Restaurent management| And much more</p>
                    <br>
                <center>
                    <img src="/static/images/a.jpg">
                    <img src="/static/images/b.jpg">
                    <img src="/static/images/c.jpg">
                    <img src="/static/images/d.jpg">

                    
                    
                </center>
                </div>
                <div class="footer">
                <footer style="color:white">
                Copyright &copy;2023 Developed by Kabilan V</footer></div>
            </div>
        </div>
    </body>
</html>
```
## people
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            People
        </title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/CSS/styles.css">
        <style>
        .home{
            height: 3000px;
            width: 85%;
            border: 12px solid rgb(255, 0, 208);
            padding-left:10px;
            padding-right:10px;
            margin-left: auto;
            margin-right:auto;
            background-color:rgb(149, 249, 249);
        }
        .text{
        color:rgb(186, 139, 229);
        font-family:'Lucida Sans';
        font-size: 30px;
        text-align:center;
        
        }
        .content{
            border:2px solid rgb(140, 225, 140);
            background-color:rgb(145, 228, 224);
            width:98%;
            height:2690px;
            padding:10px;
            margin-left:auto;
            margin-right:auto;
        }
        .ceoph{
            background-image: url(/static/images/a.jpg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:3px solid rgb(145, 255, 0);
            height:300px;
            width:20%;
            position:relative;
            left: 0px;
            margin-left:auto;
            margin-right: auto;
        }
        .ceo{
            color: rgb(219, 108, 149);
            position:relative;
            text-align:center;
            
            
        }
        .manph1{
            background-image: url(/static/images/b.jpg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:300px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;            
        }
        .man1{
            color: rgb(224, 86, 176);
            position:relative;
            text-align:center;
            
        }
        .manph2{
            background-image: url(/static/images/c.jpg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:300px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .man2{
            color: rgb(232, 105, 204);
            position:relative;
            text-align:center;
        }
        
        .amph1{
            background-image: url(/static/images/d.jpg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:300px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .am1{
            color: rgb(255, 0, 208)(255, 0, 179);
            position:relative;
            text-align:center;
        }

        
        
        

        </style>
    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: rgb(232, 45, 163); text-decoration: none;"><b>Home</b></a></div>
                    <div class="prod">
                        <a href="products.html" title="Products" style="color: rgb(139, 0, 118), 0, 139); text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:rgb(139, 0, 120); text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:rgb(139, 0, 127); text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>People</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <p>Board Members</p>
                    <h4><u>Chairman</u></h4>
                    </div>
                    <div class="ceoph"></div>
                    <div class="ceo"><p align="center"><b><h2>LING_CHI</h2></b></div>
                    <br>
                    <div class="text">
                        <p><b><u>Head executives</u></b></p><br>
                    </div>
                    <div class="manph1"></div>
                    <div class="man1"><p align="center"><b><h2>ZHEN_SHI</h2></b></p></div>
                    <div class="manph2"></div>
                    <div class="man2"><p><b><h2>KAI_HUEN</h2></b></p></div>
                    <br>
                    <div class="text"><p><b><u>Manager</u></b></p></div><br>
                    <div class="amph1"></div>
                    <div class="am1"><p align="center"><b><h2>HUANG ZUI</h2></b></p></div>
                    

                    
                    
                    <div class="text">Quality code for reliable future!<br>!</div>
                </div>
                <div class="footer">
                <footer style="color:white">
                Copyright &copy;2023 Developed by Kabilan V</footer></div>
            </div>
        </div>
    </body>
</html>
```
## Product
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            Products
        </title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/styles.css">
        <style>
        .home{
            height: 1555px;
            width: 85%;
            border: 12px solid rgb(162, 176, 217);
            padding-left:10px;
            padding-right:10px;
            margin-left: auto;
            margin-right:auto;
            background-color:rgb(144, 218, 218);
        }
        .text{
            color:rgb(171, 133, 207);
            font-family:'Lucida Sans';
            font-size: 30px;
            text-align:center;
        
        }
        .content{
            border:3px solid rgb(214, 134, 195);
            background-color: white;
            width:98%;
            height:1190px;
            padding:10px;
            margin-left:auto;
            margin-right:auto;
        }
        .ph1{
            background-image: url(/static/images/h.jpg);
            background-size: 300px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:200px;
            width:30%;
            position:relative;
            left: 50px;
        }
        .l1{
            color: rgb(126, 199, 226);
            position:relative;
            right:380px;
            
            
        }
        .ph2{
            background-image: url(/static/images/css.jpg);
            background-size: 300px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:200px;
            width:30%;
            position:relative;
            left: 50px;
            
        }
        .l2{
            color: rgb(111, 176, 185)7, 244);
            position:relative;
            right:380px;

        
        }
        .ph3{
            background-image: url(/static/images/web.jpg);
            background-size: 300px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:200px;
            width:30%;
            position:relative;
            left: 70px;
            bottom: 40px;
        }
        .l3{
            color: rgb(152, 201, 229)5)
            position:relative;
            right:380px;
            
            
        }
        .ph4{
            background-image: url(/static/images/software.jpeg);
            background-size: 300px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:200px;
            width:30%;
            position:center;
            left: 200px;
        }
        .l4{
            color: rgb(68, 190, 204);
            position:relative;
            right:300px;
            
            
        }
        .bot{
            text-align:center;
            font-size:larger;
            color:magenta;

        }
        </style>
    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: rgb(141, 16, 122); text-decoration: none;"><b>Home</a></div>
                    <div class="prod">
                        <a href="products.html" title="Products" style="color: rgb(139, 0, 120), 0, 111); text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:rgb(139, 0, 90), 0, 90); text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:rgb(139, 0, 113), 0, 102); text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>Products</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <p>These are the products that are available now</p>
                    </div>
                    <div class="ph1"></div>
                    <div class="l1"><p align="center"><b>HTML<br><br><br><br></p></div>
                    <div class="ph2"></div>
                    <div class="l2"><p align="center"><b>CSS<br><br><br><br></p></div>
                    <div class="ph3"></div>
                    <div class="l3"><p align="center"><b>web software<br><br><br><br></p></div>
                    <div class="ph4"></div>
                    <div class="l4"><p align="center"><b>product development<br><br><br><br></p></div>
         
                </div>
                <div class="bot"><p>To Order Online: Call 9124445798</p></div>

                <div class="footer">
                <footer style="color:white">
                Copyright &copy;2023 Developed by kabilan V</footer></div>
            </div>
        </div>
    </body>
</html>
```
## Contact
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            Contact Us
        </title>
        <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/CSS/styles.css">
    <style>
    .text{
        color:rgb(103, 51, 153);
        font-family:'Lucida Sans';
        font-size: 30px;
        text-align:center;
    }
    
    </style>

    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: darkred; text-decoration: none;"><b>Home</b></a></div>
                    <div class="prod">
                        <a href="products.html" title="Products" style="color: darkred; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:darkred; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:darkred; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>Contact Us</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <p><b> Details about us as required
                    <h5>Do contact us if needed</h5></b></p>
                    
                    </div>
                    <b><h2>Contact Information:</h2></b>
                    <p><b>&emsp;&ensp;Address:</b>
                        anna nagar,chennai, TamilNadu, India.
                    </p>
                    <ul>
                        <li><b>Landline:</b> 23453444</li>
                        <li><b>Mobile</b>: 9124445798</li>
                        <li><b>Facebook</b>: fb/nachi</li>
                        <li><b>Email Id:</b>na@nizso.com</li>
                    </ul>
                    <div style="text-align: center;color:rgb(198, 97, 198);font-size:20px;"><b>Use our services and Beautify Yourself!</b></div>

                </div>
                <div class="footer">
                <footer style="color:white">
                Copyright &copy;2023 Developed by ALAGU NACHIYAR</footer></div>
            </div>
        </div>
    </body>
</html>
home.html
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            Home Page
        </title>
        <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/CSS/styles.css">
    <style>
    .text{
        color:rgb(139, 76, 199);
        font-family:'Lucida Sans';
        font-size: 30px;
        text-align:center;
    }
    img{
        height: 150px;
        width: 150px;
        align-items:center;
    }
    </style>

    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: darkred; text-decoration: none;"><b>Home</b></a></div>
                    <div class="prod">
                        <a href="products.html" title="Products" style="color: darkred; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:darkred; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:darkred; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>LEO SOFTWARE COMPANY</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <marquee><b>Rasing Software Developer</b></marquee>
                    <p style="color:purple; font-family:'Tahoma'; font-size:20px;"> This is the Official Website of our Software company!</p>
                    </div>
                    <p>Leading software developer <span style="background-color:rgb(235, 151, 207))">Nizso solutions</span>
                         GST Billing software | Supermarket software | Mobile shops | Restaurent management| And much more</p>
                    <br>
                <center>
                    <img src="/static/images/a.jpeg">
                    <img src="/static/images/b.jpeg">
                    <img src="/static/images/c.jpeg">
                    <img src="/static/images/d.jpg">
                    
                    
                </center>
                </div>
                <div class="footer">
                <footer style="color:white">
                Copyright &copy;2023 Developed by kabilan V</footer></div>
            </div>
        </div>
    </body>
</html>
```
## Stylecss
```
.home{
    height: 700px;
    width: 85%;
    border: 12px solid rgb(202, 147, 182);
    padding-left:10px;
    padding-right:10px;
    margin-left: auto;
    margin-right:auto;
    background-color:rgb(188, 220, 235);
}
.content{
    border:1px solid rgb(220, 188, 240)0, 0, 255);
    background-color: white;
    width:95%;
    height:400px;
    padding:10px;
    margin-left:auto;
    margin-right:auto;
}
.header{
    height: 128px;
    width:100%;
    background-image: url(/static/images/header.png);
    background-size: cover;
    
}
.logo{
    height:21%;
    width: 10%;
    position:absolute;
    background-image: url(/static/images/icon.png);
    background-size:cover;
    
}
.prod{
    height:auto;
    width:auto;
    position:relative;
    bottom:10px;
    left:550px;
    border:4px solid transparent;
    text-align:center;
    display: inline;
    padding:15px;
    font-family:'Algerian';
    font-size: large;  
}
.prod:hover{
    background-color:darkmagenta;
}
.people{
    height:auto;
    width:auto;
    position:relative;
    bottom:10px;
    left:700px;
    border:4px solid transparent;
    text-align:center;
    display: inline;
    padding:15px;
    font-family:'Algerian';
    font-size: large;  
}
.people:hover{
    background-color:darkmagenta;
}
.contact{
    height:20px;
    width:10%;
    position:relative;
    bottom:45px;
    left:1000px;
    border:4px solid transparent;
    text-align:center;
    padding:15px;
    font-family:'Algerian';
    font-size: large;  
}
.contact:hover{
    background-color:darkmagenta;
}
        
.h{
    height:20px;
    width:10%;
    position:relative;
    top:30px;
    left:200px;
    border:4px solid transparent;
    text-align:center;
    
    padding:15px;
    font-family:'Algerian';
    font-size: large;  
}
.h:hover{
    background-color:darkmagenta;
    overflow:hidden;
}
.footer{
    border:3px solid rgb(190, 233, 175));
    width:98%;
    height:6px;
    position:relative;
    bottom: 1px;
    background-color: darkmagenta;
    text-align:center;

}
.title{
    border:2px solid rgb(175, 236, 233);
    background-color:rgb(179, 255, 0);
    padding:1px;
    width:99.7%;
    height: 70px;
    text-align:center;
    font-family:'Alberian';
    margin-left:auto;
    margin-right: auto;
    
}
.content1{
    border:1px solid rgb(255, 0, 187);
    background-color: white;
    width:98%;
    height:100px;
    padding:10px;
    margin-left:auto;
    margin-right:auto;

}
```

## OUTPUT:
## Home
![Alt text](<Screenshot (71).png>) 
## People
![Alt text](<Screenshot (72).png>)
## Product 
![Alt text](<Screenshot (73).png>)
## Contact
![Alt text](<Screenshot (74).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
