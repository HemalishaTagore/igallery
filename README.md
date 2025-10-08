# Ex.08 Design of Interactive Image Gallery
## Date: 08/10/2025

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
gallery.html
<html>
<head>
    <title>GALLERY</title>
    <link rel="stylesheet" href="gallery.css">
    <script src="gal.js"></script>
</head>
<body>
    <h1>PHOTO GALLERY - HEMALISHA T(25017673)</h1>
    <div class="gallery">
        <div class="galleryitem">
            <img class="zoom" src="dharshan raval.jpg" onmouseover="mousein(this)" onmouseout="mouseout(this)">
        </div>
        <div class="galleryitem">
            <img class="zoom" src="dr.jpg" onmouseover="mousein(this)" onmouseout="mouseout(this)">
        </div>
        <div class="galleryitem">
            <img class="zoom" src="zayn malik.jpg" onmouseover="mousein(this)" onmouseout="mouseout(this)">
        </div>
        <div class="galleryitem">
            <img class="zoom" src="dq.jpg" onmouseover="mousein(this)" onmouseout="mouseout(this)">
        </div>
        <div class="galleryitem">
            <img class="zoom" src="tharun naik.jpg" onmouseover="mousein(this)" onmouseout="mouseout(this)">
        </div>
    </div>
    <footer class="copyrights">
        &copy; Image gallery | HEMALISHA_TAGORE 
    </footer>
</body>
</html>

gallery.css

body {
    background-color: rgb(3, 95, 118);
    text-align: center;
    margin-top: 50px;
}
body h1{
    color: #ebcd95
}

.gallery {
    display: flex;
    gap: 20px;
    padding-top: 50px;
    justify-content: center;;
}

.galleryitem {
    cursor: pointer;
    text-align: center;
    width: 180px;
    padding: 20px;
}

.galleryitem img {
    width: 230px;
    height: 300px;
}

.copyrights{
    width: 1510px;
    height: 20px;
    text-align: center;
    top: 130px;
    left: -20px;
    position: relative;
}

gal.js

function mousein(img) {
    img.style.width = "230px";
    img.style.height = "320px";
}

function mouseout(img) {
    img.style.width = "210px";
    img.style.height = "280px";
}
```

## OUTPUT:
![alt text](<Screenshot (51)-1.png>) 
![alt text](<Screenshot (52)-1.png>)

## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.