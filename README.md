<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Animation Beast</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #444;
            color: white;
            padding: 10px 20px;
            text-align: center;
        }
        nav {
            text-align: center;
            margin: 20px 0;
        }
        nav a {
            color: #444;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .content {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .link-section {
            text-align: center;
            margin: 20px 0;
        }
        .link-section a {
            display: inline-block;
            padding: 10px 20px;
            background-color: #007BFF;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-size: 18px;
        }
        .link-section a:hover {
            background-color: #0056b3;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .gallery img {
            width: 200px;
            height: 200px;
            object-fit: cover;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
        }
        .why-section {
            margin-top: 40px;
            padding: 20px;
            background: #e8f5e9;
            border-radius: 8px;
            text-align: center;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #444;
            color: white;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Animation Beast</h1>
        <p>Your hub for epic stop-motion animation and action figures!</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#gallery">Gallery</a>
        <a href="#link">My Channel</a>
        <a href="#why">Why I Made This</a>
    </nav>

    <div class="content" id="home">
        <h2>Welcome to Animation Beast!</h2>
        <p>Discover stunning stop-motion animations and action figure collections. Dive into a world of creativity and epic battles brought to life through animation.</p>
    </div>

    <div class="content link-section" id="link">
        <h2>Check Out My YouTube Channel</h2>
        <a href="https://www.youtube.com/@The_stop-motion_MAN" target="_blank">Visit Animation Beast on YouTube</a>
    </div>

    <div class="content" id="gallery">
        <h2>Action Figure Gallery</h2>
        <div class="gallery">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT_hUOv2fR3Pj29sjYhWeMeZVxNLoUdpI63euhrjntYTy55Nboa6HTd6XKtgPVjiwHM254&usqp=CAU" alt="Action Figure 1">
            <img src="https://m.media-amazon.com/images/I/71Hc7uqVhIL._AC_UF894,1000_QL80_.jpg" alt="Action Figure 2">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQbnBYyof6CVtyINQ2F_XhfWjMnJQdF0_m_BQ&s" alt="Action Figure 3">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRzeDQjBjpT9cCRgXndWuFwn74hY92fPSvS0g&s" alt="Action Figure 4">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRngWqQzMUZGcvtIqdZDe_qTw2Reb4pCIdIPQ&s" alt="Action Figure 5">
        </div>
    </div>

    <div class="content why-section" id="why">
        <h2>Why I Made This Account</h2>
        <p>I created this stop-motion account to share my passion for storytelling and animation. Stop-motion allows me to bring action figures to life, creating epic battles and unique narratives. It's a blend of creativity, patience, and imagination that I love to share with others. Join me on this journey!</p>
        <p>Created by: The_Stop-Motion_Man</p>
    </div>

    <footer>
        <p>&copy; 2024 Animation Beast. All Rights Reserved.</p>
    </footer>
</body>
</html>
