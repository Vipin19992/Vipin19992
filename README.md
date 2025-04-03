https://vipin19992.github.io/Ultimate-Gym/
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Ultimate Gym</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@picocss/pico@1/css/pico.min.css">
</head>
<body>
    <nav class="container-fluid">
        <ul>
            <li><strong>Ultimate Gym</strong></li>
        </ul>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#membership" role="button">Join Now</a></li>
        </ul>
    </nav>
    
    <main class="container">
        <div class="grid">
            <section>
                <hgroup>
                    <h2>Welcome to Ultimate Gym</h2>
                    <h3>Unleash Your Potential</h3>
                </hgroup>
                <p>Achieve your dream physique with our world-class fitness programs and expert trainers.</p>
                
                <figure>
                    <img src="https://source.unsplash.com/800x500/?muscular-bodybuilder" alt="Muscular Bodybuilder">
                    <figcaption><a href="https://unsplash.com/s/photos/muscular-bodybuilder" target="_blank">Image Source</a></figcaption>
                </figure>
                
                <figure>
                    <img src="https://source.unsplash.com/800x500/?fitness,workout" alt="Intense Workout">
                    <figcaption><a href="https://unsplash.com/s/photos/fitness-workout" target="_blank">Image Source</a></figcaption>
                </figure>
                
                <h3>Contact Person</h3>
                <p><strong>Name:</strong> Ajeet Yadav</p>
                <p><strong>Phone:</strong> <a href="tel:9691287440">96912 87440</a></p>
                <p><strong>Address:</strong> Ganeshpura No. 2, School Ke Samne</p>
            </section>
        </div>
    </main>
    
    <section aria-label="Subscribe example">
        <div class="container">
            <article>
                <hgroup>
                    <h2>Join Our Gym Community</h2>
                    <h3>Subscribe for updates & special offers</h3>
                </hgroup>
                <form class="grid">
                    <input type="text" id="firstname" name="firstname" placeholder="Your Name" aria-label="Your Name" required>
                    <input type="email" id="email" name="email" placeholder="Your Email" aria-label="Your Email" required>
                    <button type="submit" onclick="event.preventDefault()">Subscribe</button>
                </form>
            </article>
        </div>
    </section>
    
    <footer class="container">
        <small><a href="#">Privacy Policy</a> • <a href="#">Terms of Service</a></small>
    </footer>
</body>
</html>
