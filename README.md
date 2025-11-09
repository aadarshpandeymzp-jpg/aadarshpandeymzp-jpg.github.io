<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Adarsh Pandey - Digital Profile</title>
    <meta name="description" content="Adarsh Pandey - Operations Executive specializing in Supply Chain and Logistics Management">
    <meta name="keywords" content="Adarsh Pandey, Supply Chain, Logistics, Operations Executive, Om Logistics">
    <meta name="author" content="Adarsh Pandey">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background: #1a1a2e;
            color: #fff;
            overflow-x: hidden;
        }

        .container {
            max-width: 480px;
            margin: 0 auto;
            background: #0f0f1e;
        }

        .header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            padding: 40px 20px 30px;
            text-align: center;
            position: relative;
        }

        .profile-img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 5px solid white;
            background: #fff;
            margin: 0 auto 15px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 3em;
            color: #667eea;
            font-weight: bold;
            box-shadow: 0 5px 20px rgba(0,0,0,0.3);
        }

        .header h1 {
            font-size: 2em;
            margin-bottom: 5px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.2);
        }

        .header p {
            font-size: 1em;
            opacity: 0.95;
        }

        .card {
            margin: 15px;
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.3);
            transition: transform 0.3s ease;
            cursor: pointer;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .card-header {
            padding: 25px;
            font-size: 1.4em;
            font-weight: bold;
            text-align: center;
            color: white;
        }

        .card-content {
            padding: 25px;
            background: white;
            color: #333;
        }

        .bg-purple { background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); }
        .bg-orange { background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%); }
        .bg-blue { background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%); }
        .bg-green { background: linear-gradient(135deg, #43e97b 0%, #38f9d7 100%); }
        .bg-yellow { background: linear-gradient(135deg, #fa709a 0%, #fee140 100%); }
        .bg-pink { background: linear-gradient(135deg, #a8edea 0%, #fed6e3 100%); }
        .bg-teal { background: linear-gradient(135deg, #d299c2 0%, #fef9d7 100%); }

        .about-text {
            font-size: 1em;
            line-height: 1.8;
            color: #555;
        }

        .skill-tag {
            display: inline-block;
            background: #667eea;
            color: white;
            padding: 8px 15px;
            border-radius: 20px;
            margin: 5px;
            font-size: 0.9em;
        }

        .experience-item {
            margin-bottom: 20px;
            padding-bottom: 20px;
            border-bottom: 1px solid #eee;
        }

        .experience-item:last-child {
            border-bottom: none;
            padding-bottom: 0;
        }

        .experience-item h3 {
            color: #667eea;
            font-size: 1.2em;
            margin-bottom: 5px;
        }

        .experience-item .company {
            color: #764ba2;
            font-weight: 600;
            margin-bottom: 5px;
        }

        .experience-item .duration {
            color: #999;
            font-size: 0.9em;
            margin-bottom: 10px;
        }

        .experience-item ul {
            margin-left: 20px;
            color: #666;
        }

        .experience-item li {
            margin: 5px 0;
        }

        .education-item {
            margin-bottom: 20px;
        }

        .education-item h3 {
            color: #667eea;
            font-size: 1.1em;
            margin-bottom: 5px;
        }

        .education-item p {
            color: #666;
            margin: 3px 0;
        }

        .goal-item {
            background: #f8f9fa;
            padding: 15px;
            border-radius: 10px;
            margin: 10px 0;
            border-left: 4px solid #667eea;
        }

        .goal-item h4 {
            color: #667eea;
            margin-bottom: 8px;
            font-size: 1.1em;
        }

        .goal-item p {
            color: #666;
            line-height: 1.6;
            font-size: 0.95em;
        }

        .contact-section {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            padding: 40px 25px;
            text-align: center;
            color: white;
        }

        .contact-section h2 {
            font-size: 1.8em;
            margin-bottom: 20px;
        }

        .contact-btn {
            display: inline-block;
            background: white;
            color: #667eea;
            padding: 12px 30px;
            border-radius: 25px;
            text-decoration: none;
            margin: 10px;
            font-weight: 600;
            transition: transform 0.3s ease;
        }

        .contact-btn:hover {
            transform: scale(1.05);
        }

        .grid-2 {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 15px;
            margin-top: 15px;
        }

        .mini-card {
            background: linear-gradient(135deg, #667eea20 0%, #764ba220 100%);
            padding: 20px;
            border-radius: 15px;
            text-align: center;
        }

        .mini-card h4 {
            color: #667eea;
            margin-bottom: 10px;
            font-size: 1.1em;
        }

        .mini-card p {
            color: #666;
            font-size: 0.9em;
            line-height: 1.5;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .card {
            animation: fadeIn 0.6s ease-out backwards;
        }

        .card:nth-child(1) { animation-delay: 0.1s; }
        .card:nth-child(2) { animation-delay: 0.2s; }
        .card:nth-child(3) { animation-delay: 0.3s; }
        .card:nth-child(4) { animation-delay: 0.4s; }
        .card:nth-child(5) { animation-delay: 0.5s; }
        .card:nth-child(6) { animation-delay: 0.6s; }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <div class="profile-img">AP</div>
            <h1>ADARSH PANDEY</h1>
            <p>Operations Executive | Supply Chain Expert</p>
        </div>

        <div class="card">
            <div class="card-header bg-purple">About Me</div>
            <div class="card-content">
                <p class="about-text">
                    I am a dedicated Operations Executive specializing in Logistics and Supply Chain Management with expertise in first-mile operations (PAK India) and advanced Excel analytics. Currently driving operational excellence at Om Logistics Supply Chain Pvt. Ltd.
                </p>
                <p class="about-text" style="margin-top: 15px;">
                    My focus is on data-driven decision making, team leadership, and process optimization using Power BI and comprehensive operational reporting.
                </p>
            </div>
        </div>

        <div class="card">
            <div class="card-header bg-blue">Professional Experience</div>
            <div class="card-content">
                <div class="experience-item">
                    <h3>Operation Executive</h3>
                    <div class="company">Om Logistics Supply Chain Pvt. Ltd.</div>
                    <div class="duration">Jul 2024 - Present · 17 months</div>
                    <ul>
                        <li>First-mile operation specialist for PAK India</li>
                        <li>Advanced Excel expert in data analysis</li>
                        <li>Power BI for operational intelligence</li>
                        <li>Process improvement & efficiency optimization</li>
                    </ul>
                </div>

                <div class="experience-item">
                    <h3>Team Supervisor</h3>
                    <div class="company">Capital Cable India Pvt. Ltd.</div>
                    <div class="duration">Oct 2023 - Apr 2024 · 7 months</div>
                    <ul>
                        <li>Led team operations & coordination</li>
                        <li>Reports and inventory management</li>
                        <li>Quality assurance & efficiency</li>
                    </ul>
                </div>
            </div>
        </div>

        <div class="card">
            <div class="card-header bg-green">Core Expertise</div>
            <div class="card-content" style="text-align: center;">
                <div class="skill-tag">Advanced Excel</div>
                <div class="skill-tag">Power BI</div>
                <div class="skill-tag">Data Analysis</div>
                <div class="skill-tag">Team Leadership</div>
                <div class="skill-tag">Supply Chain</div>
                <div class="skill-tag">Operations Management</div>
                <div class="skill-tag">Team Building</div>
                <div class="skill-tag">Strategy</div>
                <div class="skill-tag">Training</div>
                <div class="skill-tag">Logistics</div>
                <div class="skill-tag">Management</div>
            </div>
        </div>

        <div class="card">
            <div class="card-header bg-orange">Education</div>
            <div class="card-content">
                <div class="education-item">
                    <h3>🎓 Manipal University Jaipur</h3>
                    <p><strong>Master of Business Administration (MBA)</strong></p>
                    <p>Supply Chain & Logistics</p>
                    <p style="color: #999;">Sep 2022 - Jul 2024</p>
                </div>

                <div class="education-item" style="margin-top: 25px;">
                    <h3>🎓 Prof. Rajendra Singh University</h3>
                    <p><strong>Bachelor of Science</strong></p>
                    <p>BSc Mathematics and Physics</p>
                    <p style="color: #999;">Activities: Cricket and Chess</p>
                </div>
            </div>
        </div>

        <div class="card">
            <div class="card-header bg-yellow">Career Strengths</div>
            <div class="card-content">
                <div class="grid-2">
                    <div class="mini-card">
                        <h4>📊 Analytics</h4>
                        <p>Expert in data analysis & visualization with Excel & Power BI</p>
                    </div>
                    <div class="mini-card">
                        <h4>👥 Leadership</h4>
                        <p>Proven track record in team management & development</p>
                    </div>
                    <div class="mini-card">
                        <h4>🚚 Operations</h4>
                        <p>Specialized in supply chain & logistics optimization</p>
                    </div>
                    <div class="mini-card">
                        <h4>⚡ Efficiency</h4>
                        <p>Process improvement & performance enhancement</p>
                    </div>
                </div>
            </div>
        </div>

        <div class="card">
            <div class="card-header bg-teal">Future Goals</div>
            <div class="card-content">
                <div class="goal-item">
                    <h4>🎯 Short-term (6-12 months)</h4>
                    <p>Enhance technical expertise in supply chain analytics and automation. Obtain advanced certifications and lead larger operational projects.</p>
                </div>

                <div class="goal-item">
                    <h4>🚀 Mid-term (1-3 years)</h4>
                    <p>Transition into senior operations management role. Build expertise in AI and IoT in logistics. Mentor junior team members.</p>
                </div>

                <div class="goal-item">
                    <h4>🌟 Long-term (3-5 years)</h4>
                    <p>Establish myself as a thought leader in supply chain management. Move into C-suite operations role or launch consulting practice focused on supply chain optimization.</p>
                </div>

                <div class="goal-item">
                    <h4>📚 Continuous Growth</h4>
                    <p>Stay ahead of industry trends through continuous learning. Expand professional network and maintain work-life balance.</p>
                </div>
            </div>
        </div>

        <div class="contact-section">
            <h2>Let's Connect</h2>
            <p style="margin-bottom: 20px; opacity: 0.95;">Interested in collaboration or opportunities?</p>
            <a href="https://www.linkedin.com/in/adarsh-pandey-228a762a4" class="contact-btn" target="_blank">LinkedIn Profile</a>
            <a href="mailto:aadarshpandeymzp@gmail.com" class="contact-btn">Email Me</a>
        </div>
    </div>

    <script>
        document.querySelectorAll('.card').forEach(card => {
            card.addEventListener('click', function(e) {
                if (!e.target.matches('a')) {
                    this.style.transform = 'scale(0.98)';
                    setTimeout(() => {
                        this.style.transform = '';
                    }, 200);
                }
            });
        });
    </script>
</body>
</html>
