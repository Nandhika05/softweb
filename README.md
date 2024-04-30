# Ex.07 Software Product Company Website
## Date:30:04:24

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
```
##web.html
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>CodeArt</title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: 'Courier New', Courier, monospace;
                        }
            .banner {
                width: 100%;
                height: 100vh;
                background-size: cover;
                background-position: center;
		background-color:yellow;
            }
            .navbar {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color:rgb(125, 211, 233);
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: rgb(154, 236, 236);
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: black;
            } 
            ::placeholder {
                color: black;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color:black;
                border-radius: 10px;
                background:rgb(130, 195, 225);
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: black;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: black;
                background-color:rgb(34, 240, 255);
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .content {
                position: absolute;
                top: 50%;
                left: 50%;
                transform: translate(-50%,-50%);
                text-align: center;
            }
            .text h2 {
                color: rgb(147, 205, 232);
                font-weight: 800;
                font-size: 50px;
                letter-spacing: 3px;
            }
	    .text h3 {
                color: black;
                font-weight: 800;
                font-size: 22px;
                letter-spacing: 3px;
            }
	
            .text p {
                color: black;
                text-transform: capitalize;
                font-size: 17px;
                margin-bottom: 30px;
                word-spacing: 2px;
                letter-spacing: 1px;
	
            }
                footer {
                background-color: rgb(218, 25, 25);
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo"><span>Code Marathon</span></h1>
            <ul>
                <li><a href="web.html"> Home </a></li>
                <li><a href="Products.html"> Products </a></li>
                <li><a href="people.html"> People </a></li>
                <li><a href="contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="content">
            <div class="text">
                <h2><span> Technology Stack Market</span></h2>
                <br>
		<h3>Welcome to Code Marathon ,where you find your inovative skills in coding.</h3>
		<br>
                <p>Our experts have extensively tested the top web design and other coding language platforms on the market. Now we have shortlisted the best, creating this guide to help you find the one that meets your needs, abilities, and budget. Join us at Code Marathon and unleash your creativity in the world of code!</p>
                <br>
                
            </div>
        </div>  
    </div>
    <footer>
        <center> Copyright@2024 Developed by NANDHIKA P </center>
    </footer>
</body>
</html>

##product
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>CodeArt</title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: 'Courier New', Courier, monospace;
                        }
            .banner {
                width: 100%;
                height: 100vh;
                background-size: cover;
                background-position: center;
		background-color:rgb(89, 195, 230);
            }
            .navbar {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color:gold;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: yellow;
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } 
            ::placeholder {
                color: white;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color:black;
                border-radius: 10px;
                background:gold;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color:gold;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .container {
                background: transparent;
                padding: 10px 5%;
                padding-bottom: 100px;
            }
            .container .box-container {
                display: grid;
                grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
                gap: 20px;
            }
            .container .box-container .box {
                color: white;
                box-shadow: 0 5px 10px rgba(0,0,0,.2);
                border-radius: 10px;
                background: transparent;
                border: 1px solid white;
                padding: 10px 5px;
            }
            .container .box-container .box img {
                height: 50px;
                border-radius: 20px;
            }
            .container .box-container .box h3 {
                color: gold;
                font-size: larger;
                padding: 10px 0;
            }
            .container .box-container .box p {
                color: white;
                font-size: larger;
                line-height: 1.5;
            }
            footer {
                background-color: rgb(209, 20, 20);
                margin-top: auto;
            }
        </style>
    </head>
<body background="image.webp">
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo"><span> Code Marathon</span></h1>
            <ul>
                <li><a href="homepage.html"> Home </a></li>
                <li><a href="Products.html"> Products </a></li>
                <li><a href="person.html"> People </a></li>
                <li><a href="contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="container">
            <div class="box-container">
                <div class="box">
                    <img src="java.jpeg" alt="">
                    <h3>Java</h3>
                    <p>Java is a high-level, class-based, object-oriented programming language that is designed to have as few implementation dependencies as possible.</p>
                </div>

                <div class="box">
                    <img src="Python.jpeg" alt="">
                    <h3>Python</h3>
                    <p> It is often used to build websites and software, automate tasks, and analyze data.Where the world simplicity meets the power of programming . </p>
                </div>
                <div class="box">
                    <img src="dev c++.jpeg"alt="">
                    <h3>Dev C++</h3>
                    <p>Dev-C++ is a free full-featured integrated development environment distributed under the GNU General Public License for programming in C and C++. </p>
                </div>
               
                <div class="box">
                    <img src="javascripts.png" alt="">
                    <h3>Javascript</h3>
                    <p> JS is a core technology of the Web, alongside HTML and CSS. 99% of websites use JavaScript on the client side for webpage behavior. Web browsers have a dedicated JavaScript engine that executes the client code. a server scripting language, and a powerful tool for making dynamic and interactive Web pages. </p>
                </div>
                <div class="box">
                    <img src="sql.jpg" alt="">
                    <h3>SQL</h3>
                    <p>Structured Query Language is a domain-specific language used to manage data, especially in a relational database management system. It is particularly useful in handling structured data.</p>
                </div>
 
            </div>
        </div>
    </div>
    <footer>
        <center> Copyright@2024 Developed by NANDHIKA P </center>
    </footer>
</body>
</html>
## people
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>CodeArt</title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: 'Courier New', Courier, monospace;
                        }
            .banner {
                width: 100%;
                height: 100vh;
                background-size: cover;
                background-position: center;
		background-color:rgb(97, 195, 248);
            }
            .navbar {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color:gold;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: yellow;
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } 
            ::placeholder {
                color: white;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color:black;
                border-radius: 10px;
                background:gold;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color:gold;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .image {
                position: relative;
                border: 0;
                top: 70px;
                background: transparent;
            }
            .image table {
                border: 0;
                color: white;
                position: relative;
                left: 200px;
            }
            .image table img {
                height: 250px;
                width: 250px;
                border: 2px solid yellow;
                padding: 5px;
                border-radius: 50%;
            }
            .image table td {
                color: yellow;
            }
            footer {
                background-color: rgb(183, 19, 19);
                margin-top: auto;
            }
        </style>
    </head>
<body background="image.webp">
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo"><span>Code Marathon</h1>
            <ul>
                <li><a href="homepage.html"> Home </a></li>
                <li><a href="Products.html"> Products </a></li>
                <li><a href="person.html"> People </a></li>
                <li><a href="contact.html"> Contact </a></li>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div> 
        <div class="image">
            <table cellspacing="20"> 
                <tr align="center">
                    <td> <img src="me.jpg"> </td>
                    <td> <img src="krithik.png"> </td>
                    <td> <img src="mom.jpg"> </td>
                    <td> <img src="eomma.jpg"> </td>
                    
                </tr>
                <tr align="center">
                    <th>NANDHIKA</th>
                    <th>krithik</th>
                    <th>RUBINI</th>
                    <th>JOTHI</th>
                   
                </tr>
                <tr align="center">
                    <td> CEO </td>
                    <td> CEO, Co-Founder </td>
                    <td> CTO, Co-Founder </td>
                    <td> Director </td>
                    
                </tr>
            </table>
        </div>
    </div>
    <footer>
        <center> Copyright@2024 Developed by NANDHIKA P</center>
    </footer>
</body>
</html>

##contact
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>CodeArt</title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: 'Courier New', Courier, monospace;
                        }
            .banner {
                width: 100%;
                height: 100vh;
                background-size: cover;
                background-position: center;
		background-color:yellow;
            }
            .navbar {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color:rgb(7, 8, 8);
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: black;
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: rgb(118, 204, 219);
            } 
            ::placeholder {
                color: black;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color:black;
                border-radius: 10px;
                background:rgb(99, 166, 192);
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: black;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: black;
                background-color:rgb(108, 144, 199);
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .box {
                display: flex;
                column-gap: 40px;
                background: transparent;
                position: relative;
                top: 50px;
            }
            .box-1 {
                height: 400px;
                width: 400px;
                border: 3px solid black;
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 250px;
            }
            .box-2 {
                height: 400px;
                width: 400px;
                border: 3px solid rgb(96, 175, 223);
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 300px;
            }
            .box-1 form {
                display: flex;
                color: black;
                background: transparent;
                padding: 10px;
                font-size: 15px;
                position: relative;
                top: 15px;
            }
            .box-1 form input {
                background: transparent;
                display: flex;
                border: 1px solid black;
                border-radius: 10px;
                padding: 15px 30px;
                font-size: 15px;
                color: black;
                position: relative;
                top: 30px;
            }
            .box-1 form textarea {
                background: transparent;
                color: black;
                padding: 15px 10px;
                position: relative;
                top: 30px;
                left: 15px;
                border: 1px solid black;
                border-radius: 10px;
            }
            .box-1 form button {
                border: 0;
                outline: none;
                padding: 10px 20px;
                color: black;
                border-radius: 30px;
                background: rgb(122, 175, 225);
                cursor: pointer;
                position: relative;
                top: 50px;
            }
            .box-2 h2 {
                color: black;
                position: relative;
                top: 25px;
                left: 50px;
                font-size: 30px;
            }
            .box-2 p {
                color: black;
                position: relative;
                top: 50px;
                
                padding: 10px 80px;
            }
            .box-2 span {
                color: rgb(116, 176, 225);
                font-size: 30px;
            }
            footer 
            {
                background-color: red;
                margin-top: auto;
            }
        </style>
    </head>
<body background="image.webp">
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo"><span> Code Marathon</span></h1>
            <ul>
                <li><a href="homepage.html"> Home </a></li>
                <li><a href="Products.html"> Products </a></li>
                <li><a href="person.html"> People </a></li>
                <li><a href="contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="box">
            <div class="box-1">
                <form>
                    <center>
                        <h1> <span>Contact Us </span></h1>
                        <input type="text" placeholder="Your Name">
                        <br>
                        <input type="email" placeholder="Your Email">
                        <br>
                        <textarea rows="4" cols="30" placeholder="Your Message"> </textarea>
                        <br>
                        <button type="submit"> Submit </button>
                    </center>
                </form>
            </div>
            <div class="box-2"> 
                <h2> Contact Information</h2>
                <p><span> Address</span>: NO,22/1A,Gandhi Main Road,Kanchipuram-631502 </p>
                <p> <span>Email</span> : codemarathon@gmail.com</p>
                <p> <span>Phone</span>: 044 7354 6921 </p>
            </div>
        </div>
    </div>
    <footer>
        <center> Copyright@2024 Developed by NANDHIKA P  </center>
    </footer>
</body>
</html>
```
## OUTPUT:
![Screenshot 2024-04-30 082705](https://github.com/Nandhika05/softweb/assets/154419402/6b1113cf-8ac8-4721-af2f-e8b01d58109a)

![Screenshot 2024-04-30 082814](https://github.com/Nandhika05/softweb/assets/154419402/5965d5d8-2a0c-49f7-a415-4fb36117ed01)

![Screenshot 2024-04-30 082836](https://github.com/Nandhika05/softweb/assets/154419402/23d4b956-5f6d-438e-a411-38a01b06a2a7)

![Screenshot 2024-04-30 082605](https://github.com/Nandhika05/softweb/assets/154419402/a0f9bd98-0a3f-44dd-873e-f7eda599b664)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
