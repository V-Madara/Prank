<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Claim Your Reward</title>
    <style>
        body {
            text-align: center;
            margin-top: 50px;
        }
        img {
            cursor: pointer;
            max-width: 90%;
            height: auto;
        }
    </style>
</head>
<body>
    <img id="prankImage" src="first_image.jpg" onclick="swapImage()">
</body>
    <script>
        function swapImage() {
            document.getElementById("prankImage").src = "second_image.jpg";
        }
    </script>
</html>
