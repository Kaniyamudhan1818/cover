# Ex.06 Book Front Cover Page Design
## Date:15.05.2025

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
~~~
<html>
 <head>
       <meta name="viewport"
          content="width=device-width, initial-scale=1.0">
          <style>
         


         .bookpage{
              width: 400px;
              height: 600px;
              color:rgba(243, 195, 195, 0.938)00, 17, 17;
              margin-left : auto;
              margin-right : auto;
              padding: 20px;

              font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
              background-image: url(bg.jpg);
              background-size: cover;
              }
             .insight{
                color:yellow;
              }

             .hrstyle{
             width:100px;
             }
             .author{
             display: inline;
             position: relative;
             color:gold;
             top:240px;

             font-family:Georgia;
             font-size: medium;
             }
             .booktitle{
             font-family: 'Courier New',Courier,monospace;
             font-size: larger;
             text-align: center;
             position: relative;
             top: 30px;
             color:black;
             ;
             }
             .id {
             width:400px;
             position: relative;
             top:250px;
             }
             .pub{
             font-size: medium;
             position: relative;
             top:204px;
             left:350px;
             color:gold;
             }
             .ed{
             color:yellow;
             font-size: medium;
             font-family: Verdana;
             position:relative;
             top:150px;
             left: 230;
             }
             .subtitle{
             font-family:Tahoma;
             font-size: large;
             position:relative;
             top:100px;
             color:black;
             }
             .mypic{
             position:relative;
             top:200px;
             right: 10px;
             width: 100px;
             height: 100px;
             background-size:cover;
             }
             </style>
             <title>Book Cover Page</title>
             </head>
             <body>
             <div class="bookpage">
             <div class="insight">
                KANIYAMUDHAN PUBLICATION
             </div>
             <div class="hrstyle">
                <hr style="color: rgb(128, 128, 96);">
             </div>
             <div class="booktitle">
             <h1>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</h1>
             </div>
             <div class="subtitle">
               EASY WAY TO LEARN WEB DEVELOPMENT
             </div>
             <div class ="mypic">
               <img src="MY.jpg" width="130" height="145" alt="">
             </div>
             <div class="id">
             <hr style="color: rgb(145, 145, 114);">
             </div>
             <div class="author">
             <p><b>KANIYAMUDHAN V</b></p>
             </div>
             <div class="pub">
             SEC
             </div>
             <div class="ed">
             <b>SECOND VERSION</b>
          </div>
    </body>
</html>

~~~

## OUTPUT:
![alt text](<Screenshot (14).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
