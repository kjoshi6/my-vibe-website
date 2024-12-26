# my-vibe-website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Krisha's Vibe</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">Krisha's Vibe</div>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#vibe-quiz">Vibe Quiz</a></li>
                <li><a href="#blog">Blog</a></li>
            </ul>
        </nav>
    </header>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Krisha's Vibe</title>
    <link rel="stylesheet" href="styles.css"> <!-- Linking CSS -->
</head>
<body>
    <header>
        <nav>
            <div class="logo">Krisha's Vibe</div>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#vibe-quiz">Vibe Quiz</a></li>
                <li><a href="#blog">Blog</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="hero">
        <h1>Welcome to My Vibe</h1>
        <p>Explore my world through my passions, photography, and interactive experiences.</p>
    </section>

    <section id="portfolio">
        <h2>My Portfolio</h2>
        <div class="gallery">
            <!-- Add your photos here -->
            <img src="image1.jpg" alt="Photo 1">
            <img src="image2.jpg" alt="Photo 2">
            <img src="image3.jpg" alt="Photo 3">
        </div>
    </section>

    <section id="vibe-quiz" class="quiz">
        <h2>What's Your Vibe Today?</h2>
        <button class="quiz-btn">Take the Quiz</button>
    </section>

    <section id="blog">
        <h2>Blog</h2>
        <p>Get a glimpse into my daily life, activities, and adventures.</p>
    </section>

    <footer>
        <p>&copy; 2024 Krisha's Vibe | Built with love & crea

    <section id="home" class="hero">
        <h1>Welcome to My Vibe</h1>
        <p>Explore my world through my passions, photography, and interactive experiences.</p>
    </section>

    <section id="portfolio">
        <h2>My Portfolio</h2>
        <div class="gallery">
            <!-- Add images for your photography here -->
            <img src="image1.jpg" alt="Photo 1">
            <img src="image2.jpg" alt="Photo 2">
            <img src="image3.jpg" alt="Photo 3">
        </div>
    </section>

    <section id="vibe-quiz" class="quiz">
        <h2>What's Your Vibe Today?</h2>
        <button class="quiz-btn">Take the Quiz</button>
    </section>

    <section id="blog">
        <h2>Blog</h2>
        <p>Get a glimpse into my daily life, activities, and adventures.</p>
    </section>

    <footer>
        <p>&copy; 2024 Krisha's Vibe | Built with love & creativity.</p>
    </footer>
</body>
</html>
/* General Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body */
body {
    font-family: 'Arial', sans-serif;
    background-color: #f9f9f9;
    color: #333;
    line-height: 1.6;
    padding: 20px;
}

/* Header */
header {
    background-color: #1a1a1a;
    color: #fff;
    padding: 20px 0;
}

header nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 20px;
}

header nav .logo {
    font-size: 1.5rem;
    font-weight: bold;
}

header nav ul {
    display: flex;
    list-style-type: none;
}

header nav ul li {
    margin: 0 15px;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 1.1rem;
}

header nav ul li a:hover {
    text-decoration: underline;
}

/* Hero Section */
.hero {
    background-color: #ffe4e1;  /* pastel pink */
    padding: 50px 20px;
    text-align: center;
    border-radius: 10px;
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
}

.hero h1 {
    font-size: 2.5rem;
    color: #2e2e2e;
}

.hero p {
    font-size: 1.1rem;
    color: #4f4f4f;
}

/* Portfolio Section */
#portfolio {
    background-color: #ffffff;
    padding: 40px 20px;
    margin-top: 40px;
    border-radius: 10px;
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
}

#portfolio h2 {
    font-size: 2rem;
    color: #2e2e2e;
    margin-bottom: 20px;
}

.gallery {
    display: flex;
    gap: 15px;
    flex-wrap: wrap;
}

.gallery img {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease-in-out;
}

.gallery img:hover {
    transform: scale(1.05);
}

/* Vibe Quiz Section */
#vibe-quiz {
    background-color: #b1e0b9; /* light lime green */
    padding: 40px 20px;
    text-align: center;
    margin-top: 40px;
    border-radius: 10px;
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
}

.quiz-btn {
    background-color: #ff4f5a; /* maroon */
    color: #fff;
    border: none;
    padding: 12px 25px;
    font-size: 1.2rem;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s;
}

.quiz-btn:hover {
    background-color: #d93f44;
}

/* Blog Section */
#blog {
    background-color: #f1f1f1;
    padding: 40px 20px;
    margin-top: 40px;
    border-radius: 10px;
    text-align: center;
}

#blog h2 {
    font-size: 2rem;
    color: #2e2e2e;
    margin-bottom: 20px;
}

/* Footer */
footer {
    background-color: #1a1a1a;
    color: #fff;
    text-align: center;
    padding: 20px 0;
    margin-top: 40px;
}
