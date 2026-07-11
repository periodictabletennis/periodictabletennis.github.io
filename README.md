<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Full Page Responsive Image</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html, body {
            width: 100%;
            height: 100%;
            overflow: hidden;
            background-color: #000;
        }

        .full-page-img {
            width: 100vw;
            height: 100vh;
            object-fit: cover;
            object-position: center;
            display: block;
        }
    </style>
</head>
<body>

    <!-- This directly calls your uploaded repository image -->
    <img src="ptt.PNG" alt="Responsive full page background" class="full-page-img">

</body>
</html>
