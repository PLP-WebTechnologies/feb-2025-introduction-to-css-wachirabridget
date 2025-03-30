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

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Introduction</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1 class="title">Welcome to CSS Styling</h1>
    </header>
    <section>
        <p id="description">CSS helps style and format web pages beautifully.</p>
        <img src="image.jpg" alt="Sample Image" class="styled-image">
    </section>   
    <footer>
        <p>&copy; 2025 Your Name</p>
    </footer>
</body>
</html>

{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.title {
    color: darkblue;
    font-family: 'Arial', sans-serif;
    text-align: center;
    margin: 20px 0;
}

#description {
    font-size: 18px;
    color: #333;
    padding: 10px;
    border-left: 4px solid darkblue;
    margin-bottom: 20px;
}

.styled-image {
    display: block;
    margin: 20px auto;
    width: 50%;
    border: 5px solid black;
    border-radius: 10px;
}


