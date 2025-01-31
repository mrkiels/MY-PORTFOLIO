# MY-PORTFOLIO
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="active.css">
</head>
<body>
    <header>
        <div class="dropdown">
            <button class="deop-btn">Menu</button>
            <div class="dropdown-content">
                <a href="#home">Home</a>
                <a href="#about">About</a>
                <a href="#projects">Projects</a>
                <a href="#contact">Contact</a>
            </div>
        </div>
    </header>

    <section id="home" class="home-section">
        <h1 id="bla">Welcome to My Portfolio</h1>
        <p id="blu">Hello! I'm Adigun ezekiel Oluwaseun, a web developer.</p>
        <button><a href="#projects" id="blau">See My Work</a></button>
    </section>

    <section id="about" class="about-section">
        <h2>About Me</h2>
        <p>I am a passionate web developer with a love for creating functional and beautiful websites. I have experience in HTML, CSS, JavaScript, and more!</p>
    </section>

    <section id="projects" class="projects-section">
        <h2>My Projects</h2>
        <div class="project-gallery"></div>
            <div class="project-card">
                <h3>Project 1 
                    Overview
                </h3>
                <p>Design and develop an e-commerce website for an online retailer that sells clothing, accessories, and home goods. The website should provide a seamless user experience, easy navigation, and a secure checkout process.</p>
            </div>
            <div class="project-card">
                <h3>Project 2</h3>
                <p>Social Media Platform for a Niche Community

                    Overview
                    Design and develop a social media platform for a niche community of photographers. The platform should allow users to share their photos, connect with other photographers, and participate in discussions.
                    
                    Features
                    
                    1. User Profiles: Allow users to create profiles to showcase their photos and connect with other users.
                    2. Photo Sharing: Implement a photo sharing feature that allows users to upload and share their photos.
                    3. Discussion Forums: Create discussion forums for users to participate in discussions related to photography.
                    4. Groups: Allow users to create and join groups based on their interests.</p>
            </div>
            <div class="project-card">
                <h3>Project 3</h3>
                <p>An innovative task management app designed to help teams collaborate, track tasks, and increase productivity.</p>
            </div>
        </div>
    </section>

    <section id="contact" class="contact-section">
        <h2>Contact Me</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Oluwaseun.</p>
    </footer>
</body>
</html>
