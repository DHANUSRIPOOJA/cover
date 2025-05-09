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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Pride and Prejudice - Book Cover</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Raleway:wght@400;600&display=swap');

    body {
      background: linear-gradient(to bottom right, #dcdcdc, #bbb);
      height: 100vh;
      margin: 0;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .book {
      position: relative;
      width: 340px;
      height: 580px;
      background: linear-gradient(145deg, #ffe0ec, #ffc2d1);
      border-radius: 16px;
      box-shadow: 0 25px 40px rgba(0, 0, 0, 0.4);
      color: #333;
      font-family: 'Playfair Display', serif;
      overflow: hidden;
      padding: 40px 30px;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      border: 1px solid #fff;
    }

    .book::before {
      content: '';
      position: absolute;
      top: 0;
      left: -30px;
      width: 30px;
      height: 100%;
      background: linear-gradient(to right, #9e9e9e, #e0e0e0);
      border-radius: 12px 0 0 12px;
      box-shadow: inset -2px 0 6px rgba(0, 0, 0, 0.3);
    }

    .title {
      font-size: 30px;
      font-weight: 700;
      color: #4b2e2e;
    }

    .subtitle {
      font-size: 16px;
      font-family: 'Raleway', sans-serif;
      margin-top: 5px;
      color: #6e4c4c;
    }

    .author-image {
      width: 100px;
      height: 100px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid #fff;
      margin: 20px auto 0;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    }

    .quote {
      font-family: 'Raleway', sans-serif;
      font-size: 14px;
      font-style: italic;
      color: #555;
      margin-top: 20px;
      background: rgba(255, 255, 255, 0.65);
      padding: 10px;
      border-left: 4px solid #b56b82;
      border-radius: 4px;
    }

    .author {
      font-family: 'Raleway', sans-serif;
      font-size: 18px;
      font-weight: 600;
      text-align: right;
      margin-top: 20px;
      color: #4b2e2e;
    }

    .publisher {
      font-family: 'Raleway', sans-serif;
      font-size: 12px;
      text-align: center;
      color: #777;
      margin-top: 30px;
    }

    .publisher::before {
      content: "❧";
      display: block;
      font-size: 20px;
      color: #ec9db8;
      margin-bottom: 5px;
    }
  </style>
</head>
<body>
  <div class="book">
    <div>
      <div class="title">Pride and Prejudice</div>
      <div class="subtitle">A Classic Novel</div>
      <!-- Author Image -->
      <img src="author1.jpg" alt="Author" class="author-image">
      <div class="quote">“It is a truth universally acknowledged, that a single man in possession of a good fortune, must be in want of a wife.”</div>
    </div>
    <div>
      <div class="author">by K DHANUSRI POOJA(212224040068)</div>
      <div class="publisher">Pink Rose Classics</div>
    </div>
  </div>
</body>
</html>
```


## OUTPUT:
![Screenshot 2025-05-09 103104](https://github.com/user-attachments/assets/0edea00a-766a-4ec2-9cf2-8aa4797acd2b)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
