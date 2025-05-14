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
<html lang="en">
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        .bookpage {
            width: 400px;
            height: 600px;
            color: rgb(0, 0, 0);
            margin-left: auto;
            margin-right: auto;
            padding: 10px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url("apj-abdul-kalam-the-missile-man-of-india.jpg");
            background-size: cover;
            background-position: center;
        }

        

        .hrstyle {
            width: 400px;
        }

        .author {
            display: inline;
            position: relative;
            color: rgb(255, 255, 255);
            top: 299.5px;
            font-family: Georgia;
            font-size: medium;
        }

        .booktitle {
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 1px;
            color: black;
        }

        .id {
            width: 400px;
            position: relative;
            top: 300px;
        }

        .pub {
            font-size: medium;
            position: relative;
            top: 260px;
            left: 330px;
            color: aliceblue;
        }

        .ed {
            color: rgb(249, 249, 249);
            font-size: medium;
            font-family: Verdana;
            position: relative;
            top: 205px;
        }

        .subtitle {
            font-family: Tahoma;
            font-size: large;
            position: relative;
            top: 40px;
        }

        .mypic {
            position: relative;
            top: 250px;
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
            
        </div>
        <div class="hrstyle">
            <hr style="color: red;">
        </div>
        <div class="booktitle">
            <h1>THE MISSILE MAN OF INDIA</h1>
        </div>
        <div class="subtitle">
            
        </div>
        <div class="mypic">
            <img src="C:\Users\WELCOME\Documents\WhatsApp Image 2024-11-02 at 08.43.04_80645c69.jpg" width="130" height="145" alt="">
        </div>
        <div class="id">
            <hr style="color: rgb(208, 255, 0);">
        </div>
        <div class="author">
            <p><b>Gowtham S</b></p>
        </div>
        <div class="pub">
            SEC
        </div>
        <div class="ed">
            <b>Extended Edition</b>
        </div>
    </div>
</body>
</html>

```

## OUTPUT:
![image](https://github.com/user-attachments/assets/7e247f0e-0511-4703-83f5-a92b23979311)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

