# Ex.07 Restaurant Website
## Date:07.10.2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

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
home.html

<html>
    <head>
        <title>Home</title>
        <link rel="stylesheet" href="style1.css">
    </head>
    <body>
        <div class="background">
        <div class="contents">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
        <div class="restname">
            <h4><b>TRADITIONAL INDIAN RESTAURANT</b></h4>
        </div >
        <div class="line">
            The tradition of tamilnadu
        </div>
        <div class="lines">
            <i>"In every bite the taste stands in the tongue"</i>
            <p>the traditon and the healthy foods are served</p>
        
        <div class="image2">
            <img src="back.png" width="600" height="300">
        </div>
        <footer class="copyrights">
            &copy; P.Dharshini-25010127
        </footer>
        </div>
    </body>
</html>

style1.css
.background {
    width: 1350px;
    height: 650px;
    color:whitesmoke;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family:Arial, Helvetica, sans-serif;
    background-image: url(front.png);
    background-size: cover;
}

.contents {
    width: 550px;
    height: 25px;
    border:2px solid black;
    padding: 10px;
    background-color: aliceblue;
    text-align: center;
    top: 5px;
    left: 700px;
    position: relative;
    word-spacing: 40px;
}

.restname {
    color: paleturquoise;
    font-family: Verdana;
    text-align: left;
    position: relative;
    font-size: 300%;
    top: -50px;
}

.line {
    color:pink;
    font-family: Verdana;
    text-align: left;
    position: relative;
    font-size: 250%;
    top: -120px;
    left: 10px;
}

.lines {
    color: pink;
    font-family: Verdana;
    text-align: center;
    position: relative;
    font-size: 130%;
    top: -100px;
}



.image2 {
    position: relative;
    top: -1px;
    left: 80px;
    background-size:contain;
}

.copyrights{
    width: 1510px;
    height: 30px;
    background-color:black;
    text-align: center;
    top: -1px;
    left: -20px;
    position: relative;
}

 menu.html
 <html>
    <head>
        <title>Home</title>
        <link rel="stylesheet" href="style2.css">
    </head>
    <body>
        <div class="background">
        <div class="contents">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
        <div class="menu">
            <h1><b>MENU</b></h1>
        </div >
        <div class="menugrid">
            <div class="menuitem">
                <img src="idly.png" width="300" height="150">
                <h1>idly</h1>
                <p>Rs. 5</p>
            </div>
            <div class="menuitem">
                <img src="dosa.png" width="300" height="150">
                <h1>dosa</h1>
                <p>Rs. 10</p>
            </div>
            <div class="menuitem">
              <img src="poori.png" width="300" height="150">
                <h1>poori</h1>
                <p>Rs. 20</p>
            </div>
            <div class="menuitem">
                <img src="vadai.png" width="300" height="150">
                <h1>vadai</h1>
                <p>Rs. 20</p>
            </div>
            <div class="menuitem">
                <img src="chickenbiriyani.png" width="300" height="150">
                <h1>chicken biriyani</h1>
                <p>Rs. 100</p>
            </div>
            <div class="menuitem">
                <img src="muttonbiriyani.png" width="300" height="150">
                <h1>mutton biriyani</h1>
                <p>Rs. 200</p>
            </div>
            <div class="menuitem">
                <img src="prawngravy.png" width="300" height="150">
                <h1>prawn gravy</h1>
                <p>Rs. 150</p>
            </div>
            <div class="menuitem">
                <img src="crabgravy.png" width="300" height="150">
                <h1>crab gravy</h1>
                <p>Rs. 150</p>
            </div>
        </div>
        <footer class="copyrights">
            &copy; P.Dharshini-25010127
        </footer>
        </div>
    </body>
</html>

style2.css
.background {
    width: 1350px;
    height: 650px;
    color:black;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family:Arial, Helvetica, sans-serif;
    background-image: url(background.png);
    background-size: cover;
}

.contents {
    width: 500px;
    height: 25px;
    border: 2px solid black;
    padding: 10px;
    background-color: aliceblue;
    text-align: center;
    top: 5px;
    left: 800px;
    position: relative;
    word-spacing: 70px;
}
menu {
    color: paleturquoise;
    font-family: Verdana;
    text-align: left;
    position: relative;
    font-size: 300%;
    top: 10px;
}

.menugrid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(90px, 1fr));;
    gap: 50px;
    justify-items: center;
    padding: 20px;
    margin-top: -50px;
}

.menuitem {
    background-color: beige;
    border-radius: 10px;
    text-align: center;
    padding: 20px;
    width: 100%;
}

.menuitem img {
  border-radius: 10px;
    width: 100%;
    height: 180px;
    object-fit: cover;
}

.menuitem h1 {
    font-size: 1.5em;
    color: black;
    margin-top: 15px;
}

.menuitem p {
    color: black;
    margin-bottom: 0px;
}

