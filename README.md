<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shijal Mishra | Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Header with navigation -->
    <header>
        <nav>
            <div class="nav-brand">UNITY</div>
            <div class="nav-menu">
                <a href="#home" class="active">Home</a>
                <a href="#about">About</a>
                <a href="#skills">Skills</a>
                <a href="#projects">Projects</a>
                <a href="#contact">Contact</a>
            </div>
        </nav>
    </header>

    <!-- Home Section -->
    <section id="home" class="home">
        <div class="home-content">
            <img src="C:\Users\Lenovo\OneDrive\Desktop\Pictures\shijal.jpg" alt="Shijal Mishra" class="profile-img">
            <h1>Shijal Mishra</h1>
            <p>Frontend Developer</p>
            <a href="#projects" class="cta-btn">View My Work</a>
        </div>
    
        <div class="home-content">
            <img src="C:\Users\Lenovo\OneDrive\Desktop\GROUPPROTFOLIO\YESWANTHIRA.jpg" alt="Yeswanthira" class="profile-img">
            <h1>Yeswanthira</h1>
            <p>Cloud Computing</p>
            <a href="#projects" class="cta-btn">View My Work</a>
        </div>
    
        <div class="home-content">
            <img src="C:\Users\Lenovo\OneDrive\Desktop\GROUPPROTFOLIO\SRINITHI.jpg" alt="Srinithi" class="profile-img">
            <h1>Srinithi</h1>
            <p>UI UX DESIGNER</p>
            <a href="#projects" class="cta-btn">View My Work</a>
        </div>
    </section>
    

 <!-- About Us Section -->
<section id="about" class="about">
    <h2>About Us</h2>
    <div class="about-content">
        <div class="triangle-images">
            <div class="triangle-img">
                <img src="C:\Users\Lenovo\OneDrive\Desktop\Pictures\shijal.jpg" alt="Shijal Mishra" class="about-img">
                <p>Shijal Mishra</p>
            </div>
            <div class="triangle-img">
                <img src="C:\Users\Lenovo\OneDrive\Desktop\GROUPPROTFOLIO\YESWANTHIRA.jpg" alt="Yeswanthira" class="about-img">
                <p>Yeswanthira</p>
               
            </div>
            <div class="triangle-img">
                <img src="C:\Users\Lenovo\OneDrive\Desktop\GROUPPROTFOLIO\SRINITHI.jpg" alt="Srinithi" class="about-img">
                <p>Srinithi</p>
            </div>
        </div>
        <p>We are a passionate team dedicated to creating innovative solutions and delivering the best user experiences. With expertise in frontend development, cloud computing, and UI/UX design, we work together to bring cutting-edge ideas to life. We are committed to constantly improving and adopting new technologies to meet the challenges of the digital world.</p>
    </div>
</section>

    <!-- Skills Section -->
    <section id="skills" class="skills">
        <h2>Our Skills</h2>
        <div class="skills-content">
            <div class="skill">
                <h3>HTML5/CSS3</h3>
                <div class="progress-bar">
                    <div class="progress" style="width: 95%"></div>
                </div>
            </div>
            <div class="skill">
                <h3>JavaScript</h3>
                <div class="progress-bar">
                    <div class="progress" style="width: 90%"></div>
                </div>
            </div>
            <div class="skill">
                <h3>C</h3>
                <div class="progress-bar">
                    <div class="progress" style="width: 85%"></div>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="projects">
        <h2>Projects</h2>
        <div class="project-card">
            <img src="C:\Users\Lenovo\Downloads\barcelona\website-development-project-plan.webp" alt="Project 1">
            <div class="project-info">
                <h3>Project 1</h3>
                <p>In this project, I built a fully-functional e-commerce website for a small business, allowing customers to browse products, add them to a shopping cart, and proceed to checkout with an integrated payment gateway. The website is built using React for dynamic content and Node.js for the backend, ensuring a fast, secure, and user-friendly shopping experience. I also implemented a content management system (CMS) so the client can easily manage inventory and track orders</p>
                <a href="#">View Live</a>
                <a href="#">View Source Code</a>
            </div>
        </div>
        <!-- Add more projects as needed -->
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2>Get In Touch</h2>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Shijal Mishra</p>
        <div class="social-links">
            <a href="https://github.com/Shijal1" target="_blank">GitHub: Shijal1</a> | 
            <a href="https://instagram.com/ok_sir44" target="_blank">Instagram: @oksir_44</a> |
            <a href="https://github.com/Srinithi-06------srinithi's" target="_blank">GitHub: Srinithi-06</a> |
            <a href="https://github.com/Yeso05" target="_blank">GitHub: Yeso05</a>
        </div>
    </footer>

    <script src="js/script.js"></script>
