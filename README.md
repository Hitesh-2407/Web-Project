# Web-Project
Photo Galary of Anime Pictures

<!DOCTYPE html>
<html lang="en">
<head>

    <title>Photo Gallery</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f4f4f4;
        }

        header {
            text-align: center;
            padding: 20px;
            background: #333;
            color: white;
        }

        header h1 {
            margin: 0;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 30px;
            padding: 40px;
        }

        .gallery img {
            width: 100%;
            height: 250px;
            object-fit: cover;
            border-radius: 10px;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .gallery img:hover {
            transform: scale(1.05);
            box-shadow: 0px 4px 10px rgba(0,0,0,0.3);
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #333;
            color: white;
        }
    </style>
</head>
<body>

    <header>
        <h1>My Anime Photo Gallery</h1>
        <p>Anime Pictures</p>
    </header>

    <div class="gallery">
        <img src="1.jpg" alt="Image 1">
	<img src="2.jpg" alt="Image 2">
	<img src="3.jpg" alt="Image 3">
	<img src="4.png" alt="Image 4">
	<img src="5.jpeg" alt="Image 5">
	<img src="6.jpg" alt="Image 6">
	<img src="7.jpg" alt="Image 7">
	<img src="8.jpg" alt="Image 8">
	<img src="9.jpg" alt="Image 9">
	<img src="10.jpg" alt="Image 10">
	<img src="11.jpg" alt="Image 11">
	<img src="12.png" alt="Image 12">
	<img src="13.jpeg" alt="Image 13">
	<img src="14.jpg" alt="Image 14">
	<img src="15.jpg" alt="Image 15">
	<img src="16.jpg" alt="Image 16">
	<img src="17.jpg" alt="Image 17">
	<img src="18.jpg" alt="Image 18">
	<img src="19.jpeg" alt="Image 19">
	<img src="hi.jpg" alt="Image 20">
        

    </div>

    <footer>
        <p>© 2026 Photo Gallery | Created by Hitesh</p>
    </footer>

</body>
</html>
