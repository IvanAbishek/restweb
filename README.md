# Ex.07 Restaurant Website
## Date:25/12/2025

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
home.html
```
<html>
<head>
    <title>The Velvet Flame</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="hotel">
    <div class="navbar">
        <a href="home.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </div>

    <h1 class="big-title">TheVelvetFlame</h1>
    <p class="subtitle"><b>TheVelvetFlame is a <u>world-renowned</u> luxury hotel chain known for its heritage, elegance, and exceptional hospitality.</b></p>
    <p class="subtitle"><i><b>Experience <u>timeless</u> elegance and fine dining.</b></i></p>

    <div class="entry">
        <img src="Velvetflame.png" width="500" height="400">    
    </div>
    <div class="entry2">
        <img src="interior.jpg" width="500" height="400">
    </div>
    <div class="entry3">
        <img src="Screenshot 2025-12-28 131351.png" width="500" height="400">
    </div>

    <div class="footer">
    <footer>
        <b>&copy; Ivan Abishek Benhannan | 25006144 | Saveetha Engineering college</b>
    </footer>
    </div>

</div>

</body>
</html>
```
menu.html
```
<html>
<head>
    <title>Menu - Taj</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="hotel">
    <div class="navbar">
        <a href="home.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </div>

    <h1 class="big-title">MENU</h1>

    <div class="card-container">
        <div class="card">
            <img src="jm-23.jpeg" alt="iberico ham">
            <h3>iberico ham</h3>
            <p>Rs. 350</p>
        </div>

        <div class="card">
            <img src="Lobster-Thermidor-14.webp" alt="Lobster Thermidor">
            <h3>Lobster Thermidor</h3>
            <p>Rs. 420</p>
        </div>

        <div class="card">
            <img src="mush.jpg" alt="Mushroom Soup">
            <h3>Mushroom Soup</h3>
            <h5 align="center">Rs. 500</h5>
        </div>
        <div class="card">
            <img src="cof.jpg" alt="Coffee">
            <h3>coffee</h3>
            <p>Rs. 30</p>
        </div>
        <div class="card">
            <img src="beluga-caviar-recipes.webp" alt="Beluga Caviar">
            <h3>Beluga Caviar</h3>
            <p>Rs. 1000</p>
        </div>
        </div>
</div>

<footer>
&copy; Ivan Abishek Benhannan | 25006144 | Saveetha Engineering college
</footer>

</body>
</html>

```
admin.html
```
<html>
<head>
    <title>Administration</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="hotel">
    <div class="navbar">
        <a href="home.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </div>

    <h1 class="big-title">ADMINISTRATION TEAM</h1>

    <div class="card-container">
        <div class="card">
            <img src="me.png" alt="CEO">
            <h3>Mr. Ivan Abishek Benhannan</h3>
            <p>CEO</p>
        </div>

        <div class="card">
            <img src="emma watson.jpg" alt="Executive Manager">
            <h3>Ms. Emma Watson</h3>
            <p>Executive Manager</p>
        </div>
        <div class="card">
            <img src="andrew tate.jpg" alt="Marketing Manager">
            <h3>Mr. Andrew Tate</h3>
            <p>Marketing manager</p>
        </div>
        <div class="card">
            <img src="messi.jpg" alt="Operations Manager">
            <h3>Mr. Lionel Messi</h3>
            <p>Operations Manager</p>
        </div>
        <div class="card">
            <img src="gordon.jpg" alt="Executive Chef">
            <h3>Gordon Ramsay</h3>
            <p>Executive Chef</p>
        </div>
        <div class="card">
            <img src="Asala.jpeg" alt="Customer Service">
            <h3>Asala</h3>
            <p>Customer Service</p>
        </div>
        

        </div>
    </div>
</div>

<footer>
&copy; Ivan Abishek Benhannan | 25006144 | Saveetha Engineering college
</footer>

</body>
</html>

```
contact.html
```
<html>
<head>
    <title>Contact</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="hotel">
    <div class="navbar">
        <a href="home.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </div>

    <h1 class="big-title">CONTACT</h1>

    <p class="subtitle">Visit us at:</p>
    <p>
    The Velvet Flame<br>
842 Sunset Crest Drive,
West Hollywood,
Los Angeles, CA 90069, USA<br>
    </p>

    <br>

    <p class="subtitle">Phone:</p>
    <p>+1 (424) 555-9176(CEO)<br>

+1 (310) 555-4821(Executive Chef)

    </p>

    <br>

    <p class="subtitle">Email:</p>
    <p>Velvetflame@gmail.com</p>
</div>
<div class="exit">
    <img src="Velvetflame.png" width="500" height="400">
</div>

<footer>
&copy; Ivan Abishek Benhannan | 25006144 | Saveetha Engineering college
</footer>

</body>
</html>

```
style.css
```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    background-color: #000;
    color: #fff;
}

.navbar {
    position: absolute;
    top: 20px;
    right: 20px;
    background: rgba(3, 3, 3, 0.986);
    padding: 12px 30px;
    border: 2px solid #000;
    border-radius: 30px;
}

.navbar a {
    margin: 20px;
    text-decoration: none;
    color: white;
    font-weight: bold;
    font-size: 18px;
}


.hotel {
    height: 100vh;
    background: url("taj.jpg") no-repeat center/cover;
    padding: 80px 60px;
}

.big-title {
    box-shadow: 2px 2px 8px #000;
    font-size: 70px;
    color: rgb(34, 33, 33);
    letter-spacing: 3px;
}

.subtitle {
    margin-top: 10px;
    font-size: 20px;
    color: black;
}


.card-container {
    display: flex;
    gap: 70px;
    padding: 150px;
    margin-top: 50px;
}

.card {
    position: relative;
    background: rgb(231, 221, 221);
    color: #000;
    padding: 20px;
    width: 200px;
    border-radius: 10px;
    text-align: center;
    gap: 100px;
}

.card img {
    width: 100%;
    height: 200px;
    border-radius: 10px;
}

.entry {
    position: relative;
    left: 45px;
    bottom: -35px;
    background: rgb(231, 221, 221);
    color: #000;
    padding: 15px;
    width: 550px;
    border-radius: 10px;
    right: 350px;
}

.entry2 {
    position: relative;
    left: 610px;
    bottom: 395px;
    background: rgb(231, 221, 221);
    color: #000;
    padding: 15px;
    width: 550px;
    border-radius: 10px;

}

.entry3 {
    position: relative;
    left: 1175px;
    bottom: 825px;
    background: rgb(231, 221, 221);
    color: #000;
    padding: 15px;
    width: 550px;
    border-radius: 10px;
}

.exit {
    position: relative;
    left: 700px;
    bottom: 650px;
    background: rgb(231, 221, 221);
    color: #000;
    padding: 15px;
    width: 530px;
    border-radius: 15px;
}

footer {
    position: relative;
    width: 100%;
    margin: 0;
    padding: 15px;
    box-sizing: border-box;
    text-align: center;
    bottom: 470px;
    color: white;
    background: black;
}
```
## OUTPUT:
<img width="1919" height="961" alt="Screenshot 2025-12-28 164710" src="https://github.com/user-attachments/assets/84963744-7e13-4f71-80da-c438fd2854a0" />

<img width="1917" height="964" alt="Screenshot 2025-12-28 164726" src="https://github.com/user-attachments/assets/e363fcb5-640f-4a7f-9f7a-21d7c2185c7b" />

<img width="1897" height="966" alt="Screenshot 2025-12-28 164745" src="https://github.com/user-attachments/assets/9f5e8de5-e065-4921-af2e-31275bfbdd1c" />

<img width="1919" height="966" alt="Screenshot 2025-12-28 164815" src="https://github.com/user-attachments/assets/3e459644-7ec4-420f-8278-bb2e647523fe" />





## RESULT:
The program for designing restaurant website using HTML and CSS is completed successfully.
