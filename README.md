<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <css>/* Remove browser default padding and margins */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body, html {
    width: 100%;
    height: 100%;
    overflow: hidden; /* Prevents unwanted scrollbars */
}

.full-page-img {
    width: 100vw;       /* 100% of viewport width */
    height: 100vh;      /* 100% of viewport height */
    object-fit: cover;  /* Crops and scales without losing aspect ratio */
    object-position: center; /* Keeps the center of the image focused */
    display: block;     /* Eliminates default inline spacing at bottom */
}
</css>
    <title>Full Page Responsive Image</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <img src="https://github.com/periodictabletennis/periodictabletennis.github.io/blob/b7f0a547f5ea5d86b6b5d5289e26b7ae921d57b7/ptt.PNG" alt="Periodic Table Tennis" class="full-page-img">

</body>
</html>
