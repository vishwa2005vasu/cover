# Ex.06 Book Front Cover Page Design
## Date:11.04.2024
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
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            color:rgb(73, 12, 113);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url("Untitled design_page-0001.jpg");
            background-size: cover;
        }
            

        .insight{
            color: rgb(22, 14, 132);

        }

        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: rgb(208, 216, 211);
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color: rgb(15, 80, 134);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            font-family:Tahoma;
            font-size: medium;
            position: relative;
            top:60px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: red;">
            </div>
            <div class="booktitle">
                <h1>LEARNING WEB DESIGN</h1></div>
            <div class="subtitle">
                A Beginner's Guide To HTML,CSS,Javascript and Web Graphics
            </div>
            <div class="mypic">
                <img src="vishwa.jpg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: rgb(208, 255, 0);">
            </div>
            <div class="author">
               <p><b>VISHWA VASU R</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Third Edition</b>
            </div>
        </div>
    </body>
</html>
```
## OUTPUT:
![Alt text](<sam/Screenshot 2024-04-11 140622.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
