# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=mn, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>Web development</h1>
    <p id="basic">Understand the basics of CSS and its role in styling web pages.</p>
    <img class="image" src="pexels-luis-gomes-166706-546819.jpg" alt="computer">
</body>
</html>
body{
    background-color: #f0f0f0;
    margin: 0;
    padding: 0; 
}
h1{
    text-align: center;
    margin-top: 50px;
    color: tomato;
}
#basic{
    font-family: 'Arial', sans-serif;
    font-size: 18px; 
    font-weight: bold; 
    color: #333; 
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 40px 40px;
    
}
.image{
    width: 500px;
    height: 400px;
    display: block;
    margin-left: auto;
    margin-right: auto;
    border-radius: 50px;
}

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨
