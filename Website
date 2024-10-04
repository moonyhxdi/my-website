<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Portfolio of Digital Artworks by Moony">
    <title>Moony's Digital Art Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Fredoka+One&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Fredoka One', sans-serif;
            background-color: #1260cc; /* Dark baby blue background */
            overflow-x: hidden;
        }

        header {
            color: #fff;
            text-align: center;
            padding: 20px 0;
            width: 100%;
            z-index: 10;
        }

        header h1 {
            margin: 0;
            font-size: 4rem; /* Larger, bolder text */
        }

        /* Raining Animation Background */
        .rain {
            position: fixed;
            top: 0;
            left: 0;
            width: 100vw;
            height: 100vh;
            pointer-events: none;
            overflow: hidden;
            z-index: -1; /* Push behind other content */
        }

        .drop {
            position: absolute;
            bottom: 100%;
            width: 5px;
            height: 80px;
            background: rgba(0, 0, 0, 0.2);
            animation: fall linear infinite;
        }

        @keyframes fall {
            to {
                transform: translateY(100vh);
            }
        }

        /* Generate multiple raindrops */
        .drop:nth-child(1) {
            left: 10%;
            animation-duration: 1s;
        }
        .drop:nth-child(2) {
            left: 30%;
            animation-duration: 0.8s;
        }
        .drop:nth-child(3) {
            left: 50%;
            animation-duration: 1.2s;
        }
        .drop:nth-child(4) {
            left: 70%;
            animation-duration: 1s;
        }
        .drop:nth-child(5) {
            left: 90%;
            animation-duration: 1.1s;
        }
        .drop:nth-child(6) {
            left: 15%;
            animation-duration: 0.9s;
        }
        .drop:nth-child(7) {
            left: 25%;
            animation-duration: 1.3s;
        }
        .drop:nth-child(8) {
            left: 60%;
            animation-duration: 0.7s;
        }
        .drop:nth-child(9) {
            left: 85%;
            animation-duration: 1.4s;
        }

        .container {
            padding-top: 70px; /* Adjusted top padding for the header */
            padding-left: 20px;
            padding-right: 20px;
            padding-bottom: 20px;
            display: flex;
            justify-content: center; /* Center content horizontally */
        }

        .portfolio-grid {
            display: flex;
            flex-direction: column;
            gap: 30px; /* Reduced gap between items */
            align-items: center; /* Center items horizontally */
        }

        .portfolio-item {
            background-color: #fff;
            border-radius: 20px; /* Rounded corners for a softer feel */
            overflow: hidden;
            box-shadow: 0 6px 10px rgba(0, 0, 0, 0.1); /* Lighter shadow */
            transition: transform 0.3s ease-in-out, opacity 1s ease-in-out; /* Smooth transition for opacity */
            text-align: center;
            width: 50%; /* Reduced width to 50% of the page */
            opacity: 1; /* Not fully faded out */
            transform: translateY(50px); /* Start slightly translated for the effect */
        }

        .portfolio-item.visible {
            opacity: 0.3; /* Fade-in effect when in view */
            transform: translateY(0); /* Reset the transform */
        }

        /* Grow effect on hover */
        .portfolio-item:hover {
            transform: scale(1.05); /* Slightly grow the image on hover */
        }

        .portfolio-item img {
            width: 100%; /* Maintain responsive width */
            height: auto; /* Maintain aspect ratio */
            border-bottom: 5px solid #cccccc; /* Light grey cartoony border under images */
        }

        footer {
            background-color: #6e6e6e; /* Grey color */
            color: #fff;
            text-align: center;
            padding: 10px 0;
            width: 100%;
            box-shadow: 0 -4px 6px rgba(0, 0, 0, 0.2);
        }

        footer p {
            margin: 0;
            font-size: 1.5rem;
        }

        @media(max-width: 768px) {
            footer p {
                font-size: 1.2rem;
            }

            .portfolio-item {
                width: 80%; /* Make items larger on smaller screens */
            }
        }
   p {
    text-align: right;
}
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Moony's Portfolio</h1>
    </header>

    <!-- Rain animation background -->
    <div class="rain">
        <!-- Generate a series of drops -->
        <div class="drop"></div>
        <div class="drop"></div>
        <div class="drop"></div>
        <div class="drop"></div>
        <div class="drop"></div>
        <div class="drop"></div>
        <div class="drop"></div>
        <div class="drop"></div>
        <div class="drop"></div>
    </div>

    <div class="container">
        <section class="portfolio-grid">
            <!-- 10 Portfolio items for scrolling (images only, no titles) -->
            <div class="portfolio-item">
                <img src="https://pbs.twimg.com/media/GYoxYAcXMAANKbM?format=jpg&name=large" alt="Artwork 1"> <!-- Example image -->
            </div>
            <div class="portfolio-item">
                <img src="https://pbs.twimg.com/media/GYq2ZUqWoAAgz-D?format=jpg&name=large" alt="Artwork 2"> <!-- Example image -->
            </div>
            <div class="portfolio-item">
                <img src="https://pbs.twimg.com/media/GYq2NAcWsAA-o1O?format=jpg&name=large" alt="Artwork 3"> <!-- Example image -->
            </div>
            <div class="portfolio-item">
                <img src="https://pbs.twimg.com/media/GYRZrEcWMAAgnzk?format=jpg&name=medium" alt="Artwork 4"> <!-- Example image -->
            </div>
            <div class="portfolio-item">
                <img src="https://pbs.twimg.com/media/GYRZrEZXgAAfhAt?format=jpg&name=large" alt="Artwork 5"> <!-- Example image -->
            </div>
            <div class="portfolio-item">
                <img src="https://pbs.twimg.com/media/GYEIsuOXUAAYZLX?format=jpg&name=medium" alt="Artwork 6"> <!-- Example image -->
            </div>
            <div class="portfolio-item">
                <img src="https://pbs.twimg.com/media/GYAgyURXgAAlqmn?format=jpg&name=large" alt="Artwork 7"> <!-- Example image -->
            </div>
            <div class="portfolio-item">
                <img src="https://pbs.twimg.com/media/GX2e5U3X0AEQUGp?format=jpg&name=medium" alt="Artwork 8"> <!-- Example image -->
            </div>
            <div class="portfolio-item">
                <img src="https://pbs.twimg.com/media/GX2e5U0XUAElDwe?format=jpg&name=large" alt="Artwork 9"> <!-- Example image -->
            </div>
            <div class="portfolio-item">
                <img src="https://pbs.twimg.com/media/GYoz-eNXoAEDicL?format=jpg&name=large"> <!-- Example image -->
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Moony. All rights reserved.</p>
    </footer>

    <script>
        // Function to check if an element is in the viewport
        function isInViewport(el) {
            const rect = el.getBoundingClientRect();
            return (
                rect.top >= 0 &&
                rect.left >= 0 &&
                rect.bottom <= (window.innerHeight || document.documentElement.clientHeight) &&
                rect.right <= (window.innerWidth || document.documentElement.clientWidth)
            );
        }

        // Function to fade elements in and out based on their visibility
        function checkVisibility() {
            const portfolioItems = document.querySelectorAll('.portfolio-item');
            portfolioItems.forEach(item => {
                if (isInViewport(item)) {
                    item.classList.add('visible
