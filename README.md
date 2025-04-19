<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yashwardhan Singh Thakur | Professional Resume</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&family=Playfair+Display:wght@400;700&family=Montserrat:wght@500;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary-color: #2962ff;
            --secondary-color: #0d47a1;
            --accent-color: #ff6d00;
            --text-color: #263238;
            --light-bg: #f5f7fa;
            --white: #ffffff;
            --gray-light: #eceff1;
            --gray-medium: #b0bec5;
            --shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
            --transition: all 0.4s cubic-bezier(0.25, 0.8, 0.25, 1);
            --border-radius: 12px;
        }
        
        body {
            font-family: 'Poppins', sans-serif;
            line-height: 1.7;
            margin: 0;
            padding: 0;
            color: var(--text-color);
            background: linear-gradient(135deg, #f5f7fa 0%, #e4e8eb 100%);
            min-height: 100vh;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        header {
            text-align: center;
            padding: 50px 0;
            margin-bottom: 40px;
            background: var(--white);
            box-shadow: var(--shadow);
            border-radius: var(--border-radius);
            position: relative;
            overflow: hidden;
            transition: var(--transition);
            border-left: 5px solid var(--primary-color);
        }
        
        header::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 5px;
            background: linear-gradient(90deg, var(--primary-color), var(--accent-color));
        }
        
        header:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.15);
        }
        
        h1 {
            color: var(--secondary-color);
            margin-bottom: 15px;
            font-size: 2.8em;
            font-family: 'Montserrat', sans-serif;
            font-weight: 700;
            letter-spacing: 1px;
            text-transform: uppercase;
            background: linear-gradient(90deg, var(--primary-color), var(--accent-color));
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }
        
        .contact-info {
            margin-bottom: 15px;
            font-size: 1.1em;
            color: var(--secondary-color);
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
        }
        
        .contact-info a {
            color: var(--primary-color);
            text-decoration: none;
            transition: var(--transition);
            display: inline-flex;
            align-items: center;
            gap: 5px;
        }
        
        .contact-info a:hover {
            color: var(--accent-color);
            transform: translateY(-2px);
        }
        
        h2 {
            color: var(--secondary-color);
            padding-bottom: 8px;
            margin-top: 40px;
            font-family: 'Montserrat', sans-serif;
            font-size: 2em;
            letter-spacing: 0.5px;
            position: relative;
            display: inline-block;
        }
        
        h2::after {
            content: "";
            position: absolute;
            bottom: 0;
            left: 0;
            width: 60px;
            height: 4px;
            background: linear-gradient(90deg, var(--primary-color), var(--accent-color));
            border-radius: 2px;
        }
        
        section {
            margin-bottom: 40px;
            background: var(--white);
            padding: 40px;
            border-radius: var(--border-radius);
            box-shadow: var(--shadow);
            transition: var(--transition);
            position: relative;
            overflow: hidden;
        }
        
        section::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 4px;
            height: 100%;
            background: linear-gradient(to bottom, var(--primary-color), var(--accent-color));
        }
        
        section:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.15);
        }
        
        .job, .education, .project {
            margin-bottom: 35px;
            padding-bottom: 25px;
            border-bottom: 1px dashed var(--gray-medium);
            position: relative;
        }
        
        .job:last-child, .education:last-child, .project:last-child {
            border-bottom: none;
            margin-bottom: 0;
            padding-bottom: 0;
        }
        
        .job-title, .degree, .project-title {
            font-weight: 700;
            font-size: 1.3em;
            color: var(--secondary-color);
            margin-bottom: 8px;
            font-family: 'Montserrat', sans-serif;
        }
        
        .company, .school {
            font-style: italic;
            color: var(--secondary-color);
            opacity: 0.9;
            margin-bottom: 10px;
            display: block;
        }
        
        .date {
            color: var(--white);
            font-size: 0.9em;
            font-weight: 600;
            margin-bottom: 15px;
            display: inline-block;
            background: linear-gradient(90deg, var(--primary-color), var(--accent-color));
            padding: 5px 15px;
            border-radius: 20px;
            box-shadow: 0 3px 10px rgba(41, 98, 255, 0.3);
        }
        
        ul {
            padding-left: 25px;
            margin-top: 20px;
        }
        
        li {
            margin-bottom: 12px;
            position: relative;
            padding-left: 25px;
        }
        
        li::before {
            content: "";
            position: absolute;
            left: 0;
            top: 10px;
            width: 12px;
            height: 12px;
            background: var(--primary-color);
            border-radius: 50%;
            transform: scale(0);
            transition: var(--transition);
        }
        
        li:hover::before {
            transform: scale(1);
            background: var(--accent-color);
        }
        
        .skills {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .skill-category {
            background: linear-gradient(135deg, var(--white) 0%, var(--gray-light) 100%);
            padding: 25px;
            border-radius: var(--border-radius);
            transition: var(--transition);
            border: 1px solid rgba(0, 0, 0, 0.05);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.03);
        }
        
        .skill-category:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1);
            border-color: rgba(41, 98, 255, 0.2);
        }
        
        .skill-category h3 {
            color: var(--secondary-color);
            margin-bottom: 20px;
            font-size: 1.4em;
            position: relative;
            display: inline-block;
        }
        
        .skill-category h3::after {
            content: "";
            position: absolute;
            bottom: -8px;
            left: 0;
            width: 40px;
            height: 3px;
            background: var(--primary-color);
            border-radius: 3px;
        }
        
        #summary p {
            font-size: 1.15em;
            line-height: 1.9;
            text-align: justify;
            padding-right: 20px;
        }
        
        /* Navigation */
        .nav-container {
            background: linear-gradient(90deg, var(--secondary-color) 0%, var(--primary-color) 100%);
            border-radius: var(--border-radius);
            margin-bottom: 40px;
            box-shadow: var(--shadow);
            position: sticky;
            top: 20px;
            z-index: 100;
        }
        
        nav {
            display: flex;
            justify-content: center;
            padding: 0;
        }
        
        nav a {
            color: var(--white);
            text-decoration: none;
            padding: 15px 25px;
            margin: 0 5px;
            border-radius: 5px;
            transition: var(--transition);
            font-weight: 600;
            position: relative;
            overflow: hidden;
        }
        
        nav a::before {
            content: "";
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: rgba(255, 255, 255, 0.1);
            transition: var(--transition);
        }
        
        nav a:hover::before {
            left: 0;
        }
        
        nav a:hover {
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }
        
        nav a i {
            margin-right: 8px;
        }
        
        /* Progress bars for skills */
        .skill-meter {
            margin-top: 15px;
        }
        
        .skill-name {
            display: flex;
            justify-content: space-between;
            margin-bottom: 5px;
            font-weight: 600;
        }
        
        .meter {
            height: 10px;
            background: var(--gray-light);
            border-radius: 5px;
            overflow: hidden;
        }
        
        .progress {
            height: 100%;
            background: linear-gradient(90deg, var(--primary-color), var(--accent-color));
            border-radius: 5px;
            transition: width 1.5s ease-out;
        }
        
        /* Floating action button */
        .fab {
            position: fixed;
            bottom: 30px;
            right: 30px;
            width: 60px;
            height: 60px;
            background: linear-gradient(135deg, var(--primary-color), var(--accent-color));
            color: white;
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 24px;
            box-shadow: 0 5px 20px rgba(41, 98, 255, 0.4);
            cursor: pointer;
            transition: var(--transition);
            z-index: 50;
            text-decoration: none;
        }
        
        .fab:hover {
            transform: scale(1.1) translateY(-5px);
            box-shadow: 0 10px 25px rgba(41, 98, 255, 0.5);
        }
        
        /* Responsive Design */
        @media (max-width: 992px) {
            .skills {
                grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            }
        }
        
        @media (max-width: 768px) {
            body {
                padding: 10px;
            }
            
            h1 {
                font-size: 2.2em;
            }
            
            .contact-info {
                flex-direction: column;
                gap: 10px;
            }
            
            section {
                padding: 30px 20px;
            }
            
            nav {
                flex-wrap: wrap;
            }
            
            nav a {
                padding: 12px 15px;
                margin: 3px;
                font-size: 0.9em;
            }
        }
        
        /* Animation */
        @keyframes fadeInUp {
            from { 
                opacity: 0; 
                transform: translateY(30px); 
            }
            to { 
                opacity: 1; 
                transform: translateY(0); 
            }
        }
        
        section {
            animation: fadeInUp 0.8s ease-out forwards;
            opacity: 0;
        }
        
        section:nth-child(1) { animation-delay: 0.1s; }
        section:nth-child(2) { animation-delay: 0.2s; }
        section:nth-child(3) { animation-delay: 0.3s; }
        section:nth-child(4) { animation-delay: 0.4s; }
        section:nth-child(5) { animation-delay: 0.5s; }
        
        /* Gradient text animation */
        .gradient-text {
            background: linear-gradient(90deg, var(--primary-color), var(--accent-color), var(--primary-color));
            background-size: 200% auto;
            color: transparent;
            -webkit-background-clip: text;
            background-clip: text;
            animation: gradientText 3s linear infinite;
        }
        
        @keyframes gradientText {
            0% { background-position: 0% center; }
            100% { background-position: 200% center; }
        }
        
        /* Card hover effect */
        .card-hover {
            transition: var(--transition);
        }
        
        .card-hover:hover {
            transform: perspective(1000px) rotateX(5deg) rotateY(5deg) scale(1.02);
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.15);
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>YASHWARDHAN SINGH THAKUR</h1>
            <div class="contact-info">
                <span><i class="fas fa-map-marker-alt"></i> 16B Ankur Aangan colony, Nipania road, Indore</span>
                <span><i class="fas fa-phone"></i> 8889308246</span>
                <a href="mailto:yashvardhansinghthakur2007@gmail.com"><i class="fas fa-envelope"></i> Email Me</a>
                <a href="https://www.linkedin.com/in/yashvardhan-thakur-534696269" target="_blank"><i class="fab fa-linkedin"></i> LinkedIn</a>
            </div>
        </header>

        <div class="nav-container">
            <nav>
                <a href="#summary"><i class="fas fa-user"></i> Summary</a>
                <a href="#experience"><i class="fas fa-briefcase"></i> Experience</a>
                <a href="#education"><i class="fas fa-graduation-cap"></i> Education</a>
                <a href="#skills"><i class="fas fa-code"></i> Skills</a>
                <a href="#projects"><i class="fas fa-project-diagram"></i> Projects</a>
            </nav>
        </div>

        <section id="summary" class="card-hover">
            <h2><span class="gradient-text">PROFESSIONAL SUMMARY</span></h2>
            <p>Motivated and enthusiastic individual seeking to leverage strong interpersonal skills and a willingness to learn in an entry-level position. Adept at collaborating in team environments and demonstrating a positive attitude in fast-paced settings. Eager to apply academic knowledge and personal skills to contribute to organizational goals while gaining valuable experience and professional growth. Committed to continuous learning and development, with a strong desire to excel in accounting and banking.</p>
        </section>

        <section id="experience" class="card-hover">
            <h2>PROFESSIONAL EXPERIENCE</h2>
            <div class="job">
                <div class="job-title">Seeking Opportunities</div>
                <div class="date">2025</div>
                <p>No work experience currently. Seeking opportunities to gain professional experience and develop skills in accounting and banking.</p>
                <ul>
                    <li>Actively pursuing internships and entry-level positions</li>
                    <li>Engaging in self-study and online courses to enhance skills</li>
                    <li>Participating in relevant student organizations and activities</li>
                    <li>Building professional network through LinkedIn and events</li>
                </ul>
            </div>
        </section>

        <section id="education" class="card-hover">
            <h2>EDUCATION</h2>
            <div class="education">
                <div class="degree">IIMB DBE Program</div>
                <div class="school">Indian Institute of Management, Bangalore</div>
                <div class="date">2024 - 2027 (Expected)</div>
                <ul>
                    <li>Specializing in Digital Business and Entrepreneurship</li>
                    <li>Coursework in financial management and business analytics</li>
                </ul>
            </div>
            <div class="education">
                <div class="degree">IIPS College DAVV</div>
                <div class="school">International Institute of Professional Studies, Indore</div>
                <div class="date">2024 - 2027 (Expected)</div>
                <ul>
                    <li>Bachelor's degree program in Business Administration</li>
                    <li>Focus on accounting and financial management</li>
                </ul>
            </div>
        </section>

        <section id="skills" class="card-hover">
            <h2>SKILLS</h2>
            <div class="skills">
                <div class="skill-category">
                    <h3>Technical Skills</h3>
                    <div class="skill-meter">
                        <div class="skill-name">Cost Accounting <span>85%</span></div>
                        <div class="meter"><div class="progress" style="width: 85%"></div></div>
                    </div>
                    <div class="skill-meter">
                        <div class="skill-name">Business Analytics <span>80%</span></div>
                        <div class="meter"><div class="progress" style="width: 80%"></div></div>
                    </div>
                    <div class="skill-meter">
                        <div class="skill-name">Stock Monitoring <span>75%</span></div>
                        <div class="meter"><div class="progress" style="width: 75%"></div></div>
                    </div>
                    <div class="skill-meter">
                        <div class="skill-name">Financial Reporting <span>80%</span></div>
                        <div class="meter"><div class="progress" style="width: 80%"></div></div>
                    </div>
                </div>
                <div class="skill-category">
                    <h3>Professional Skills</h3>
                    <div class="skill-meter">
                        <div class="skill-name">Leadership <span>90%</span></div>
                        <div class="meter"><div class="progress" style="width: 90%"></div></div>
                    </div>
                    <div class="skill-meter">
                        <div class="skill-name">Team Collaboration <span>85%</span></div>
                        <div class="meter"><div class="progress" style="width: 85%"></div></div>
                    </div>
                    <div class="skill-meter">
                        <div class="skill-name">Problem Solving <span>88%</span></div>
                        <div class="meter"><div class="progress" style="width: 88%"></div></div>
                    </div>
                    <div class="skill-meter">
                        <div class="skill-name">Communication <span>82%</span></div>
                        <div class="meter"><div class="progress" style="width: 82%"></div></div>
                    </div>
                </div>
                <div class="skill-category">
                    <h3>Software Skills</h3>
                    <div class="skill-meter">
                        <div class="skill-name">Microsoft Office <span>90%</span></div>
                        <div class="meter"><div class="progress" style="width: 90%"></div></div>
                    </div>
                    <div class="skill-meter">
                        <div class="skill-name">Tally <span>75%</span></div>
                        <div class="meter"><div class="progress" style="width: 75%"></div></div>
                    </div>
                    <div class="skill-meter">
                        <div class="skill-name">Tableau <span>70%</span></div>
                        <div class="meter"><div class="progress" style="width: 70%"></div></div>
                    </div>
                </div>
            </div>
        </section>

        <section id="projects" class="card-hover">
            <h2>ACADEMIC PROJECTS</h2>
            <div class="project">
                <div class="project-title">Financial Analysis Project</div>
                <div class="date">2025</div>
                <ul>
                    <li>Analyzed company financial statements and prepared reports for 5 major corporations</li>
                    <li>Calculated key financial ratios and interpreted results to assess company health</li>
                    <li>Presented findings to faculty panel with recommendations for financial improvement</li>
                </ul>
            </div>
            <div class="project">
                <div class="project-title">Stock Market Simulation</div>
                <div class="date">2025</div>
                <ul>
                    <li>Participated in 3-month virtual stock trading competition</li>
                    <li>Researched and analyzed stock performance using fundamental and technical analysis</li>
                    <li>Developed investment strategy based on market trends and economic indicators</li>
                </ul>
            </div>
        </section>

        <a href="#" class="fab" title="Back to Top">
            <i class="fas fa-arrow-up"></i>
        </a>
    </div>

    <script>
        // Animate progress bars when they come into view
        document.addEventListener('DOMContentLoaded', function() {
            const progressBars = document.querySelectorAll('.progress');
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        const width = entry.target.style.width;
                        entry.target.style.width = '0';
                        setTimeout(() => {
                            entry.target.style.width = width;
                        }, 100);
                    }
                });
            }, { threshold: 0.5 });
            
            progressBars.forEach(bar => {
                observer.observe(bar);
            });
        });
    </script>
</body>
</html>
