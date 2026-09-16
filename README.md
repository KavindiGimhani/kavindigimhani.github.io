# kavindigimhani.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Kavindi Gimhani | Data Analyst</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #222;
            background: #ffffff;
        }

        nav {
            position: sticky;
            top: 0;
            z-index: 100;
            background: #ffffff;
            border-bottom: 1px solid #eaeaea;
            padding: 18px 8%;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 21px;
            font-weight: bold;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 28px;
        }

        nav a {
            text-decoration: none;
            color: #333;
            font-size: 15px;
        }

        nav a:hover {
            color: #555;
        }

        .hero {
            min-height: 85vh;
            display: flex;
            align-items: center;
            padding: 80px 8%;
            background: #f7f7f7;
        }

        .hero-content {
            max-width: 850px;
        }

        .hero h1 {
            font-size: 58px;
            line-height: 1.1;
            margin-bottom: 20px;
        }

        .hero h2 {
            font-size: 28px;
            font-weight: normal;
            margin-bottom: 25px;
        }

        .hero p {
            font-size: 18px;
            max-width: 700px;
            color: #555;
            margin-bottom: 35px;
        }

        .buttons {
            display: flex;
            gap: 15px;
            flex-wrap: wrap;
        }

        .button {
            display: inline-block;
            padding: 13px 22px;
            text-decoration: none;
            border: 1px solid #222;
            color: #222;
            border-radius: 5px;
            font-size: 15px;
        }

        .button:hover {
            background: #222;
            color: white;
        }

        section {
            padding: 90px 8%;
        }

        .section-title {
            font-size: 34px;
            margin-bottom: 20px;
        }

        .section-intro {
            max-width: 750px;
            color: #666;
            margin-bottom: 40px;
        }

        .about {
            max-width: 850px;
        }

        .about p {
            margin-bottom: 18px;
            color: #444;
        }

        .career-path {
            margin-top: 30px;
            padding: 25px;
            border-left: 4px solid #222;
            background: #f7f7f7;
            font-weight: bold;
        }

        .projects {
            background: #f7f7f7;
        }

        .project-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 25px;
        }

        .project-card {
            background: white;
            padding: 30px;
            border: 1px solid #e5e5e5;
            border-radius: 8px;
            transition: transform 0.2s ease;
        }

        .project-card:hover {
            transform: translateY(-4px);
        }

        .project-card h3 {
            margin-bottom: 12px;
            font-size: 21px;
        }

        .project-card p {
            color: #666;
            margin-bottom: 18px;
        }

        .project-tools {
            font-size: 14px;
            font-weight: bold;
            color: #444;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 25px;
            max-width: 900px;
        }

        .skill-box {
            padding: 25px;
            border: 1px solid #e5e5e5;
            border-radius: 8px;
        }

        .skill-box h3 {
            margin-bottom: 10px;
        }

        .skill-box p {
            color: #666;
        }

        .contact {
            background: #f7f7f7;
        }

        .contact p {
            margin-bottom: 12px;
            color: #555;
        }

        footer {
            padding: 25px 8%;
            text-align: center;
            color: #777;
            font-size: 14px;
        }

        @media (max-width: 700px) {

            .hero h1 {
                font-size: 42px;
            }

            .hero h2 {
                font-size: 23px;
            }

            nav {
                flex-direction: column;
                gap: 15px;
            }

            nav ul {
                gap: 15px;
                flex-wrap: wrap;
                justify-content: center;
            }

            .project-grid,
            .skills-grid {
                grid-template-columns: 1fr;
            }

            section {
                padding: 65px 7%;
            }
        }
    </style>
</head>

