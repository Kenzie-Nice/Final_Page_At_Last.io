<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coffee Making Guide</title>
    <!-- Bootstrap CSS -->
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <style>
        /* Your existing CSS styles */
        body {
            font-family: Arial, sans-serif;
            background-color: #e0f2f1;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 800px;
            margin: 50px auto;
            padding: 20px;
            background-color: rgba(255, 255, 255, 0.8);
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.2);
        }
        h1, h2, h3, h4, h5, h6 {
            text-align: center;
        }
        .highlight {
            color: red;
        }
        iframe, table {
            margin: 20px auto;
            display: block;
        }
        ul, ol {
            margin-left: 20px;
        }
        form {
            text-align: center;
        }
        form label {
            margin-right: 10px;
        }
        .footer {
            text-align: center;
            margin-top: 50px;
        }
        /* Additional CSS for Canvas */
        canvas {
            display: block;
            margin: 20px auto;
            border: 1px solid black;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Your existing HTML content -->
    </div>
 <!-- HTML5 Canvas -->
    <canvas id="myCanvas" width="400" height="200"></canvas>
 <!-- Bootstrap JavaScript -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script
     <!-- JavaScript for Canvas -->
    <script>
        // Get the canvas element
        var canvas = document.getElementById("myCanvas");
        var ctx = canvas.getContext("2d");
        // Draw a red rectangle on the canvas
        ctx.fillStyle = "red";
        ctx.fillRect(10, 10, 50, 50);
    </script>
    <!-- Your existing footer -->
    <ul>
        <li> Home Page <a href="https://kenzie-nice.github.io/Kenzie_Nice.github.io/">Home we go!</a></li>
        <li>Any Questions, comments, or concerns? <a href="https://kenzie-nice.github.io/Contact-Page.io/">Contact Us!</a></li>
        <li> Interested in our origin?!<a href="https://kenzie-nice.github.io/About_us.io/">About Us!</a></li>
    </ul>
</body>
</html>