</body>
</html>

<!--......................................................................................................................................................................-->


/* Reset and Base Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Poppins', sans-serif;
    line-height: 1.6;
    color: #333;
    scroll-behavior: smooth;
    background: #f0f4f8; /* Subtle background color */
}

/* Header and Navigation */
header {
    position: fixed;
    top: 0;
    width: 100%;
    background: rgba(13, 12, 12, 0.7); /* Slight dark background */
    box-shadow: 0 2px 10px rgba(171, 11, 11, 0.3);
    z-index: 1000;
    transition: background 0.3s ease;
}

header:hover {
    background: rgba(13, 12, 12, 1); /* Darker on hover for dynamic effect */
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 5%;
    max-width: 1200px;
    margin: 0 auto;
    position: relative;
    z-index: 2;
}

.nav-brand {
    font-size: 1.6rem;
    font-weight: 700;
    color: #f5f6fa;
    letter-spacing: 2px;
    transition: color 0.3s ease;
}

.nav-brand:hover {
    color: #0984e3;
}

.nav-menu a {
    text-decoration: none;
    color: #dfe6e9;
    margin-left: 2rem;
    position: relative;
    padding: 0.5rem 0;
    transition: color 0.3s, transform 0.3s ease;
}

.nav-menu a:hover,
.nav-menu a.active {
    color: #0984e3;
    transform: translateY(-5px);
}

.nav-menu a::after {
    content: '';
    position: absolute;
    bottom: 0;
    left: 0;
    width: 0;
    height: 2px;
    background: #0984e3;
    transition: width 0.3s ease;
}

.nav-menu a:hover::after,
.nav-menu a.active::after {
    width: 100%;
}

/* Home Section */
.home {
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 0 1rem;
    background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
    gap: 3rem;
    flex-wrap: wrap;
    animation: slideIn 1s ease-out forwards;
}

.home-content {
    text-align: center;
    transform: translateY(20px);
    animation: fadeInUp 1s ease-out forwards;
}

.profile-img {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    margin-bottom: 2rem;
    border: 5px solid white;
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
    object-fit: cover;
    transition: transform 0.5s ease-in-out;
}

.profile-img:hover {
    transform: scale(1.1);
}

.home h1 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
    color: #2d3436;
    animation: fadeInUp 1s ease-out forwards;
}

.home p {
    font-size: 1.2rem;
    color: #636e72;
    margin-bottom: 2rem;
    animation: fadeInUp 1s ease-out forwards;
}

.cta-btn {
    display: inline-block;
    padding: 1rem 2rem;
    background: #0984e3;
    color: white;
    text-decoration: none;
    border-radius: 30px;
    transition: transform 0.3s, box-shadow 0.3s ease;
}

.cta-btn:hover {
    transform: translateY(-3px);
    box-shadow: 0 5px 15px rgba(9, 132, 227, 0.4);
}

/* About Us Section */
.about {
    padding: 6rem 5%;
    max-width: 1200px;
    margin: 0 auto;
    background: linear-gradient(135deg, #ffb3b3 0%, #ff6666 100%); /* Soft warm gradient */
    background-image: url('https://www.transparenttextures.com/patterns/soft-shadow.png'); /* Subtle fabric texture */
    background-size: 200%;
    border-radius: 10px;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.15); /* Subtle shadow to create depth */
    position: relative;
    overflow: hidden;
    animation: fadeInUp 1s ease-out forwards;
}

.about:before {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(255, 255, 255, 0.3); /* Light frosted effect */
    z-index: 0;
    transform: scale(1.2);
    animation: pulse 5s infinite ease-in-out;
}

.about h2 {
    text-align: center;
    margin-bottom: 3rem;
    font-size: 2.5rem;
    color: #2d3436;
    text-transform: uppercase;
    letter-spacing: 2px;
    font-weight: 600;
    z-index: 1;
    position: relative;
    animation: fadeInUp 1s ease-out forwards;
}

.about-content {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
    gap: 2rem;
    position: relative;
    z-index: 1;
    animation: fadeInUp 1s ease-out forwards;
}

.about-content p {
    font-size: 1.2rem;
    color: #636e72;
    line-height: 1.8;
    margin-top: 1rem;
    max-width: 800px;
    margin-left: auto;
    margin-right: auto;
    z-index: 1;
}

