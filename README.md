# Ex.06 Book Front Cover Page Design
## Date:18/05/2025

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
book.html
```
.
<html>

<head>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">

    <style>
        .space {
            width: 35%;
            height: 100%;
        }

        .first{
            position: absolute;
            top:49px;
            left: 530px;
            color: red;
            font-weight: 900;
            font-size: 32px;
            font-style: unset;
            line-height: 1.2;
            margin-bottom: 5px;
        }

        .second{
            position: absolute;
            top: 140px;
            left: 565px;
            color: white;
            font-style: italic;
            font-family: 'Montserrat', sans-serif;
            font-weight: 900;
            font-size: 35px;
            line-height: 1.2;
            margin-bottom: 5px;
        }

        .about{
            position: absolute;
            top: 160px;
            left: 550px;
            right: 540px;
            color: rgb(206, 41, 12);
            font-style: oblique;
            font-variant: normal;
            font-weight: lighter;
            font-family: none;
            font-size: 65px;
        }
        .fourth{
            position: absolute;
            top: 350px;
            left: 680px;
            right: 540px;
            color: white;
            font-style: italic;
            font-variant: normal;
            font-weight: lighter;
            font-family: none;
            font-size: 35px;
        }

        .edition {
            position: absolute;
            bottom: 80px;
            left: 520px;
            right: 600px;
            color:rgb(222, 237, 13);
            font-style: oblique;
            font-variant: normal;
            font-family: monospace;
            font-size: 20px;
        }
        .author{
            position: absolute;
            bottom: 30px;
            left: 520px;
            right: 600px;
            color: rgb(213, 47, 47);
            font-style: oblique;
            font-variant: normal;
            font-family: monospace;
            font-size: 20px;
        }
        .pub{
            position: absolute;
            bottom: 170px;
            right: 525px;
            left: 930px;
            color: rgb(143, 13, 125);
            font-style: oblique;
            font-variant: normal;
            font-family:monospace;
            font-size: 20px;
        }
        .kk
        {
            position: absolute;
            bottom: 220px;
            right: 500px;
            left: 900px;
            width: 6%;
        }

        .pub2{
            position: absolute;
            bottom: 145px;
            right: 525px;
            left: 880px;
            color: rgb(61, 199, 15);
            font-style: oblique;
            font-variant: normal;
            font-family:monospace;
            font-size: 20px;
        }
    </style>
    </style>

</head>

<body>
    <div class="cover">
        <center>
            <img src="cover image.png" class="space">
        </center>
        <center>
            <img src="ISAAC.jpg" class="kk">
        </center>
        <h1 class="first"><br>SAVEETHA Presents...</h1>
        <h2 class="second">A Course in</h2>
        <p class="about">
            ASSEMBLY LANGUAGE<br>
        </p>
        <h2 class="fourth">For Beginners</h2>
        <p class="edition">
            First Edition
        </p>
        <p class="author">
           ISAAC RAJA T
        </p>
        <p class="pub">
            SEC 
        </p>
        <p class="pub2">
            Publications
        </p>
    </div>
    </div>

</body>

</html>
```

## OUTPUT:
![alt text](image.png)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
