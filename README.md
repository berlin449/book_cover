# Ex.06 Book Front Cover Page Design
# Date:
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
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
           color:rgb(236, 24, 24);
           margin-left: auto;
           margin-right: auto;
           padding: 20px;
           font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
           background-size: cover;
           background-image: url(back1.jpg);
       }
           

       .insight{
           color: rgb(229, 19, 226);

       }

       
       .hrstyle{
           width:100px;
       }
       .author{
       
           display: inline;
           position: relative;
           color: rgb(21, 17, 21);
           top:190px;
           font-style: inherit;
           font-family:Georgia;
           font-size: medium;
       }
       .booktitle{
           font-family: 'Courier New', Courier, monospace;
           font-size: larger;
           text-align: center;
           font-style: italic;
           position: relative;
           top: 30px;
       
       }
       .id {
           width:400px;
           position: relative;
           top:180px;
           
       }
       .ed{
           color: rgb(86, 46, 156);
           font-size: medium;
           font-family: Verdana;
           position:relative;
           top:85px;

       }
       .subtitle{
           color:rgb(28, 12, 249);
           font-family:Verdana;
           font-size: small;
           position: relative;
           top:40px;
           font-style: oblique;
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
               SEC WORK
           </div>
           <div class="hrstyle">
               <hr style="color: rgb(255, 0, 217);">
           </div>
           <div class="booktitle">
               <h2>Ethical Hacking Course</h2></div>
           <div class="subtitle">
           Learn The Ethical Way of HACKING!!!
           </div>
           <div class="mypic">
               <img src="my pic.jpg" width="125" height="150" alt="">
           </div>
           <div class="id">
               <hr style="color: orange;">
           </div>
           <div class="author">
              <p><b>MUGUNTHAN M(24005593)</b></p>
           </div>
           <div class="ed">
               <b>III Edition</b>
           </div>
       </div>
   </body>
</html>
```
# OUTPUT:
![Screenshot 2024-12-05 184045](https://github.com/user-attachments/assets/36fbd535-cee2-493c-9896-5a76ecc8f1fb)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
