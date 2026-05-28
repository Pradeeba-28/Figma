# Ex09 Event Registration Web Application
## Date:27-05-2026

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
Page 1:
html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Page</title>
    <link rel="stylesheet" href="page1.css">
</head>
<body>

    <div class="phone-container">

        <img src="logo.png" class="logo">

        <h2>SIGN UP / LOG IN</h2>

        <div class="form-group">
            <label>EMAIL ID:</label>
            <input type="text">
        </div>

        <div class="form-group">
            <label>PASSWORD:</label>
            <input type="password">
        </div>

        <button>SUBMIT</button>

        <p class="trouble">FACING TROUBLE?</p>

        <a href="#">CONTACT US</a>

    </div>

</body>
</html>
```
css
```
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
}

body{
    background:black;
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
}

.phone-container{
    width:393px;
    height:822px;
    background-image:url('bg.jpg');
    background-size:cover;
    background-position:center;
    padding:40px 25px;
    color:white;
}

.logo{
    width:120px;
    display:block;
    margin:30px auto 20px;
}

h2{
    text-align:center;
    margin-bottom:100px;
}

.form-group{
    margin-bottom:40px;
}

label{
    font-weight:bold;
    margin-right:10px;
}

input{
    width:180px;
    height:30px;
    border:none;
    border-radius:10px;
    background:#d9d9d9;
}

button{
    display:block;
    margin:80px auto 40px;
    background:red;
    color:white;
    border:none;
    padding:10px 30px;
    border-radius:10px;
    cursor:pointer;
}

.trouble{
    text-align:center;
    margin-top:30px;
    font-weight:bold;
}

a{
    display:block;
    text-align:center;
    margin-top:20px;
    color:red;
    text-decoration:none;
    font-weight:bold;
}
```
Page 2:
html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Events Page</title>
    <link rel="stylesheet" href="page2.css">
</head>
<body>

    <div class="phone-container">

        <h1>EVENTS</h1>

        <ul>
            <li>CHESS</li>
            <li>CRICKET</li>
            <li>VOLLEYBALL</li>
            <li>ARCHERY</li>
            <li>KHO - KHO</li>
            <li>HACKATHON</li>
            <li>WORKSHOPS</li>
            <li>VLSI DESIGNING</li>
            <li>PRESENTATION</li>
            <li>DEBATE</li>
        </ul>

        <h3>CLICK TO REDIRECT</h3>

        <p class="fun">FUN GUARANTEED EVENTS!</p>

        <a href="#">CONTACT US</a>

    </div>

</body>
</html>
```
css
```
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
}

body{
    background:black;
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
}

.phone-container{
    width:393px;
    height:822px;
    background-image:url('bg.jpg');
    background-size:cover;
    background-position:center;
    padding:40px 25px;
    color:white;
}

h1{
    text-align:center;
    margin-top:20px;
    margin-bottom:60px;
    font-size:42px;
}

ul{
    list-style:none;
    line-height:2;
    font-size:24px;
    font-weight:bold;
}

h3{
    text-align:center;
    margin-top:80px;
}

.fun{
    text-align:center;
    margin-top:100px;
    font-weight:bold;
    font-size:20px;
}

a{
    display:block;
    text-align:center;
    margin-top:40px;
    color:red;
    text-decoration:none;
    font-weight:bold;
}
```
Page 3:
html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Details</title>
    <link rel="stylesheet" href="page3.css">
</head>
<body>

    <div class="phone-container">

        <h1>PERSONAL DETAILS</h1>

        <div class="form-group">
            <label>NAME:</label>
            <input type="text">
        </div>

        <div class="form-group">
            <label>GENDER:</label>
            <input type="text">
        </div>

        <div class="form-group">
            <label>REGISTER NO:</label>
            <input type="text">
        </div>

        <div class="form-group">
            <label>DEPARTMENT:</label>
            <input type="text">
        </div>

        <div class="form-group">
            <label>YEAR:</label>
            <input type="text">
        </div>

        <div class="form-group">
            <label>PHONE NO:</label>
            <input type="text">
        </div>

        <div class="form-group">
            <label>EMAIL ID:</label>
            <input type="email">
        </div>

        <button>SUBMIT</button>

        <a href="#">CONTACT US</a>

    </div>

</body>
</html>
```
css
```
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
}

body{
    background:black;
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
}

.phone-container{
    width:393px;
    height:822px;
    background-image:url('bg.jpg');
    background-size:cover;
    background-position:center;
    padding:40px 25px;
    color:white;
}

h1{
    text-align:center;
    margin-top:30px;
    margin-bottom:80px;
    font-size:32px;
}

.form-group{
    margin-bottom:28px;
}

label{
    font-size:22px;
    font-weight:bold;
    margin-right:10px;
}

input{
    width:160px;
    height:28px;
    border:none;
    border-radius:10px;
    background:#d9d9d9;
}

button{
    display:block;
    margin:80px auto 40px;
    background:red;
    color:white;
    border:none;
    padding:12px 40px;
    font-size:20px;
    cursor:pointer;
}

a{
    display:block;
    text-align:center;
    margin-top:40px;
    color:red;
    text-decoration:none;
    font-weight:bold;
}
```
Page 4:
html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Success Page</title>
    <link rel="stylesheet" href="page4.css">
</head>
<body>

    <div class="phone-container">

        <h1>
            EVENT <br>
            REGISTRATION <br>
            IS <br>
            SUCCESSFUL
        </h1>

        <div class="tick">✔</div>

        <p>
            DETAILS ARE SENT TO <br>
            YOUR EMAIL
        </p>

        <a href="#">CONTACT US</a>

    </div>

</body>
</html>
```
css
```
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
}

body{
    background:black;
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
}

.phone-container{
    width:393px;
    height:822px;
    background-image:url('bg.jpg');
    background-size:cover;
    background-position:center;
    padding:40px 25px;
    color:white;
    text-align:center;
}

h1{
    margin-top:180px;
    font-size:38px;
    line-height:1.5;
}

.tick{
    font-size:70px;
    color:lime;
    margin-top:40px;
}

p{
    margin-top:80px;
    font-size:22px;
    font-weight:bold;
    line-height:1.5;
}

a{
    display:block;
    margin-top:180px;
    color:red;
    text-decoration:none;
    font-weight:bold;
    font-size:22px;
}
```

## OUTPUT:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7e689b6c-cbcc-49cc-bceb-9273eebc1227" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1bd55221-4fc5-4a1e-bbbb-d469ab18c758" />



## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
