<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Right Side</title>
    <style>
        /* Set full height for body and html */
        html, body {
            height: 100%;
            margin: 0;
        }

        /* Flexbox parent container to divide the page in half */
        .parent {
            display: flex;
            flex-direction: row;
            height: 100%;
            width: 100%;
        }

        /* Left side (empty) div */
        .leftdiv {
            width: 50%;
            height: 100%;
            background-color: #f4f4f4; /* Light background color for the left side */
        }

        /* Right side (image) div */
        .rightdiv {
            width: 50%;
            height: 100%;
            background-image: url('https://catalog-management.s3.ap-south-1.amazonaws.com/htmobile1/simpleenergy_dot-one/images/exterior_simple-energy-dot-one_left-view_600x400.jpg'); /* Image URL */
            background-size: cover; /* Ensure the image covers the full div */
            background-position: center; /* Center the image */
            background-repeat: no-repeat; /* Prevent the image from repeating */
        }
    </style>
</head>

<body>
    <div class="parent">
        <div class="leftdiv"></div>  
        <div class="rightdiv"></div>
    </div> 
</body>
</html>

