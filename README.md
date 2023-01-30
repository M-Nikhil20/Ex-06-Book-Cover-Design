# Ex-06-Book-Cover-Design
## cover-page-design

# AIM:
To develop a website to display the cover page design of a book

# Design Steps:
# Step 1:
Create a new Django project and app.

# Step 2:
Create a static file directory and mention the changes in settings.

# Step 3:
Make a new folder templates inside your app and create a html and map them using views and url.

# Step 4:
Write down the code for book cover using HTML and CSS.

# Step 5:
Add images and other contents using CSS record a screenshot of it.

# Code:
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>
        .bookpage{
            width: 420px;
            height: 600px;
            color:rgb(245, 76, 9);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(/static/images/luff.jpg);
            background-size: cover;
        }
            
        .insight{
            color: rgb(236, 240, 3);
        }
        
        .hrstyle{
            width:100px;
        }
        .author{
            color: white;
            display: inline;
            position: relative;
            color: rgb(3, 3, 3);
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
            color:rgb(255, 115, 0);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;
        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
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
        <title>COVER PAGE DESIGN</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: rgb(0, 0, 0);">
            </div>
            <div class="booktitle" style="color: rgb(255, 64, 0);">
                <h1>Fundamentals of Web Application Development</h1></div>
            <div class="subtitle" style="color: rgb(247, 255, 6);"><b>
                HTML and CSS Combined with Django Architecture</b>
            </div>
            <div class="mypic" >
                <img src="/static/images/DSC_3162.jpg" width="60" height="100" alt="" style="vertical-align:bottom;margin:50px 55px">
            </div>
            <div class="id">
                <hr style="color: rgb(255, 0, 0);">
            </div>
            <div class="author">
               <p><b>A NIXAN DASS</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Seventh Edition</b>
            </div>
            
        </div>
    </body>
</html>



# Output:

![image](https://user-images.githubusercontent.com/118707852/215408009-9e1ff620-3b85-474a-aaa0-eb6deadbbd54.png)


# RESULT:
Hence the program to print the book cover is succesfully runned.
