<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Background Image Website</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
        }

        .background-images {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            display: flex;
        }

        .background-images img {
            width: 33.333%;
            height: 100%;
            object-fit: cover;
        }

        .search-container {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            text-align: center;
        }

        .search-button {
            font-size: 24px;
            padding: 10px 20px;
            border: none;
            background-color: #333;
            color: #fff;
            cursor: pointer;
        }

        .search-button:hover {
            background-color: #555;
        }
    </style>
</head>
<body>
    <div class="background-images">
        <img src="https://images.app.goo.gl/idEPFfsM15XoinyL8" alt="Background Image 1">
        <img src="https://images.app.goo.gl/cnKqHfGokNGReRkJ6" alt="Background Image 2">
        <img src="https://images.app.goo.gl/woKRmdf46qtofP2i7" alt="Background Image 3">
    </div>
    <div class="search-container">
        <button class="search-button">Search</button>
    </div>
</body>
</html>
