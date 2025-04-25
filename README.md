# Ex.06 Book Front Cover Page Design
## Date:25.04.2025

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
cover.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            font-family: Arial, sans-serif;
            
        }
        .cover {
            width: 450px;
            height: 750px;
            border: 2px solid #000;
            background-color: #fff;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            background-repeat: no-repeat;
            background-position: center;
            background-image: url('1.png');
        }
        .title {
            font-size: 40px;
            font-weight: bold;
            font-family:'Harrington'; 
            text-align: center;;
            margin-bottom: 70px;
            color: hsl(190, 70%, 88%);
        }
        .subtitle {
            font-size: 35px;
            font-family: Chiller;
            margin-bottom: 20px;
            text-align: right;
            color: rgb(189, 238, 246);
        }
        .bottom-text {
            margin-top: auto;
            font-family: "Matura MT Script Capitals";
            font-size: 30px;
            color: rgb(189, 168, 140)     }
    </style>
</head>
<body>
    <div class="cover">
        <div class="title">The last Guardian of the Forsaken blade</div>
        <div class="subtitle">The Story of Real Hero</div>
        <div class="bottom-text">Written By:RAM</div>
    </div>
</body>
</html>
 ```

## OUTPUT:
![alt text](<Screenshot 2025-04-25 144533.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
