<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta name="description" content="Abdallah Ibrahim - PHP Laravel Full Stack Developer with 3+ years experience in web development">
        <meta name="keywords" content="PHP, Laravel, Full Stack Developer, Web Development, Node.js, Angular">
        
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&family=JetBrains+Mono:wght@400;500;600&display=swap" rel="stylesheet">
        <link rel="stylesheet" href="style.css">

        <title>Abdallah Ibrahim - Full Stack Developer</title>
    </head>
<body>
    <!-- Navigation -->
    <nav class="navbar" role="navigation" aria-label="Main navigation">
        <div class="nav-container">
            <a href="./index.html" class="nav-logo" aria-label="Abdallah Ibrahim Home">
                <span class="logo-text">Abdallah Ibrahim</span>
            </a>

            <div class="nav-menu" id="nav-menu">
                <a href="#services" class="nav-link">Services</a>
                <a href="#projects" class="nav-link">Projects</a>
                <a href="#contact" class="nav-link">Contact</a>
                <button class="theme-toggle" id="theme-toggle" aria-label="Toggle dark mode">
                    <i class="fas fa-moon"></i>
                </button>
            </div>

            <div class="hamburger" id="hamburger" aria-label="Toggle navigation menu">
                <span class="bar"></span>
                <span class="bar"></span>
                <span class="bar"></span>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="hero-container">
            <div class="hero-content">
                <div class="hero-text">
                    <h1 class="hero-title">
                        Hello, I'm <span class="highlight">Abdallah Ibrahim</span>
                    </h1>
                    <h2 class="hero-subtitle">PHP Laravel Full Stack Developer</h2>
                    <p class="hero-description">
                        I am offering 3+ years of experience in the Software Development field (Full Stack Backend Mainly).
                        College graduate seeking a technical position with extensive technical experience at NTI.
                        Motivated, enthusiastic and committed to be an added value employee at my work.
                    </p>
                    <div class="hero-buttons">
                        <a href="./Abdallah Ibrahim CV.pdf" download="Abdallah_Ibrahim_CV.pdf" class="btn btn-primary">
                            <i class="fas fa-download"></i>
                            Download Resume
                        </a>
                        <a href="#contact" class="btn btn-secondary">
                            <i class="fas fa-envelope"></i>
                            Get In Touch
                        </a>
                    </div>
                    <div class="social-links">
                        <a href="https://www.linkedin.com/in/abdallah-ibrahim-0a2b15156/" target="_blank" rel="noopener noreferrer" aria-label="LinkedIn Profile">
                            <i class="fab fa-linkedin"></i>
                        </a>
                        <a href="https://github.com/M45CJ3J" target="_blank" rel="noopener noreferrer" aria-label="GitHub Profile">
                            <i class="fab fa-github"></i>
                        </a>
                    </div>
                </div>
                <div class="hero-image">
                    <div class="image-container">
                        <img src="./img/abido.jpeg" alt="Abdallah Ibrahim" class="profile-image">
                        <div class="image-overlay"></div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section class="services" id="services">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title">Services</h2>
                <p class="section-subtitle">What I can do for you</p>
            </div>
            <div class="services-grid">
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-code"></i>
                    </div>
                    <h3 class="service-title">Web Development</h3>
                    <p class="service-description">
                        Creating modern web applications and RESTful APIs using Laravel and Node.js for both web and mobile applications.
                    </p>
                </div>
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-mobile-alt"></i>
                    </div>
                    <h3 class="service-title">API Development</h3>
                    <p class="service-description">
                        Building robust backend APIs and endpoints for mobile apps and frontend frameworks with proper documentation.
                    </p>
                </div>
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-database"></i>
                    </div>
                    <h3 class="service-title">Database Design</h3>
                    <p class="service-description">
                        Designing and optimizing database schemas for scalable applications with complex data relationships.
                    </p>
                </div>
            </div>
        </div>
    </section>
 
    <!-- Projects Section -->
    <section class="projects" id="projects">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title">Featured Projects</h2>
                <p class="section-subtitle">A showcase of my recent work</p>
            </div>
            
            <div class="project-filters">
                <button class="filter-btn active" data-filter="all">All Projects</button>
                <button class="filter-btn" data-filter="laravel">Laravel</button>
                <button class="filter-btn" data-filter="angular">Angular</button>
                <button class="filter-btn" data-filter="nodejs">Node.js</button>
                <button class="filter-btn" data-filter="codeignitor">CodeIgniter</button>
            </div>

            <div class="projects-grid" id="projects-grid">
                <!-- Projects will be dynamically loaded here -->
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact" id="contact">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title">Let's Work Together</h2>
                <p class="section-subtitle">Ready to bring your ideas to life?</p>
            </div>
            <div class="contact-content">
                <div class="contact-info">
                    <div class="contact-card">
                        <div class="contact-icon">
                            <i class="fas fa-phone"></i>
                        </div>
                        <div class="contact-details">
                            <h3>Phone</h3>
                            <p>+201124093527</p>
                        </div>
                    </div>
                    <div class="contact-card">
                        <div class="contact-icon">
                            <i class="fas fa-envelope"></i>
                        </div>
                        <div class="contact-details">
                            <h3>Email</h3>
                            <p>abdallanasr505@gmail.com</p>
                        </div>
                    </div>
                    <div class="contact-card">
                        <div class="contact-icon">
                            <i class="fas fa-map-marker-alt"></i>
                        </div>
                        <div class="contact-details">
                            <h3>Location</h3>
                            <p>Egypt</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <div class="footer-content">
                <p>&copy; 2024 Abdallah Ibrahim. All rights reserved.</p>
                <div class="footer-social">
                    <a href="https://www.linkedin.com/in/abdallah-ibrahim-0a2b15156/" target="_blank" rel="noopener noreferrer" aria-label="LinkedIn">
                        <i class="fab fa-linkedin"></i>
                    </a>
                    <a href="https://github.com/M45CJ3J" target="_blank" rel="noopener noreferrer" aria-label="GitHub">
                        <i class="fab fa-github"></i>
                    </a>
                </div>
            </div>
        </div>
    </footer>

    <script src="json.js"></script>
    <script src="script.js"></script>
      
</body>
</html>
