<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coffee Making Guide</title>
    <!-- Bootstrap CSS -->
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-image: url('depositphotos_424626210-stock-photo-autumn-leaves-in-a-puddle.jpg'); 
            background-size: cover;
            background-position: center;
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
        canvas {
            display: block;
            margin: 20px auto;
            border: 1px solid black;
        }
        .main-photo {
            display: block;
            margin: 20px auto; 
            width: 300px; 
            border-radius: 10px;
        }
        /* Center-align the navbar links */
        .navbar-nav {
            margin: 0 auto;
            display: table;
        }
        .navbar-nav .nav-item {
            display: table-cell;
            text-align: center;
        }
    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
            <ul class="navbar-nav">
                <li class="nav-item">
                    <a class="nav-link" href="https://kenzie-nice.github.io/Final_Page_At_Last.io/">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="https://kenzie-nice.github.io/Final-stuff.io/">Contact Us</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="https://kenzie-nice.github.io/FinalAbout.io/">About Us</a>
                </li>
            </ul>
        </div>
    </nav>

    <div class="container">  
        <h3><img src="37605990474_d632c445e0_b.jpg" alt="Coffee Image 3" class="Dream Life"></h3> 
        <p>Natural rain makes everything look so pretty, though a professional photographer also helps.</p>
        <h1><img src="rain-flower_27V64NTJSD.jpg" alt="Flower" class="main-photo"></h1> 
           <p>Rain as expected, does help plants grow as it carries an important biological function for a plant. But it can also do more than help sustain the plant; it can assist even with pollination.</p>
        <h2><img src="leaf-rain_Q4TIQ25RBY.jpg" alt="Leaf" class="main-photo"></h2> 
         <p>I Leaf.....</p>
    </div>
    <!-- HTML5 Canvas -->
    <canvas id="myCanvas" width="400" height="200"></canvas>
    <!-- Bootstrap JavaScript -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    <!-- JavaScript for Canvas -->
    <script>
        // JavaScript code for canvas
        var canvas = document.getElementById("myCanvas");
        var ctx = canvas.getContext("2d");
        ctx.fillStyle = "red";
        ctx.fillRect(10, 10, 50, 50);
    </script>
</body>
</html>

