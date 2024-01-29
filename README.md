<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em;
        }

        #banner {
            width: 100%;
            height: 300px;
            background: url('banner-image.jpg') center/cover no-repeat;
            text-align: center;
            color: white;
            display: flex;
            flex-direction: column;
            justify-content: center;
        }

        section {
            padding: 20px;
        }

        .quote {
            font-style: italic;
            text-align: center;
            margin-bottom: 20px;
        }

        .video-list {
            list-style: none;
            padding: 0;
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }

        .video-list li {
            width: 30%;
            margin-bottom: 20px;
        }

        .faq {
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .membership {
            background-color: #3498db;
            color: white;
            padding: 20px;
            text-align: center;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em;
            position: absolute;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>

<body>

    <header>
        <h1>Your Website</h1>
    </header>

    <div id="banner">
        <h2>Welcome to Our Website</h2>
        <p>Your tagline goes here</p>
    </div>

    <section>
        <div class="quote">
            <blockquote>
                "hate you to much."
            </blockquote>
        </div>

        <ul class="video-list">
            <li><iframe width="300" height="200" src="https://www.youtube.com/embed/example-video-1" frameborder="0" allowfullscreen></iframe></li>
            <li><iframe width="300" height="200" src="https://www.youtube.com/embed/example-video-2" frameborder="0" allowfullscreen></iframe></li>
            <li><iframe width="300" height="200" src="https://www.youtube.com/embed/example-video-3" frameborder="0" allowfullscreen></iframe></li>
        </ul>

        <div class="faq">
            <h2>Frequently Asked Questions</h2>
            <p>Q: Your question goes here?</p>
            <p>A: Your answer goes here.</p>
            <!-- Repeat as needed -->
        </div>

        <div class="membership">
            <h2>Join Our Membership Program</h2>
            <p>Unlock exclusive content and benefits. Become a member today!</p>
            <button>Join Now</button>
        </div>
    </section>

    <footer>
        &copy; 2024 Your Website. All rights reserved.
    </footer>

</body>

</html>
