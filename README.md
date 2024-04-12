<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">    
    <title>Image Display Website</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;   
        }

        .container {
            position: relative;
            width: 100%;
            height: 100%;
        }

        .image-container {
            width: 70%; /* Adjust the width of the image container as needed */
            height: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            float: left;
        }

        .image-container img {
            max-width: 100%;
            max-height: 100%;
            object-fit: contain;
        }

        .search-button-container {
            position: absolute;
            top: 20px; /* Adjust the top position of the button container */
            right: 20px; /* Adjust the right position of the button container */
        }

        .search-button {
            font-size: 24px;
            padding: 15px 30px; /* Adjust the padding of the button as needed */
            border: none;
            background-color: #f44336; /* Adjust the background color of the button */
            color: #fff;
            cursor: pointer;
            border-radius: 10px; /* Add border-radius for rounded corners */
        }

        .search-button:hover {
            background-color: #d32f2f; /* Change color on hover if desired */
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="image-container">
            <img src="https://github.com/636a0a8c-e57b-44ef-9521-9e0729ed45ea" alt="Placeholder Image">
        </div>
        <div class="search-button-container">
            <button class="search-button">Search</button>
        </div>
    </div>
</body>
</html>