<body>

    <!-- Navigation -->
    <nav>
        <div class="logo">Kavindi Gimhani</div>

        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>


    <!-- Hero Section -->
    <section class="hero">

        <div class="hero-content">

            <h1>Hi, I'm Kavindi.</h1>

            <h2>Data Analyst | Sales & Business Analytics</h2>

            <p>
                I use data, statistics and business intelligence to turn
                complex information into clear, practical insights that
                support better business decisions.
            </p>

            <div class="buttons">
                <a class="button" href="#projects">View My Projects</a>

                <a class="button"
                   href="https://www.linkedin.com/"
                   target="_blank">
                    LinkedIn
                </a>
            </div>

        </div>

    </section>


    <!-- About Section -->
    <section id="about">

        <div class="about">

            <h2 class="section-title">About Me</h2>

            <p>
                I am a Data Analyst with an academic background in Statistics
                and hands-on experience across business analytics, sales,
                inventory, market research and reporting.
            </p>

            <p>
                My career has allowed me to understand both the business
                side and the analytical side of decision-making. I enjoy
                working with data to identify patterns, understand business
                performance and communicate insights clearly.
            </p>

            <p>
                I am particularly interested in commercial and revenue
                analytics, business intelligence and using automation to
                improve repetitive reporting processes.
            </p>

            <div class="career-path">
                Statistics → Business Experience → Data Analytics
                → Sales & Inventory Analytics → Revenue Analytics
            </div>

        </div>

    </section>


    <!-- Projects Section -->
    <section id="projects" class="projects">

        <h2 class="section-title">Featured Projects</h2>

        <p class="section-intro">
            A selection of analytics projects demonstrating my experience
            with business intelligence, sales analysis, inventory analysis
            and revenue analytics.
        </p>


        <div class="project-grid">

            <div class="project-card">

                <h3>Amazon Sales & Inventory Analytics</h3>

                <p>
                    Analysis of sales performance, inventory levels,
                    product performance and weeks of supply to identify
                    business and inventory opportunities.
                </p>

                <div class="project-tools">
                    Power BI · SQL · Excel
                </div>

            </div>


            <div class="project-card">

                <h3>FBA Inventory & WOS Dashboard</h3>

                <p>
                    Interactive dashboard focused on FBA inventory,
                    sales velocity and weeks of supply to support
                    inventory monitoring and replenishment decisions.
                </p>

                <div class="project-tools">
                    Power BI · DAX · Excel
                </div>

            </div>


            <div class="project-card">

                <h3>Apparel Sales Analysis</h3>

                <p>
                    Business analysis of apparel sales patterns,
                    product performance, colours, seasons and
                    category-level trends.
                </p>

                <div class="project-tools">
                    Power BI · Excel · Data Analysis
                </div>

            </div>


            <div class="project-card">

                <h3>Reporting Automation</h3>

                <p>
                    Exploring how repetitive weekly reporting processes
                    can be transformed through data preparation,
                    automation and business intelligence.
                </p>

                <div class="project-tools">
                    Power Query · Power BI · Automation
                </div>

            </div>


            <div class="project-card">

                <h3>Hospitality Revenue Analytics</h3>

                <p>
                    Hotel performance analysis covering occupancy,
                    ADR, RevPAR, booking channels, cancellations,
                    seasonality and revenue trends.
                </p>

                <div class="project-tools">
                    Power BI · Excel · Revenue Analytics
                </div>

            </div>


            <div class="project-card">

                <h3>Market Research Analysis</h3>

                <p>
                    Statistical and analytical exploration of market
                    research data to identify patterns, relationships
                    and meaningful business insights.
                </p>

                <div class="project-tools">
                    Statistics · R · Data Analysis
                </div>

            </div>

        </div>

    </section>


    <!-- Skills Section -->
    <section id="skills">

        <h2 class="section-title">Skills</h2>

        <p class="section-intro">
            Tools and analytical capabilities I use to solve practical
            business problems.
        </p>


        <div class="skills-grid">

            <div class="skill-box">
                <h3>Data Analytics</h3>
                <p>
                    Excel · SQL · Statistics · Data Cleaning
                </p>
            </div>


            <div class="skill-box">
                <h3>Business Intelligence</h3>
                <p>
                    Power BI · DAX · Power Query · Data Visualization
                </p>
            </div>


            <div class="skill-box">
                <h3>Business Analytics</h3>
                <p>
                    Sales Analytics · Inventory Analytics · KPI Reporting
                    · Business Insights
                </p>
            </div>


            <div class="skill-box">
                <h3>Automation</h3>
                <p>
                    Power Query · Power Automate · Reporting Automation
                </p>
            </div>

        </div>

    </section>


    <!-- Contact Section -->
    <section id="contact" class="contact">

        <h2 class="section-title">Let's Connect</h2>

        <p>
            I'm interested in opportunities related to Data Analytics,
            Business Intelligence, Commercial Analytics and Revenue Analytics.
        </p>

        <p>
            You can find me on LinkedIn and GitHub.
        </p>

        <div class="buttons">

            <a class="button"
               href="https://github.com/KavindiGimhani"
               target="_blank">
                GitHub
            </a>

            <a class="button"
               href="https://www.linkedin.com/"
               target="_blank">
                LinkedIn
            </a>

        </div>

    </section>


    <!-- Footer -->
    <footer>
        © 2026 Kavindi Gimhani · Data Analyst
    </footer>

</body>
</html>
