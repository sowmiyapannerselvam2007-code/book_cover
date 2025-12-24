# Ex.05 Book Front Cover Page Design
# Date:15.12.2025
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
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Book Cover</title>

  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(135deg, #2c3e50, #000000);
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .cover-container {
      width: 400px;
      height: 600px;
      box-shadow: 0 20px 40px rgba(0, 0, 0, 0.6);
      border-radius: 15px;
      overflow: hidden;
      position: relative;
    }

    .background {
      width: 100%;
      height: 100%;
      object-fit: cover;
      position: absolute;
      inset: 0;
      z-index: 1;
    }

    .overlay {
      position: relative;
      z-index: 2;
      height: 100%;
      padding: 40px 25px;
      box-sizing: border-box;
      color: #ffffff;
      text-align: center;
      background: linear-gradient(
        to bottom,
        rgba(0, 0, 0, 0.6),
        rgba(0, 0, 0, 0.85)
      );
      display: flex;
      flex-direction: column;
      justify-content: center;
    }

    .title {
      font-size: 38px;
      font-weight: bold;
      letter-spacing: 3px;
      margin-bottom: 10px;
    }

    .subtitle {
      font-size: 20px;
      font-style: italic;
      color: #f1c40f;
      margin-bottom: 40px;
    }

    .author {
      font-size: 18px;
      margin-top: auto;
      margin-bottom: 20px;
      letter-spacing: 1px;
    }

    .author-photo {
      position: absolute;
      bottom: 25px;
      right: 25px;
      width: 110px;
      height: 110px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid #ffffff;
      box-shadow: 0 0 15px rgba(255, 255, 255, 0.4);
      z-index: 3;
      background-color: #6e67cd;
    }
  </style>
</head>

<body>
  <div class="cover-container">
    <img src="book.jpg" alt="Background Image" class="background">

    <div class="overlay">
      <h1 class="title">Magic Has Whiskers</h1>
      <h2 class="subtitle">Not All Magic Comes With A Wand</h2>
      <p class="author">by SOWMIYA</p>
    </div>

    <img src="me.jpg" alt="Author Photo" class="author-photo">
  </div>
</body>
</html>
```
# OUTPUT:
![alt text](<Screenshot 2025-12-15 180039.png>)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
