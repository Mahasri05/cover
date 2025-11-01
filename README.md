# Ex.06 Book Front Cover Page Design
## Date:
31.10.2025

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
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Book Cover</title>
<link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Cinzel+Decorative:wght@700&display=swap" rel="stylesheet">
<style>
  body {
    margin: 0;
    padding: 0;
    background-color: #f6f6f6;
  }

  .cover-container {
    position: relative;
    width: 100%;
    max-width: 800px;
    margin: auto;
  }

  .cover-container img {
    width: 100%;
    height: auto;
    display: block;
    border-radius: 10px;
  }

  .title {
    position: absolute;
    top: 45%;
    left: 50%;
    transform: translate(-50%, -50%);
    font-family: 'Cinzel Decorative', cursive;
    font-size: 3em;
    color: #2f3e46;
    text-align: center;
    letter-spacing: 2px;
    text-shadow: 2px 2px 6px rgba(0, 0, 0, 0.3);
  }

  .author {
    position: absolute;
    bottom: 30px;
    left: 50%;
    transform: translateX(-50%);
    font-family: 'Great Vibes', cursive;
    font-size: 2em;
    color: #36454F;
    text-shadow: 1px 1px 3px rgba(0,0,0,0.3);
  }
</style>
</head>
<body>

<div class="cover-container">
  <img src="cover img .png" alt="Book Cover">
  <div class="title">Whispers of Bloom</div>
  <div class="author">Developed by Mahasri D</div>
</div>

</body>
</html>
```

## OUTPUT:
![alt text](image.png)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