.copyrights{
    width: 1200px;
    height: 20px;
    background-color: gray;
    text-align: center;
    top: 100px;
    left: -20px;
    position: relative;
}

admin.html
<html>
    <head>
        <title>Home</title>
        <link rel="stylesheet" href="style3.css">
    </head>
    <body>
        <div class="background">
        <div class="contents">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
        <div class="admin">
            <h1><b>ADMINISTRATION TEAM</b></h1>
        </div>
        <div class="admingrid">
            <div class="adminlist">
                <div class="admingrid">
            <div class="adminlist">
                <img src="dharshini.jpg" width="130" height="250">
                <h1><P>P.Dharshini</P></h1>
                <p class="post">CEO</p>
            </div>
            <div class="adminlist">
                <img src="nayan.png" width="130" height="250">
                <h1>nayan</h1>
                <p class="post">Marketer</p>
            </div>
            <div class="adminlist">
                <img src="surya.png" width="130" height="250">
                <h1>surya</h1>
                <p class="post">Operator</p>
            </div>
            <div class="adminlist">
                <img src="virat.png" width="130" height="250">
                <h1>virat</h1>
                <p class="post">HR</p>
            </div>
            <div class="adminlist">
                <img src="sk.png" width="130" height="250">
                <h1>sk</h1>
                <p class="post">Chef</p>
            </div>
            <div class="adminlist">
                <img src="samantha.png" width="100" height="200">
                <h1>samantha</h1>
                <p class="post">Service Manager</p>
            </div>
        </div>
        <footer class="copyrights">
            &copy; P.Dharshini-25010127
        </footer>
        </div>
    </body>
</html>

style3.css
.background {
    width: 1350px;
    height: 650px;
    color:black;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family:Arial, Helvetica, sans-serif;
    background-image: url(backadmin.png);
    background-size: cover;
}

.contents {
    width: 500px;
    height: 25px;
    border: 2px solid black;
    padding: 5px;
    background-color:goldenrod;
    text-align: center;
    top: 5px;
    left: 830px;
    position: relative;
    word-spacing: 70px;
}
.admin {
    color:black;
    font-family: Verdana;
    text-align: left;
    position: relative;
    font-size: 300%;
    top: -50px;
}

.admingrid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(90px, 1fr));;
    gap: 50px;
    justify-items: center;
    padding: 20px;
    margin-top: -90px;
}

.adminlist{
    background-color: beige;
    border-radius: 10px;
    text-align: center;
    padding: 20px;
    width: 100%;
}
.adminlist img {
    border-radius: 10px;
    width: 100%;
    height: 250px;
    object-fit: cover;
    border-radius: 50% / 35%;
}

.adminlist h1 {
    font-size: 1.5em;
    color: black;
    margin-top: 15px;
}

.adminlist p {
    color: black;
    margin-bottom: 0px;
}

.copyrights {
    width: 1510px;
    height: 20px;
    background-color: gray;
    text-align: center;
    top: 30px;
    left: -20px;
    position: relative;
}

contact.html
<html>
    <head>
        <title>Home</title>
        <link rel="stylesheet" href="style4.css">
    </head>
    <body>
        <div class="background">
        <div class="contents">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
        <div class="contact">
            <h1><b>CONTACT</b></h1>
        </div>
        <div class="info">
            <h1>Visit us at:</h1>
            <p>The traditional indian restaurant<br>17-1-3/2,<br>kirungakotai road ,singampunari<br>Tamilnadu,India</p>
            <h1>Phone:</h1>
            <p>+91 7868931347</p>
             <h1>Email ID:</h1>
            <p>traditional@gmail.com</p>
        </div>
        <footer class="copyrights">
            &copy; P.Dharshini-25010127
        </footer>
        </div>
    </body>
</html>

style4.css
.background {
    width: 1300px;
    height: 750px;
    color:black;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family:Arial, Helvetica, sans-serif;
    background-image: url(backcontact.png);
    background-size: cover;
}
.contents {
    width: 500px;
    height: 25px;
    border: 2px solid black;
    padding: 10px;
    background-color: aliceblue;
    text-align: center;
    top: 20px;
    left: 750px;
    position: relative;
    word-spacing: 70px;
}

.contact {
    color:pink;
    font-family: Verdana;
    text-align: center;
    position: relative;
    font-size: 300%;
    top: -50px;
}
.info {
    color: whitesmoke;
    font-family:Arial, Helvetica, Verdana, Geneva, Tahoma, sans-serif;
    position: relative;
    text-align:center;
    top: -70px;
    left: 50;
}
.copyrights{
    width: 1300px;
    height: 20px;
    background-color:pink;
    text-align: center;
    top: -50px;
    left: -15px;
    position: relative;
}
```

## OUTPUT:
![alt text](<Screenshot (209).png>)
![alt text](<Screenshot (210).png>)
![alt text](<Screenshot (211).png>)
![alt text](<Screenshot (212).png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
