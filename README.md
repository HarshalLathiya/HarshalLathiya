<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Harshal Lathiya - Professional Profile</title>
    <style>
        :root {
            --primary: #2962ff;
            --primary-dark: #0039cb;
            --secondary: #f5f5f5;
            --text: #333333;
            --text-light: #666666;
            --accent: #00c853;
            --background: #ffffff;
            --card-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            --transition: all 0.3s ease;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: var(--secondary);
            color: var(--text);
            line-height: 1.6;
            padding: 0;
            margin: 0;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        header {
            background: linear-gradient(135deg, var(--primary), var(--primary-dark));
            color: white;
            padding: 60px 20px;
            text-align: center;
            margin-bottom: 30px;
        }
        
        .header-content {
            max-width: 800px;
            margin: 0 auto;
        }
        
        h1 {
            font-size: 2.8rem;
            margin-bottom: 10px;
            font-weight: 700;
        }
        
        h2 {
            font-size: 1.8rem;
            margin-bottom: 20px;
            color: var(--primary);
            font-weight: 600;
        }
        
        h3 {
            font-size: 1.4rem;
            margin-bottom: 15px;
            color: var(--primary-dark);
        }
        
        p {
            margin-bottom: 15px;
            font-size: 1.05rem;
        }
        
        .tagline {
            font-size: 1.4rem;
            margin-bottom: 25px;
            font-weight: 300;
        }
        
        .badge-container {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 10px;
            margin: 25px 0;
        }
        
        .badge {
            display: inline-block;
            padding: 8px 16px;
            background-color: rgba(255, 255, 255, 0.2);
            border-radius: 50px;
            font-size: 0.9rem;
            transition: var(--transition);
        }
        
        .badge:hover {
            background-color: rgba(255, 255, 255, 0.3);
            transform: translateY(-2px);
        }
        
        .section {
            background-color: var(--background);
            border-radius: 10px;
            padding: 30px;
            margin-bottom: 30px;
            box-shadow: var(--card-shadow);
        }
        
        .about-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 30px;
        }
        
        @media (max-width: 768px) {
            .about-grid {
                grid-template-columns: 1fr;
            }
        }
        
        .tech-stack {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
        }
        
        .tech-category {
            margin-bottom: 25px;
        }
        
        .tech-items {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        
        .tech-item {
            background-color: var(--secondary);
            padding: 8px 15px;
            border-radius: 5px;
            font-size: 0.9rem;
            transition: var(--transition);
        }
        
        .tech-item:hover {
            background-color: var(--primary);
            color: white;
            transform: translateY(-2px);
        }
        
        .stats-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        
        .stat-card {
            background: linear-gradient(135deg, #f5f5f5, #e0e0e0);
            padding: 20px;
            border-radius: 8px;
            text-align: center;
            transition: var(--transition);
        }
        
        .stat-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
        }
        
        .stat-value {
            font-size: 2.2rem;
            font-weight: 700;
            color: var(--primary);
            margin-bottom: 5px;
        }
        
        .stat-label {
            font-size: 1rem;
            color: var(--text-light);
        }
        
        .contact-links {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 15px;
            margin-top: 20px;
        }
        
        .contact-link {
            display: inline-flex;
            align-items: center;
            padding: 12px 25px;
            background-color: var(--primary);
            color: white;
            text-decoration: none;
            border-radius: 50px;
            font-weight: 500;
            transition: var(--transition);
        }
        
        .contact-link:hover {
            background-color: var(--primary-dark);
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(41, 98, 255, 0.3);
        }
        
        .quote {
            text-align: center;
            font-style: italic;
            color: var(--text-light);
            margin: 40px 0;
            padding: 20px;
            border-left: 4px solid var(--primary);
            background-color: rgba(41, 98, 255, 0.05);
        }
        
        .highlight {
            color: var(--primary);
            font-weight: 600;
        }
        
        .divider {
            height: 2px;
            background: linear-gradient(to right, transparent, var(--primary), transparent);
            margin: 40px 0;
            border: none;
        }
    </style>
</head>
<body>
    <header>
        <div class="header-content">
            <h1>Harshal Lathiya</h1>
            <p class="tagline">Full-Stack Developer & Tech Enthusiast</p>
            <div class="badge-container">
                <span class="badge">Node.js</span>
                <span class="badge">JavaScript</span>
                <span class="badge">GCP</span>
                <span class="badge">Java</span>
                <span class="badge">Photography</span>
            </div>
            <p>Building innovative solutions while framing the perfect shot</p>
        </div>
    </header>

    <div class="container">
        <section class="section">
            <h2>About Me</h2>
            <div class="about-grid">
                <div>
                    <p>I'm a <span class="highlight">BCA student</span> and passionate full-stack developer from India with expertise in building robust and scalable web applications.</p>
                    <p>Currently, I'm deepening my knowledge in <span class="highlight">cloud technologies (GCP)</span>, <span class="highlight">Node.js</span>, and modern frameworks while sharpening my skills in <span class="highlight">DSA</span> and <span class="highlight">Java</span>.</p>
                    <p>When I'm not coding, you'll find me behind a camera exploring my passion for photography — another form of creativity and problem-solving.</p>
                </div>
                <div>
                    <p>I believe in continuous learning and staying updated with the latest technologies and industry trends.</p>
                    <p>Currently preparing for <span class="highlight">CMAT</span> and <span class="highlight">IELTS</span> while working on personal projects that challenge my skills and expand my knowledge.</p>
                    <p>Open to <span class="highlight">freelance opportunities</span> and <span class="highlight">collaborations</span> on innovative projects that make a difference.</p>
                </div>
            </div>
        </section>

        <section class="section">
            <h2>Technical Skills</h2>
            <div class="tech-stack">
                <div class="tech-category">
                    <h3>Frontend Development</h3>
                    <div class="tech-items">
                        <span class="tech-item">HTML5</span>
                        <span class="tech-item">CSS3</span>
                        <span class="tech-item">JavaScript</span>
                        <span class="tech-item">Bootstrap</span>
                    </div>
                </div>
                
                <div class="tech-category">
                    <h3>Backend Development</h3>
                    <div class="tech-items">
                        <span class="tech-item">Node.js</span>
                        <span class="tech-item">Express.js</span>
                        <span class="tech-item">PHP</span>
                    </div>
                </div>
                
                <div class="tech-category">
                    <h3>Databases</h3>
                    <div class="tech-items">
                        <span class="tech-item">MySQL</span>
                        <span class="tech-item">PostgreSQL</span>
                        <span class="tech-item">Oracle</span>
                    </div>
                </div>
                
                <div class="tech-category">
                    <h3>Programming Languages</h3>
                    <div class="tech-items">
                        <span class="tech-item">C</span>
                        <span class="tech-item">C++</span>
                        <span class="tech-item">C#</span>
                        <span class="tech-item">Java</span>
                        <span class="tech-item">.NET</span>
                    </div>
                </div>
                
                <div class="tech-category">
                    <h3>Tools & Cloud</h3>
                    <div class="tech-items">
                        <span class="tech-item">Git</span>
                        <span class="tech-item">Docker</span>
                        <span class="tech-item">GCP</span>
                        <span class="tech-item">Postman</span>
                        <span class="tech-item">Linux</span>
                    </div>
                </div>
            </div>
        </section>

        <section class="section">
            <h2>GitHub Statistics</h2>
            <div class="stats-container">
                <div class="stat-card">
                    <div class="stat-value">50+</div>
                    <div class="stat-label">Projects Completed</div>
                </div>
                <div class="stat-card">
                    <div class="stat-value">25+</div>
                    <div class="stat-label">Repositories</div>
                </div>
                <div class="stat-card">
                    <div class="stat-value">15+</div>
                    <div class="stat-label">Technologies</div>
                </div>
                <div class="stat-card">
                    <div class="stat-value">1000+</div>
                    <div class="stat-label">Code Commits</div>
                </div>
            </div>
        </section>

        <section class="section">
            <h2>Current Focus</h2>
            <p>I'm currently working on <span class="highlight">AgriMotors</span>, a project aimed at revolutionizing the agricultural sector through technology.</p>
            <p>Deepening my expertise in:</p>
            <ul>
                <li>Google Cloud Platform (GCP) and cloud architecture</li>
                <li>Advanced Node.js and Express.js development</li>
                <li>Next.js and modern React patterns</li>
                <li>TypeScript for robust application development</li>
                <li>Tailwind CSS for efficient styling</li>
            </ul>
            <p>Additionally, strengthening my foundation in Data Structures and Algorithms while preparing for higher studies.</p>
        </section>

        <hr class="divider">

        <section class="section">
            <h2>Let's Connect</h2>
            <p>I'm always interested in connecting with fellow developers, potential collaborators, or those who share interests in technology and photography.</p>
            
            <div class="contact-links">
                <a href="https://www.linkedin.com/in/harshal-lathiya11/" class="contact-link">LinkedIn</a>
                <a href="mailto:Harshalplathiya@gmail.com" class="contact-link">Email</a>
                <a href="https://harshallathiya.github.io/Bootstrap/My_web_framework/my_website.html" class="contact-link">Photography Portfolio</a>
                <a href="https://github.com/HarshalLathiya" class="contact-link">GitHub</a>
            </div>
        </section>

        <p class="quote">"Code is like humor. When you have to explain it, it's bad." - Cory House</p>
    </div>
</body>
</html>
