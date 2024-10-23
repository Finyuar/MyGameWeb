# MyGameWeb
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Game Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Game World!</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#games">Games</a></li>
                <li><a href="#blog">Blog</a></li>
                <li><a href="#live">Live Stream</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>About Me</h2>
        <p>Hello! I'm a passionate gamer who loves exploring the world of video games, especially Genshin Impact.</p>
    </section>

    <section id="games">
        <h2>My Favorite Games</h2>
        <div class="game">
            <h3>Genshin Impact</h3>
            <p>A beautiful open-world RPG.</p>
        </div>
        <div class="game">
            <h3>Game 2</h3>
            <p>Description of Game 2.</p>
        </div>
    </section>

    <section id="blog">
        <h2>Blog</h2>
        <article>
            <h3>Game Review</h3>
            <p>This is a brief review of a game.</p>
        </article>
    </section>

    <section id="live">
        <h2>Live Streaming</h2>
        <p>Watch me play live on <a href="https://www.twitch.tv/yourchannel" target="_blank">Twitch</a>.</p>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 My Game Website</p>
    </footer>
</body>
</html>
