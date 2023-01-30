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
<style>
    .bookpage{
        width: 400px;
        height: 600px;
        color:crimson;
        margin-left: auto;
        margin-right: auto;
        padding: 20px;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        background-image: url(/static/images/back.jpg);
        background-size: cover;
    }
        

    .insight{
        color: blue;

    }

    
    .hrstyle{
        width:100px;
    }
    .author{
    
        display: inline;
        position: relative;
        color: purple;
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
        color:orange;
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
            <h1>Coding for beginners</h1></div>
        <div class="subtitle">
            C,C++,Python and more.
        </div>
        <div class="mypic">
            <img src="/static/images/profile.JPG" width="130" height="145" alt="">
        </div>
        <div class="id">
            <hr style="color: black;">
        </div>
        <div class="author">
           <p><b>Ben Frain</b></p>
        </div>
        <div class="pub">
            SEC
        </div>
        <div class="ed">
            <b>Third Edition</b>
        </div>
    </div>
</body>


# Output:

![image](https://user-images.githubusercontent.com/118707852/215408009-9e1ff620-3b85-474a-aaa0-eb6deadbbd54.png)


# RESULT:
Hence the program to print the book cover is succesfully runned.
