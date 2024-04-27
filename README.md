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
'''



  <html>
    
    <heAD>
      
      <title>

            Book Cover
        </title>
        <style>
        .book
            {
                width: 450px;
                height: 600px;
                color:gold;
                margin-left: auto;
                margin-right: auto;
                padding: 20px;
                background-image: url("book\ cover.jpg");
                background-size: cover;
            }
            .insight
            {
                color: silver;
                margin-left: 80px;
                margin-top: 70px;

            }
            .hrstyle
            {
                width:98px;
                margin-left: 70px;

            }
            .booktitle
            {
                font-size: larger;
                font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
                text-align: center;
                position: relative;
                top: 30px;
                margin-top: 20px;
            }
            .subtitle
            {
                font-family: sans-serif;
                font-size: large;
                position: relative;
                top:50px;
                margin-left: 100px;
                margin-top: 30px;
            }
            .mypic
            {
                position: relative; 
                top: 135px; 
                left: 260px; 
                width: 100px; 
                height: 100px; 
                background-size: cover;
            }
            .id { 
                width:350px; 
                position: relative; 
                margin-left: 30px;
                top:180px;
               
            }
            .author
            {
                 display: inline; 
                 position: relative; 
                 color: yellow; 
                 top:190px; 
                 left:155px;
                 font-family:Georgia; 
                 font-size: medium;
            }
            .pub
            {
                font-size: medium; 
                position: relative; 
                top:155px; 
                left:330px;
            }
            .ed
            {
                color: silver; 
                font-size: medium; 
                font-family: Verdana;
                position:relative; 
                margin-left: 30px;
                top:85px;
            }

        </style>
    </head>
    <body>
        <div class="book">
            <div class="insight">
                SEC INSIGHT
            </div>
            <div class="hrstyle"> 
                <hr style="color: red;">
             </div>
            <div class="booktitle">
                FUNDAMENTALS OF WEB APPLICATION
            </div>
            <div class="subtitle">
                HTML AND CSS COMBINED WITH DJANGO ARCHITECTURE
            </div>
            <div class="mypic">
                <img src="kamalesh2.jpeg" height="140" width="125">
            </div>
            <div class="id">
                <hr style="color: orange;">
            </div>
            <div class="author">
                <p><b>KAMALESH</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>SIXTH EDITION</b>
            </div>
        </div>
    </body>
</html>
'''


## OUTPUT:
![Screenshot 2024-04-27 102226](https://github.com/sakamalesh/cover/assets/149148235/86c4226d-bcb4-441e-8db5-b452d7afaf55)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
