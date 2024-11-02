<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MSKXplore</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background: #007BFF;
            color: white;
            padding: 20px 0;
            text-align: center;
            position: relative;
            animation: fadeIn 1s;
        }

        nav ul {
            list-style: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: #ffcc00; /* Change color on hover */
        }

        main {
            padding: 20px;
        }

        h2 {
            color: #007BFF;
        }

        article {
            margin-bottom: 20px;
            padding: 15px;
            background: white;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }

        article:hover {
            transform: scale(1.02);
        }

        .video-gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }

        video {
            width: 100%;
            max-width: 400px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        footer {
            text-align: center;
            padding: 10px 0;
            background: #007BFF;
            color: white;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to MSKXplore</h1>
        <nav>
            <ul>
                <li><a href="#blogs">Blogs</a></li>
                <li><a href="#vlogs">Vlogs</a></li>
                <li><a href="#adventures">Adventures</a></li>
                <li><a href="#cyber-awareness">Cyber Awareness</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="blogs">
            <h2>Blogs</h2>
            <article>
                <h3>My Daily Activities</h3>
                <p>Content about daily activities...</p>
            </article>
            <article>
                <h3>Special Occasions</h3>
                <p>Content about special occasions in my life...</p>
            </article>
            <!-- More blog articles can be added here -->
        </section>

        <section id="vlogs">
            <h2>Vlogs</h2>
            <div class="video-gallery">
                <video controls>
                    <source src="video.mp4" type="video/mp4">
                    Your browser does not support the video tag.
                </video>
                <!-- More videos can be added here -->
            </div>
        </section>

        <section id="adventures">
            <h2>Adventurous Trips</h2>
            <p>Content about trips and excursions...</p>
        </section>

        <section id="cyber-awareness">
            <h2>Cyber Awareness Tips</h2>
            <p>Content about cyber safety...</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 MSKXplore. All rights reserved.</p>
    </footer>
</body>
</html>
