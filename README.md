<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BSC COMPUTER SCIENCE</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #666;
            color: #fff;
            padding: 10px;
            text-align: center;
        }
        nav a {
            text-decoration: none;
            color: #fff;
            margin: 0 10px;
        }
        section {
            padding: 20px;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .gallery img {
            max-width: 100%;
            height: auto;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>COMPUTER SCIENCE STUDENTS 22-25</h1>
</header>

<nav>
    <a href="#photos">Photos</a>
    <a href="#videos">Videos</a>
    <a href="#contact">Contact</a>
</nav>

<section id="photos">
    <h2>Photos</h2>
    <div class="gallery">
        <img src="img2.png.jpg" alt="Photo 1">
        <img src="img4.png.jpg" alt="Photo 2">
        <img src="img3.png.jpg" alt="Photo 3">
        <!-- Add more photos as needed -->
    </div>
</section>

<section id="videos">
    <h2>Videos</h2>
    <video width="640" height="360" controls>
        <source src="video1.png.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
    <video width="640" height="360" controls>
        <source src="video2.png.mp4" type="video/mp4">
        Your browser does not support the video tag
    </video>
    <!--add more vidoes as needed-->
</section>


<section id="Contant">
    <h2>Contact</h2>
    <h2>balakumaran467@gmail.com</h2>
</section>


<footer>
    <p>&copy; <a href=" https://www.instagram.com/bala..m?igsh=aDU1bjRpNW1xdzJy">balakumaran</a> </p>
</footer>

</body>
</html>
