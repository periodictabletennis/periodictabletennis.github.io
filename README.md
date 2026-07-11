<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Full Page Responsive Image</title>
    <style>
        /* Reset margins and default spacing */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Ensure the document takes up the full browser screen */
        html, body {
            width: 100%;
            height: 100%;
            overflow: hidden; /* Prevents scrollbars */
            background-color: #000; /* Dark background fallback while loading */
        }

        /* Responsive image styling */
        .full-page-img {
            width: 100vw;            /* 100% of the viewport width */
            height: 100vh;           /* 100% of the viewport height */
            object-fit: cover;       /* Automatically scales and crops without stretching */
            object-position: center; /* Keeps the center of the image in focus */
            display: block;          /* Removes default inline spacing at the bottom */
        }
    </style>
</head>
<body>

    <!-- 
      REPLACE WITH YOUR IMAGE:
      You can use a local file path (like "my-photo.jpg") or a web URL link. 
    -->
    <img src="https://unsplash.com" alt="Responsive full page background" class="full-page-img">

</body>
</html>
