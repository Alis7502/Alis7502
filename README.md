<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ali Sadeghi - GitHub Profile</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #0d1117 0%, #161b22 100%);
            color: #c9d1d9;
            line-height: 1.6;
            padding: 2rem;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
        }
        
        header {
            text-align: center;
            padding: 2rem 0;
            margin-bottom: 2rem;
            position: relative;
        }
        
        .profile-header {
            background: linear-gradient(135deg, #238636 0%, #2ea043 100%);
            border-radius: 15px;
            padding: 2rem;
            margin-bottom: 2rem;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
        }
        
        h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
            color: #fff;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }
        
        h2 {
            font-size: 2rem;
            margin-bottom: 1.5rem;
            color: #58a6ff;
            border-bottom: 2px solid #30363d;
            padding-bottom: 0.5rem;
        }
        
        h3 {
            font-size: 1.5rem;
            margin: 1.5rem 0 1rem;
            color: #f0f6fc;
        }
        
        .tagline {
            font-size: 1.3rem;
            color: #8b949e;
            margin-bottom: 1.5rem;
        }
        
        .badges {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 10px;
            margin: 1.5rem 0;
        }
        
        .badge {
            background: #21262d;
            padding: 8px 16px;
            border-radius: 20px;
            font-size: 0.9rem;
            display: flex;
            align-items: center;
            border: 1px solid #30363d;
            transition: transform 0.3s ease;
        }
        
        .badge:hover {
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }
        
        .badge i {
            margin-right: 5px;
            color: #58a6ff;
        }
        
        .content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 2rem;
        }
        
        @media (max-width: 900px) {
            .content {
                grid-template-columns: 1fr;
            }
        }
        
        .card {
            background: #161b22;
            border-radius: 10px;
            padding: 1.5rem;
            margin-bottom: 2rem;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
            border: 1px solid #30363d;
        }
        
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 1rem;
        }
        
        .skill-category {
            margin-bottom: 1.5rem;
        }
        
        .skill-items {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        
        .skill-item {
            background: #238636;
            padding: 5px 12px;
            border-radius: 15px;
            font-size: 0.9rem;
        }
        
        .project {
            margin-bottom: 1.5rem;
            padding-bottom: 1.5rem;
            border-bottom: 1px solid #30363d;
        }
        
        .project:last-child {
            border-bottom: none;
            margin-bottom: 0;
            padding-bottom: 0;
        }
        
        .project-title {
            display: flex;
            align-items: center;
            color: #58a6ff;
            margin-bottom: 0.5rem;
        }
        
        .project-title i {
            margin-right: 10px;
        }
        
        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 2rem;
        }
        
        .social-link {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            width: 50px;
            height: 50px;
            background: #21262d;
            border-radius: 50%;
            color: #c9d1d9;
            font-size: 1.5rem;
            transition: all 0.3s ease;
            border: 1px solid #30363d;
            text-decoration: none;
        }
        
        .social-link:hover {
            background: #58a6ff;
            color: #fff;
            transform: translateY(-5px);
        }
        
        .interests {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
        }
        
        .interest {
            display: flex;
            align-items: center;
            background: #21262d;
            padding: 8px 15px;
            border-radius: 20px;
            border: 1px solid #30363d;
        }
        
        .interest i {
            margin-right: 8px;
            color: #db61a2;
        }
        
        .quote {
            text-align: center;
            font-style: italic;
            margin: 2rem 0;
            padding: 1.5rem;
            background: linear-gradient(135deg, #1f6feb 0%, #58a6ff 100%);
            border-radius: 10px;
            color: #f0f6fc;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }
        
        .stats {
            display: flex;
            justify-content: space-around;
            text-align: center;
            margin: 2rem 0;
        }
        
        .stat {
            padding: 1rem;
        }
        
        .stat-number {
            font-size: 2.5rem;
            font-weight: bold;
            color: #58a6ff;
        }
        
        .stat-label {
            color: #8b949e;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="profile-header">
            <h1>Ali Sadeghi</h1>
            <p class="tagline">Control Engineering Student & AI Developer</p>
            
            <div class="badges">
                <div class="badge"><i class="fas fa-graduation-cap"></i> Control Engineering</div>
                <div class="badge"><i class="fab fa-python"></i> Python Developer</div>
                <div class="badge"><i class="fas fa-brain"></i> Deep Learning</div>
                <div class="badge"><i class="fas fa-robot"></i> Machine Learning</div>
                <div class="badge"><i class="fas fa-chart-line"></i> Data Analysis</div>
            </div>
        </div>
        
        <div class="stats">
            <div class="stat">
                <div class="stat-number">15+</div>
                <div class="stat-label">Projects</div>
            </div>
            <div class="stat">
                <div class="stat-number">5+</div>
                <div class="stat-label">Technologies</div>
            </div>
            <div class="stat">
                <div class="stat-number">2+</div>
                <div class="stat-label">Years Experience</div>
            </div>
        </div>
        
        <div class="content">
            <div class="left-column">
                <div class="card">
                    <h2><i class="fas fa-user"></i> About Me</h2>
                    <p>I am a dedicated <strong>Control Engineering student</strong> with a strong foundation in <strong>Machine Learning</strong> and <strong>Deep Learning</strong>, dedicated to developing innovative solutions for <strong>Fault Detection and Diagnosis</strong>.</p>
                    <p>My academic projects focus on integrating control systems with AI to enhance system reliability and performance. I am passionate about transitioning into the professional world and contributing to cutting-edge advancements in automation and intelligent systems.</p>
                </div>
                
                <div class="card">
                    <h2><i class="fas fa-code"></i> Skills</h2>
                    <div class="skills-grid">
                        <div class="skill-category">
                            <h3>Programming</h3>
                            <div class="skill-items">
                                <div class="skill-item">Python</div>
                                <div class="skill-item">MATLAB</div>
                            </div>
                        </div>
                        
                        <div class="skill-category">
                            <h3>ML/DL Frameworks</h3>
                            <div class="skill-items">
                                <div class="skill-item">TensorFlow</div>
                                <div class="skill-item">PyTorch</div>
                                <div class="skill-item">Scikit-learn</div>
                                <div class="skill-item">Keras</div>
                            </div>
                        </div>
                        
                        <div class="skill-category">
                            <h3>Data Science</h3>
                            <div class="skill-items">
                                <div class="skill-item">Pandas</div>
                                <div class="skill-item">NumPy</div>
                                <div class="skill-item">Matplotlib</div>
                            </div>
                        </div>
                        
                        <div class="skill-category">
                            <h3>Domains</h3>
                            <div class="skill-items">
                                <div class="skill-item">Machine Learning</div>
                                <div class="skill-item">Deep Learning</div>
                                <div class="skill-item">Fault Detection</div>
                                <div class="skill-item">Data Visualization</div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="right-column">
                <div class="card">
                    <h2><i class="fas fa-rocket"></i> Projects</h2>
                    
                    <div class="project">
                        <h3 class="project-title"><i class="fas fa-project-diagram"></i> Fault Detection System</h3>
                        <p>Developed machine learning and deep learning models to detect anomalies in industrial systems, improving diagnostic accuracy by 25% compared to traditional methods.</p>
                    </div>
                    
                    <div class="project">
                        <h3 class="project-title"><i class="fas fa-chart-bar"></i> Data Visualization Dashboard</h3>
                        <p>Built interactive visualizations with Pandas and Matplotlib to analyze system performance metrics, enabling faster decision-making for engineering teams.</p>
                    </div>
                </div>
                
                <div class="card">
                    <h2><i class="fas fa-heart"></i> Interests</h2>
                    <div class="interests">
                        <div class="interest"><i class="fas fa-film"></i> Films</div>
                        <div class="interest"><i class="fas fa-gamepad"></i> Computer Games</div>
                        <div class="interest"><i class="fas fa-book"></i> Reading</div>
                        <div class="interest"><i class="fas fa-code"></i> AI Research</div>
                    </div>
                    
                    <p class="quote">"Beyond coding, I find inspiration in the narrative depth of films and the strategic complexity of computer games, which fuel my creative approach to solving technical challenges."</p>
                </div>
            </div>
        </div>
        
        <div class="card">
            <h2><i class="fas fa-envelope"></i> Contact</h2>
            <div class="social-links">
                <a href="https://www.linkedin.com/in/alisadeghi7502/" class="social-link">
                    <i class="fab fa-linkedin-in"></i>
                </a>
                <a href="mailto:alisadeghi7502@gmail.com" class="social-link">
                    <i class="fas fa-envelope"></i>
                </a>
                <a href="https://github.com/yourusername" class="social-link">
                    <i class="fab fa-github"></i>
                </a>
            </div>
        </div>
    </div>
</body>
</html>
