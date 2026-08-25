<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Ibrahim Doni Samaila | ICT Professional Portfolio</title>

    <style>
        :root {
            --primary: #123b5d;
            --secondary: #0f766e;
            --light: #f4f7f9;
            --dark: #1f2937;
            --muted: #64748b;
            --white: #ffffff;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, Helvetica, sans-serif;
            line-height: 1.7;
            color: var(--dark);
            background: #e9eef2;
        }

        .container {
            max-width: 1100px;
            margin: 30px auto;
            background: var(--white);
            box-shadow: 0 10px 35px rgba(0, 0, 0, 0.10);
        }

        /* HERO */
        header {
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            color: white;
            padding: 70px 55px;
        }

        header h1 {
            font-size: 44px;
            margin-bottom: 10px;
            letter-spacing: 1px;
        }

        header h2 {
            font-size: 19px;
            font-weight: normal;
            margin-bottom: 25px;
            opacity: 0.95;
        }

        .tagline {
            max-width: 800px;
            font-size: 18px;
            border-left: 4px solid rgba(255,255,255,.8);
            padding-left: 18px;
        }

        .btn {
            display: inline-block;
            margin-top: 25px;
            padding: 12px 22px;
            background: white;
            color: var(--primary);
            text-decoration: none;
            border-radius: 6px;
            font-weight: bold;
        }

        .btn:hover {
            transform: translateY(-2px);
        }

        /* NAVIGATION */
        nav {
            position: sticky;
            top: 0;
            z-index: 100;
            background: #0b2d45;
            padding: 13px 20px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 9px;
            font-size: 13px;
        }

        nav a:hover {
            color: #7dd3fc;
        }

        /* MAIN */
        main {
            padding: 50px 55px;
        }

        section {
            margin-bottom: 55px;
            scroll-margin-top: 70px;
        }

        h3 {
            color: var(--primary);
            font-size: 27px;
            margin-bottom: 20px;
            padding-bottom: 9px;
            border-bottom: 2px solid #dce5eb;
        }

        h4 {
            color: var(--secondary);
            font-size: 19px;
            margin: 18px 0 8px;
        }

        p {
            margin-bottom: 14px;
        }

        ul {
            margin: 10px 0 15px 25px;
        }

        li {
            margin-bottom: 6px;
        }

        /* CARDS */
        .grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 20px;
        }

        .card {
            background: var(--light);
            border-left: 4px solid var(--secondary);
            padding: 22px;
            border-radius: 6px;
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-4px);
            box-shadow: 0 8px 20px rgba(0,0,0,.08);
        }

        .card h4 {
            margin-top: 0;
        }

        /* SKILLS */
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }

        .skill {
            background: #e7f1f1;
            color: #155e59;
            padding: 8px 14px;
            border-radius: 20px;
            font-size: 14px;
            font-weight: bold;
        }

        /* TIMELINE */
        .timeline {
            border-left: 3px solid var(--secondary);
            padding-left: 27px;
        }

        .timeline-item {
            position: relative;
            margin-bottom: 30px;
        }

        .timeline-item::before {
            content: "";
            position: absolute;
            width: 13px;
            height: 13px;
            background: var(--secondary);
            border-radius: 50%;
            left: -35px;
            top: 8px;
        }

        .year {
            color: var(--muted);
            font-size: 14px;
            font-weight: bold;
        }

        /* QUOTE */
        .quote {
            background: var(--light);
            border-left: 5px solid var(--secondary);
            padding: 27px;
            font-size: 20px;
            font-style: italic;
        }

        /* CONTACT */
        .contact {
            background: #f1f6f8;
            padding: 28px;
            border-radius: 8px;
        }

        .contact strong {
            font-size: 20px;
        }

        /* FOOTER */
        footer {
            background: #0b2d45;
            color: white;
            text-align: center;
            padding: 28px;
            font-size: 14px;
        }

        /* MOBILE */
        @media (max-width: 760px) {

            .container {
                margin: 0;
            }

            header {
                padding: 45px 25px;
            }

            header h1 {
                font-size: 32px;
            }

            header h2 {
                font-size: 16px;
            }

            main {
                padding: 35px 25px;
            }

            .grid {
                grid-template-columns: 1fr;
            }

            nav {
                display: none;
            }
        }

        /* PRINT */
        @media print {

            body {
                background: white;
            }

            .container {
                margin: 0;
                box-shadow: none;
            }

            nav,
            .btn {
                display: none;
            }

            section {
                break-inside: avoid;
            }
        }
    </style>
