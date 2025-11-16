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
<html>

<head>
    <title>BOOK COVER</title>
    <style>
        body {
            background-color: #f0f0f0;
        }

        .bookcover {
            width: 400px;
            height: 600px;
            margin: 50px auto;
            padding: 25px;
            font-family: 'Arial', sans-serif;
            color: #fff;

            /* Background image */
            background-image: url('coverbg.jpg'); /* <-- Replace with your background file */
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;

            border-radius: 15px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.5);
            position: relative;
            overflow: hidden;
        }

        .publisher {
            font-size: 18px;
            color: #00e0ff;
            font-weight: bold;
            text-align: center;
            letter-spacing: 1px;
        }

        .title {
            font-family: 'Georgia', serif;
            font-size: 28px;
            font-weight: bold;
            text-align: center;
            margin: 40px 0 10px 0;
            color: #9d0808;
        }

        .subtitle {
            font-family: 'Verdana', sans-serif;
            font-size: 16px;
            text-align: center;
            margin-bottom: 30px;
            color: #80059e;
        }

        .cover-image {
            display: block;
            margin: 0 auto;
            width: 120px;
            height: 120px;
            border-radius: 10px;
            object-fit: cover;
            border: 3px solid #00e0ff;
        }

        .author {
            font-size: 18px;
            color: #010906;
            font-weight: bold;
            text-align: center;
            margin-top: 20px;
        }

        .decor-line {
            width: 80%;
            height: 2px;
            background-color: #00e0ff;
            margin: 20px auto;
            border: none;
        }

        .edition {
            position: absolute;
            bottom: 20px;
            right: 20px;
            font-size: 14px;
            color: #080205;
            font-weight: bold;
        }
    </style>
</head>

<body>
    <div class="bookcover">
        <div class="publisher">Present by WORLD THINGS</div>

        <div class="title">Advanced JavaScript Patterns</div>
        <div class="subtitle">Mastering Efficient Web Development</div>

        <!-- Author or book photo -->
        <img class="cover-image" src="myphoto.jpg" alt="Author Photo">

        <hr class="decor-line">

        <div class="author">By Shyam Gideon.A </div>

        <div class="edition">3rd EDITION</div>
    </div>
</body>

</html>

```


## OUTPUT:

![alt text](<Screenshot 2025-11-16 234532.png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
