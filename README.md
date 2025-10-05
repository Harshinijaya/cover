# Ex.06 Book Front Cover Page Design
## Date:

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
```
<html>
  <head>
    <title>Book Cover</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body> 
    <div class="background">
      <div class="inner">
        <div class="title">
          <p>SEC Insights</p>
        <hr>
        <br><br>
        <h1 align="center">Cloud computing</h1>
        <br>
        <p class="sub">cloud performance,cloud resourse,cloud security and cloud automation</p>
      </div>
      <div class="footer">
        <div class="edition-section">
          <h3 class="edition">MY EDITION</h3>
          <img src="MY PIC (2).jpeg" class="image" alt="Author Photo">
        </div>
        <hr class="line">
        <div class="footer-text">
          <p class="left-text">J.HARSHINI</p>
          <p class="right-text">SAVEETHA ENGINEERING COLLEGE</p>
        </div>
      </div>
    </div>
  </div>
  </body>
</html>
style.css

body{
    display: flex;
    justify-content: center;
    color:violet
}
.background{
    height: 600px;
    width: 400;
    margin-top: 25px;
    background-image: url("background pic.jpeg");
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    position: relative;
    padding: 9px;
}
.inner{
    width:400px;
    height: 600px;
    border: 3px solid rgb(218,178,254)

}
.title{
    margin: 4px
}
.sub{
    font-size: large;
}
.footer{
    margin: 4px;
    position: absolute;
    bottom: 25px;
    left: 20px;
    right: 20px;
    display: flex;
    flex-direction: column;
    justify-content: flex-end;

}
.edition-section{
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
}
.image{
    width: 100px;
    height: auto;

}
.footer-text{
    display: flex;
    justify-content: space-between;
    font-weight: bold;
    font-size: 13px;
}

.left-text{
    text-align: left;
    font-size: large;

}
.right-text{
    text-align: right;
    font-size: large;
}
.line{
    width: 350px;
}
```

## OUTPUT:


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
