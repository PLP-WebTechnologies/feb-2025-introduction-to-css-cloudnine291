<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Styled Web Page</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <h1 id="main-title">Welcome</h1>

  <p class="intro-text">This page demonstrates external CSS styling using classes, IDs, and other properties.</p>

  <img src="image.jpg" alt="Sample Image" class="styled-image">

</body>
</html>



     css 

     #main-title {
  color: #2c3e50;
  font-family: 'Georgia', serif;
  margin-bottom: 20px;
  padding-bottom: 10px;
  border-bottom: 2px solid #ccc;
}

.intro-text {
  color: #444;
  font-family: Arial, sans-serif;
  font-size: 16px;
  margin: 20px;
  padding: 12px;
  border: 1px solid #bbb;
  background-color: #f5f5f5;
}

.styled-image {
  width: 300px;
  margin: 20px 0;
  padding: 6px;
  border: 2px solid #666;
  border-radius: 8px;
}
