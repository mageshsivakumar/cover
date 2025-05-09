# Ex.06 Book Front Cover Page Design
## Date:09/05/2025
# Name : Magesh S
# reg no : 212224040180

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
html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Book Cover</title>
  <link href="https://fonts.googleapis.com/css2?family=Indie+Flower&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="book-cover">
    <div class="cover">
      <h1 class="title">The Art of Coding</h1>
      <p class="author">by Jane Doe</p>
    </div>
    <div class="spine"></div>
    <div class="back-cover">
      <p class="description">An insightful journey into the world of programming and software development.</p>
    </div>
  </div>
</body>
</html>

css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Indie Flower', sans-serif;
  background-color: #f4f4f4;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.book-cover {
  display: flex;
  width: 300px;
  height: 400px;
  background-color: #fff;
  border: 2px solid #333;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  overflow: hidden;
}

.cover {
  flex: 2;
  background-color: #4CAF50;
  color: white;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 20px;
  text-align: center;
}

.title {
  font-size: 24px;
  font-weight: bold;
  margin-bottom: 10px;
}

.author {
  font-size: 18px;
  font-style: italic;
}

.spine {
  width: 20px;
  background-color: #333;
}

.back-cover {
  flex: 2;
  background-color: #f0f0f0;
  padding: 20px;
}

.description {
  font-size: 14px;
  color: #555;
}


## OUTPUT:
![Screenshot 2025-05-09 140326](https://github.com/user-attachments/assets/dfd1eb2b-2949-4705-bbfa-ba688ba74ec9)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