</head>

<body>

<div class="container">

    <!-- HERO SECTION -->
    <header>

        <h1>IBRAHIM DONI SAMAILA</h1>

        <h2>
            ICT Manager |
            Network &amp; Systems Technician |
            CBT Centre Manager |
            ICT Trainer
        </h2>

        <p class="tagline">
            Using technology to solve real-life problems,
            improve productivity, create opportunities and
            empower individuals and communities.
        </p>

        <a href="#contact" class="btn">
            Contact Me
        </a>

    </header>


    <!-- NAVIGATION -->
    <nav>

        <a href="#about">About</a>
        <a href="#experience">Experience</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#achievements">Achievements</a>
        <a href="#training">Training</a>
        <a href="#contact">Contact</a>

    </nav>


    <main>

        <!-- PROFILE -->
        <section id="profile">

            <h3>Professional Profile</h3>

            <p>
                I am an ICT professional with over
                <strong>12 years of practical experience</strong>
                in information and communication technology,
                ICT infrastructure management, computer-based
                testing, networking, technical support, digital
                skills training and technology-driven community
                development.
            </p>

            <p>
                My experience covers the design, installation and
                maintenance of computer networks, management of
                ICT infrastructure, operation of Computer-Based
                Testing (CBT) centres, server and systems support,
                troubleshooting, digital literacy training and
                technical support for organisations and communities.
            </p>

            <p>
                I strongly believe that technology is most valuable
                when it is used to solve real-life problems, improve
                productivity, create opportunities and empower people.
            </p>

        </section>


        <!-- ABOUT -->
        <section id="about">

            <h3>About Me</h3>

            <p>
                My professional journey has been driven by a passion
                for technology and its ability to create positive
                social and economic impact.
            </p>

            <p>
                I have developed practical experience managing ICT
                environments, supporting users, setting up computer
                laboratories and CBT centres, deploying networks,
                maintaining ICT equipment, providing technical support
                and training people with different levels of digital
                knowledge.
            </p>

            <p>My approach combines:</p>

            <ul>
                <li>Technical problem-solving</li>
                <li>ICT infrastructure management</li>
                <li>Networking</li>
                <li>User support</li>
                <li>Training and mentorship</li>
                <li>Project coordination</li>
                <li>Community engagement</li>
                <li>Innovation and continuous learning</li>
            </ul>

        </section>


        <!-- SKILLS -->
        <section id="skills">

            <h3>Core Competencies</h3>

            <div class="grid">

                <div class="card">

                    <h4>ICT Management</h4>

                    <ul>
                        <li>ICT infrastructure management</li>
                        <li>IT operations</li>
                        <li>Technical support</li>
                        <li>ICT asset management</li>
                        <li>Hardware and software troubleshooting</li>
                        <li>Systems administration</li>
                        <li>ICT project coordination</li>
                    </ul>

                </div>


                <div class="card">

                    <h4>Networking</h4>

                    <ul>
                        <li>LAN/WAN installation</li>
                        <li>Network configuration</li>
                        <li>Structured cabling</li>
                        <li>IP addressing</li>
                        <li>Router and switch configuration</li>
                        <li>Wireless networking</li>
                        <li>Network troubleshooting</li>
                        <li>CCTV networking</li>
                    </ul>

                </div>


                <div class="card">

                    <h4>Computer-Based Testing</h4>

                    <ul>
                        <li>CBT centre setup</li>
                        <li>CBT network configuration</li>
                        <li>Server configuration</li>
                        <li>Client computer deployment</li>
                        <li>Examination support</li>
                        <li>CBT troubleshooting</li>
                    </ul>

                </div>


                <div class="card">

                    <h4>Digital Skills Training</h4>

                    <ul>
                        <li>Digital literacy</li>
                        <li>Computer appreciation</li>
                        <li>Internet skills</li>
                        <li>Microsoft Office</li>
                        <li>Digital safety</li>
                        <li>ICT training for women and young people</li>
                    </ul>

                </div>

            </div>

        </section>


        <!-- EXPERIENCE -->
        <section id="experience">

            <h3>Professional Experience</h3>

            <div class="timeline">

                <div class="timeline-item">

                    <h4>
                        Fantsuam Foundation —
                        ICT Manager / ICT Professional
                    </h4>

                    <div class="year">
                        12+ Years
                    </div>

                    <p>
                        Responsible for supporting and managing the
                        organisation's ICT infrastructure and
                        technology-related activities.
                    </p>

                    <ul>
                        <li>Managing ICT infrastructure and equipment</li>
                        <li>Maintaining computer systems and networks</li>
                        <li>Providing technical support to staff</li>
                        <li>Managing network connectivity</li>
                        <li>Supporting servers and ICT systems</li>
                        <li>Managing CBT infrastructure</li>
                        <li>Providing ICT training</li>
                        <li>Coordinating technical projects</li>
                    </ul>

                </div>


                <div class="timeline-item">

                    <h4>
                        CBT ZittNet Academy —
                        CBT Academy Manager
                    </h4>

                    <div class="year">
                        2022 – Present
                    </div>

                    <p>
                        Managing technical and operational aspects
                        of a Computer-Based Testing environment,
                        including systems, networking, hardware,
                        candidate support and examination readiness.
                    </p>

                </div>


                <div class="timeline-item">

                    <h4>
                        Fantsuam Foundation —
                        CBT Technical Manager
                    </h4>

                    <div class="year">
                        2014 – 2017
                    </div>

                    <p>
                        Supported the technical setup, maintenance
                        and operation of CBT facilities, including
                        computer deployment, networking and
                        troubleshooting.
                    </p>

                </div>


                <div class="timeline-item">

                    <h4>
                        Rumbu Industry Limited, Kano —
                        Technical/Operator Assistant
                    </h4>

                    <div class="year">
                        2020 – 2021
                    </div>

                </div>


                <div class="timeline-item">

                    <h4>
                        Society for Family Health —
                        Community Facilitator
                    </h4>

                    <div class="year">
                        2015 – 2016
                    </div>

                </div>

            </div>

        </section>


        <!-- CBT -->
        <section>

            <h3>Computer-Based Testing Experience</h3>

            <p>
                One of my major areas of professional experience
                is the management and technical operation of
                Computer-Based Testing centres.
            </p>

            <div class="skills">

                <span class="skill">CBT Centre Setup</span>
                <span class="skill">Network Configuration</span>
                <span class="skill">Server/Client Configuration</span>
                <span class="skill">Examination Support</span>
                <span class="skill">Hardware Maintenance</span>
                <span class="skill">Network Troubleshooting</span>
                <span class="skill">Candidate Support</span>
                <span class="skill">System Preparation</span>

            </div>

        </section>


        <!-- NETWORKING -->
        <section>

            <h3>ICT Networking Projects</h3>

            <p>
                My networking experience includes planning,
                installation, configuration and maintenance
                of computer networks.
            </p>

            <div class="skills">

                <span class="skill">Structured Cabling</span>
                <span class="skill">Cat6 Installation</span>
                <span class="skill">Router Configuration</span>
                <span class="skill">Switch Configuration</span>
                <span class="skill">Wireless Networking</span>
                <span class="skill">IP Addressing</span>
                <span class="skill">CCTV Networking</span>
                <span class="skill">Server Connectivity</span>
                <span class="skill">Network Documentation</span>

            </div>

        </section>


        <!-- TRAINING -->
        <section id="training">

            <h3>
                Digital Skills Training &amp;
                Community Impact
            </h3>

            <p>
                I am passionate about using technology to empower
                people who may otherwise have limited access to
                digital opportunities.
            </p>

            <div class="grid">

                <div class="card">

                    <h4>900+ Women Trained</h4>

                    <p>
                        Trained over
                        <strong>900 women</strong>
                        in digital literacy over a six-week programme.
                    </p>

                </div>


                <div class="card">

                    <h4>50 Girls Trained</h4>

                    <p>
                        Delivered digital skills training to
                        <strong>50 girls</strong>
                        at secondary-school level.
                    </p>

                </div>

            </div>

            <p style="margin-top:20px;">

                <strong>
                    Simple → Practical → Inclusive →
                    Relevant → Empowering
                </strong>

            </p>

        </section>


        <!-- ACHIEVEMENTS -->
        <section id="achievements">

            <h3>Key Achievements</h3>

            <div class="grid">

                <div class="card">

                    <h4>ICT Infrastructure Management</h4>

                    <p>
                        Managed and supported ICT infrastructure
                        used by staff, students, candidates
                        and community members.
                    </p>

                </div>


                <div class="card">

                    <h4>CBT Operations</h4>

                    <p>
                        Supported deployment and operation of
                        CBT infrastructure for large numbers of
                        users and examination candidates.
                    </p>

                </div>


                <div class="card">

                    <h4>Digital Literacy</h4>

                    <p>
                        Trained hundreds of women, girls and
                        young people in practical digital skills.
                    </p>

                </div>


                <div class="card">

                    <h4>Network Deployment</h4>

                    <p>
                        Designed, installed, maintained and
                        troubleshot computer networks for
                        ICT laboratories and CBT environments.
                    </p>

                </div>


                <div class="card">

                    <h4>Technical Problem Solving</h4>

                    <p>
                        Provided hands-on solutions to hardware,
                        software, networking, server, power and
                        connectivity challenges.
                    </p>

                </div>


                <div class="card">

                    <h4>Community Technology</h4>

                    <p>
                        Used ICT as a tool for community development,
                        education and economic empowerment.
                    </p>

                </div>

            </div>

        </section>


        <!-- PROJECTS -->
        <section id="projects">

            <h3>Selected ICT Projects</h3>


            <div class="card">

                <h4>
                    Project 1: CBT Centre Network Deployment
                </h4>

                <p>
                    <strong>Role:</strong>
                    ICT/Technical Lead
                </p>

                <ul>
                    <li>Network planning</li>
                    <li>Structured cabling</li>
                    <li>Computer deployment</li>
                    <li>Switch installation</li>
                    <li>IP addressing</li>
                    <li>Server configuration</li>
                    <li>Client configuration</li>
                    <li>Testing and troubleshooting</li>
                </ul>

            </div>


            <br>


            <div class="card">

                <h4>
                    Project 2: Digital Skills Training for Women
                </h4>

                <p>
                    <strong>Role:</strong>
                    ICT Trainer
                </p>

                <ul>
                    <li>Curriculum preparation</li>
                    <li>Practical computer training</li>
                    <li>Internet training</li>
                    <li>Digital literacy</li>
                    <li>User support</li>
                </ul>

                <p>
                    <strong>Outcome:</strong>
                    Trained more than 900 women in practical
                    digital skills.
                </p>

            </div>


            <br>


            <div class="card">

                <h4>
                    Project 3: Digital Skills Training for Girls
                </h4>

                <p>
                    <strong>Target:</strong>
                    50 secondary-school girls
                </p>

                <p>
                    <strong>Focus:</strong>
                    Computer appreciation, internet use,
                    digital skills, online safety and practical
                    computer applications.
                </p>

            </div>


            <br>


            <div class="card">

                <h4>
                    Project 4: ICT Infrastructure Support
                </h4>

                <p>
                    <strong>Role:</strong>
                    ICT Manager
                </p>

                <ul>
                    <li>Hardware maintenance</li>
                    <li>Network troubleshooting</li>
                    <li>Server support</li>
                    <li>User support</li>
                    <li>ICT equipment management</li>
                    <li>Connectivity troubleshooting</li>
                </ul>

            </div>

        </section>


        <!-- TECHNICAL SKILLS -->
        <section>

            <h3>Technical Skills</h3>

            <h4>Hardware</h4>

            <div class="skills">

                <span class="skill">Desktop Computers</span>
                <span class="skill">Laptops</span>
                <span class="skill">Printers</span>
                <span class="skill">UPS Systems</span>
                <span class="skill">Network Equipment</span>
                <span class="skill">CCTV Equipment</span>
                <span class="skill">Servers</span>
                <span class="skill">Storage Devices</span>

            </div>


            <h4>Networking</h4>

            <div class="skills">

                <span class="skill">TCP/IP</span>
                <span class="skill">IPv4</span>
                <span class="skill">LAN</span>
                <span class="skill">WAN</span>
                <span class="skill">DHCP</span>
                <span class="skill">DNS Fundamentals</span>
                <span class="skill">Routing &amp; Switching</span>
                <span class="skill">Structured Cabling</span>
                <span class="skill">Wireless Networking</span>

            </div>


            <h4>
                Systems &amp; Emerging Technology
            </h4>

            <div class="skills">

                <span class="skill">Windows</span>
                <span class="skill">Server Environments</span>
                <span class="skill">Moodle</span>
                <span class="skill">CBT Systems</span>
                <span class="skill">Microsoft Office</span>
                <span class="skill">Cybersecurity Fundamentals</span>
                <span class="skill">Cloud Computing</span>
                <span class="skill">Data Analysis</span>
                <span class="skill">Artificial Intelligence</span>
                <span class="skill">IoT</span>
                <span class="skill">Web Technologies</span>

            </div>

        </section>


        <!-- EDUCATION -->
        <section>

            <h3>
                Education &amp;
                Professional Development
            </h3>

            <h4>Academic Background</h4>

            <p>
                <strong>
                    Graduate — Mechanical Engineering
                </strong>
            </p>

            <h4>
                ICT &amp;
                Professional Development
            </h4>

            <ul>
                <li>Cisco Networking</li>
                <li>IT Essentials</li>
                <li>Data Analysis</li>
                <li>Virtual Assistance</li>
                <li>Cybersecurity</li>
                <li>Digital Skills Training</li>
                <li>Computer-Based Testing</li>
                <li>ICT Infrastructure Management</li>
            </ul>

        </section>


        <!-- SERVICES -->
        <section>

            <h3>Services I Can Provide</h3>

            <div class="grid">

                <div class="card">

                    <h4>ICT Consultancy</h4>

                    <p>
                        ICT infrastructure assessment,
                        technology planning and ICT project
                        implementation.
                    </p>

                </div>


                <div class="card">

                    <h4>Networking</h4>

                    <p>
                        Network design, installation,
                        configuration, troubleshooting
                        and documentation.
                    </p>

                </div>


                <div class="card">

                    <h4>CBT Consultancy</h4>

                    <p>
                        CBT centre planning, network deployment,
                        hardware configuration and technical
                        operations.
                    </p>

                </div>


                <div class="card">

                    <h4>Digital Training</h4>

                    <p>
                        Computer literacy, digital skills,
                        internet literacy and ICT training
                        for organisations and communities.
                    </p>

                </div>


                <div class="card">

                    <h4>Technical Support</h4>

                    <p>
                        Computer troubleshooting, hardware
                        maintenance, software installation
                        and network support.
                    </p>

                </div>

            </div>

        </section>


        <!-- VALUE -->
        <section>

            <h3>My Professional Value</h3>

            <p>
                I bring together
                <strong>
                    technical knowledge, practical field
                    experience and community-focused
                    technology implementation.
                </strong>
            </p>

            <p>
                My strength is not only in understanding
                technology, but in making technology work
                in real-world environments.
            </p>

            <div class="skills">

                <span class="skill">Plan It</span>
                <span class="skill">Install It</span>
                <span class="skill">Configure It</span>
                <span class="skill">Troubleshoot It</span>
                <span class="skill">Train People</span>
                <span class="skill">Manage It</span>

            </div>

        </section>


        <!-- MISSION -->
        <section>

            <h3>Professional Mission</h3>

            <div class="quote">

                “To use technology to solve real-life problems,
                improve access to digital opportunities and
                empower individuals, organisations and communities.”

            </div>

        </section>


        <!-- VISION -->
        <section>

            <h3>Career Vision</h3>

            <p>
                My long-term goal is to contribute to organisations
                and technology projects where ICT can be used to
                improve productivity, education, employment,
                business development and community impact.
            </p>

            <div class="skills">

                <span class="skill">ICT Management</span>
                <span class="skill">IT Support</span>
                <span class="skill">Network Administration</span>
                <span class="skill">Systems Administration</span>
                <span class="skill">Technology Operations</span>
                <span class="skill">CBT Management</span>
                <span class="skill">Digital Transformation</span>
                <span class="skill">Digital Skills Training</span>
                <span class="skill">Technology for Development</span>

            </div>

        </section>


        <!-- CONTACT -->
        <section id="contact">

            <h3>Contact</h3>

            <div class="contact">

                <p>
                    <strong>
                        Ibrahim Doni Samaila
                    </strong>
                </p>

                <p>
                    ICT Manager |
                    Network &amp; Systems Technician |
                    ICT Trainer
                </p>

                <p>
                    📧 Email:
                    <em>[Your Email Address]</em>
                </p>

                <p>
                    📱 Phone:
                    <em>[Your Phone Number]</em>
                </p>

                <p>
                    🔗 LinkedIn:
                    <em>[Your LinkedIn Profile]</em>
                </p>

                <p>
                    📍 Location: Nigeria
                </p>

            </div>

        </section>


        <!-- FINAL STATEMENT -->
        <section>

            <h3>Professional Statement</h3>

            <div class="quote">

                “I believe that ICT is most profitable when
                it is used to solve real-life problems.”

                <br><br>

                <strong>
                    — Ibrahim Doni Samaila
                </strong>

        
</body>
</html>