.triangle-images {
    display: flex;
    justify-content: center;
    gap: 2rem;
    flex-wrap: wrap;
    z-index: 1;
}

.triangle-img {
    width: 180px;
    text-align: center;
    flex-shrink: 0;
    position: relative;
    transition: transform 0.5s ease, box-shadow 0.3s ease;
    animation: fadeInUp 1s ease-out forwards;
}

.triangle-img:hover {
    transform: scale(1.05);
    box-shadow: 0 5px 30px rgba(0, 0, 0, 0.2);
}

.triangle-img img {
    width: 100%;
    height: 100%;
    border-radius: 50%;
    border: 5px solid white;
    object-fit: cover;
}

.triangle-img p {
    font-size: 1rem;
    color: #2d3436;
    margin-top: 0.5rem;
    font-weight: 500;
}

/* Skills Section */
.skills {
    padding: 6rem 5%;
    background: #f5f7fa;
}

.skills h2 {
    text-align: center;
    margin-bottom: 3rem;
    font-size: 2rem;
    color: #2d3436;
    animation: fadeInUp 1s ease-out forwards;
}

.skills-content {
    max-width: 800px;
    margin: 0 auto;
}

.skill {
    margin-bottom: 2rem;
}

.skill h3 {
    margin-bottom: 0.5rem;
    color: #2d3436;
}

.progress-bar {
    background: #dfe6e9;
    height: 10px;
    border-radius: 5px;
    overflow: hidden;
}

.progress {
    height: 100%;
    background: #0984e3;
    border-radius: 5px;
    transition: width 1s ease-in-out;
}

/* Projects Section */
.projects {
    padding: 6rem 5%;
    max-width: 1200px;
    margin: 0 auto;
}

.projects h2 {
    text-align: center;
    margin-bottom: 3rem;
    font-size: 2rem;
    color: #2d3436;
}

.project-card {
    background: white;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
    margin-bottom: 2rem;
    transition: transform 0.3s ease-in-out;
}

.project-card:hover {
    transform: translateY(-5px);
}

.project-card img {
    width: 100%;
    height: 300px;
    object-fit: cover;
}

.project-info {
    padding: 2rem;
}

.project-info h3 {
    margin-bottom: 1rem;
    color: #2d3436;
}

.project-info a {
    display: inline-block;
    margin-right: 1rem;
    margin-top: 1rem;
    padding: 0.5rem 1rem;
    background: #0984e3;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    transition: background 0.3s ease;
}

.project-info a:hover {
    background: #0767b3;
}

/* Contact Section */
.contact {
    padding: 6rem 5%;
    background: #f5f7fa;
}

.contact h2 {
    text-align: center;
    margin-bottom: 3rem;
    font-size: 2rem;
    color: #2d3436;
}

form {
    max-width: 600px;
    margin: 0 auto;
}

form input,
form textarea {
    width: 100%;
    padding: 1rem;
    margin-bottom: 1rem;
    border: 1px solid #dfe6e9;
    border-radius: 5px;
    font-family: inherit;
}

form textarea {
    height: 150px;
    resize: vertical;
}

form button {
    display: block;
    width: 100%;
    padding: 1rem;
    background: #0984e3;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background 0.3s ease;
}

form button:hover {
    background: #0767b3;
}

/* Footer */
footer {
    text-align: center;
    padding: 2rem;
    background: #2d3436;
    color: white;
}

.social-links {
    margin-top: 1rem;
}

.social-links a {
    color: white;
    text-decoration: none;
    transition: color 0.3s ease;
}

.social-links a:hover {
    color: #0984e3;
}

/* Animations */
@keyframes fadeInUp {
    from {
        opacity: 0;
        transform: translateY(20px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

@keyframes slideIn {
    from {
        opacity: 0;
        transform: translateX(-50%);
    }
    to {
        opacity: 1;
        transform: translateX(0);
    }
}

@keyframes pulse {
    0% {
        transform: scale(1.1);
    }
    50% {
        transform: scale(1.15);
    }
    100% {
        transform: scale(1.1);
    }
}

section {
    animation: fadeInUp 1s ease-out;
}



<-- JS.....................................................................................................................................................................................................-->
// Smooth scrolling for navigation links
document.querySelectorAll('nav a').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();
        document.querySelector(this.getAttribute('href')).scrollIntoView({
            behavior: 'smooth'
        });
    });
});

