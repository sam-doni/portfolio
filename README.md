<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ibrahim Doni Samaila | ICT & Technology Professional Portfolio</title>
<style>
    :root {
        --primary: #123b5d;
        --secondary: #1f6f8b;
        --accent: #e7a93b;
        --light: #f4f7f9;
        --dark: #1d2730;
        --muted: #667784;
        --white: #fff;
    }
    * { box-sizing: border-box; }
    html { scroll-behavior: smooth; }
    body {
        margin: 0;
        font-family: Arial, Helvetica, sans-serif;
        color: var(--dark);
        background: #eef2f5;
        line-height: 1.65;
    }
    header {
        background: linear-gradient(135deg, var(--primary), var(--secondary));
        color: white;
        padding: 70px 20px 55px;
        text-align: center;
    }
    .hero {
        max-width: 1050px;
        margin: auto;
    }
    .hero h1 {
        margin: 0 0 8px;
        font-size: clamp(2.2rem, 6vw, 4rem);
        letter-spacing: 1px;
    }
    .hero h2 {
        margin: 0 auto 25px;
        font-size: clamp(1rem, 2.5vw, 1.35rem);
        font-weight: 400;
        max-width: 850px;
    }
    .tagline {
        display: inline-block;
        background: rgba(255,255,255,.12);
        border: 1px solid rgba(255,255,255,.25);
        padding: 10px 18px;
        border-radius: 30px;
        font-style: italic;
    }
    nav {
        position: sticky;
        top: 0;
        z-index: 10;
        background: rgba(18,59,93,.97);
        box-shadow: 0 2px 10px rgba(0,0,0,.12);
    }
    nav .nav-inner {
        max-width: 1100px;
        margin: auto;
        display: flex;
        gap: 6px;
        overflow-x: auto;
        padding: 8px 12px;
    }
    nav a {
        color: white;
        text-decoration: none;
        white-space: nowrap;
        padding: 9px 12px;
        border-radius: 6px;
        font-size: .9rem;
    }
    nav a:hover { background: var(--secondary); }
    main {
        max-width: 1100px;
        margin: 30px auto;
        padding: 0 18px;
    }
    section {
        background: white;
        margin-bottom: 24px;
        padding: 35px;
        border-radius: 12px;
        box-shadow: 0 4px 18px rgba(20,40,60,.07);
    }
    section h2 {
        color: var(--primary);
        margin-top: 0;
        font-size: 1.8rem;
        border-bottom: 3px solid var(--accent);
        padding-bottom: 8px;
    }
    h3 { color: var(--secondary); margin-bottom: 8px; }
    .lead { font-size: 1.08rem; color: #394b58; }
    .grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
        gap: 16px;
    }
    .card {
        background: var(--light);
        padding: 20px;
        border-radius: 10px;
        border-left: 4px solid var(--secondary);
    }
    .card h3 { margin-top: 0; }
    ul { padding-left: 22px; }
    .skills {
        display: flex;
        flex-wrap: wrap;
        gap: 9px;
    }
    .skill {
        background: #e9f2f6;
        color: var(--primary);
        border: 1px solid #c9dfe8;
        padding: 7px 12px;
        border-radius: 20px;
        font-size: .92rem;
    }
    .timeline {
        border-left: 3px solid var(--secondary);
        padding-left: 22px;
    }
    .timeline-item {
        position: relative;
        margin-bottom: 25px;
    }
    .timeline-item::before {
        content: "";
        position: absolute;
        left: -31px;
        top: 6px;
        width: 13px;
        height: 13px;
        border-radius: 50%;
        background: var(--accent);
        border: 3px solid white;
        box-shadow: 0 0 0 2px var(--secondary);
    }
    .achievement {
        padding: 18px;
        border-radius: 9px;
        background: #faf7ef;
        border-left: 4px solid var(--accent);
    }
    blockquote {
        margin: 20px 0;
        padding: 22px 25px;
        background: var(--light);
        border-left: 5px solid var(--accent);
        font-size: 1.25rem;
        font-style: italic;
        color: var(--primary);
    }
    .contact {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
        gap: 15px;
    }
    .contact div {
        padding: 18px;
        background: var(--light);
        border-radius: 8px;
    }
    footer {
        text-align: center;
        background: var(--primary);
        color: white;
        padding: 30px 18px;
        margin-top: 30px;
    }
    footer strong { color: var(--accent); }
    @media (max-width: 650px) {
        section { padding: 24px 20px; }
        header { padding-top: 50px; }
    }
    @media print {
        nav { display: none; }
        body { background: white; }
        section { box-shadow: none; page-break-inside: avoid; }
    }
</style>
</head>
<body>

<header id="home">
    <div class="hero">
        <h1>IBRAHIM DONI SAMAILA</h1>
        <h2>ICT Manager | Network &amp; Systems Technician | CBT Centre Manager | ICT Trainer | Digital Skills Advocate</h2>
        <div class="tagline">Using ICT to solve real-life problems and empower people.</div>
    </div>
</header>

<nav>
    <div class="nav-inner">
        <a href="#about">About</a>
        <a href="#competencies">Competencies</a>
        <a href="#experience">Experience</a>
        <a href="#cbt">CBT</a>
        <a href="#projects">Projects</a>
        <a href="#impact">Impact</a>
        <a href="#skills">Skills</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </div>
</nav>

<main>
<section id="about">
    <h2>Professional Profile</h2>
    <p class="lead">
        I am an ICT professional with over <strong>12 years of practical experience</strong> in information and communication technology,
        ICT infrastructure management, computer-based testing, networking, technical support, digital skills training,
        and technology-driven community development.
    </p>
    <p>
        My professional experience covers the design, installation and maintenance of computer networks, management of ICT infrastructure,
        operation of Computer-Based Testing (CBT) centres, server and systems support, digital literacy training, and technical support for organisations and communities.
    </p>
    <p>
        I strongly believe that technology is most valuable when it is used to solve real-life problems, improve productivity,
        create opportunities and empower people.
    </p>
</section>

<section>
    <h2>About Me</h2>
    <p>
        My professional journey has been driven by a passion for technology and its ability to create positive social and economic impact.
        I have developed practical experience managing ICT environments, supporting users, setting up computer laboratories and CBT centres,
        deploying networks, maintaining ICT equipment, providing technical support and training people with different levels of digital knowledge.
    </p>
    <p>My approach combines:</p>
    <div class="skills">
        <span class="skill">Technical Problem-Solving</span>
        <span class="skill">ICT Infrastructure Management</span>
        <span class="skill">Networking</span>
        <span class="skill">User Support</span>
        <span class="skill">Training &amp; Mentorship</span>
        <span class="skill">Project Coordination</span>
        <span class="skill">Community Engagement</span>
        <span class="skill">Innovation</span>
    </div>
</section>

<section id="competencies">
    <h2>Core Competencies</h2>
    <div class="grid">
        <div class="card">
            <h3>ICT Management</h3>
            <ul>
                <li>ICT infrastructure management</li>
                <li>IT operations and technical support</li>
                <li>Hardware and software troubleshooting</li>
                <li>ICT asset management</li>
                <li>Systems administration</li>
                <li>ICT project coordination</li>
            </ul>
        </div>
        <div class="card">
            <h3>Networking</h3>
            <ul>
                <li>LAN/WAN installation</li>
                <li>Structured cabling</li>
                <li>IP addressing</li>
                <li>Router and switch configuration</li>
                <li>Wireless networking</li>
                <li>Network troubleshooting</li>
                <li>CCTV networking</li>
            </ul>
        </div>
        <div class="card">
            <h3>CBT Operations</h3>
            <ul>
                <li>CBT centre setup</li>
                <li>CBT network configuration</li>
                <li>Server/client configuration</li>
                <li>Examination support</li>
                <li>Hardware maintenance</li>
                <li>Technical troubleshooting</li>
            </ul>
        </div>
        <div class="card">
            <h3>Digital Training</h3>
            <ul>
                <li>Digital literacy</li>
                <li>Computer appreciation</li>
                <li>Internet skills</li>
                <li>Microsoft Office</li>
                <li>Digital safety</li>
                <li>Community technology training</li>
            </ul>
        </div>
    </div>
</section>

<section id="experience">
    <h2>Professional Experience</h2>
    <div class="timeline">
        <div class="timeline-item">
            <h3>Fantsuam Foundation — ICT Manager / ICT Professional</h3>
            <strong>12+ Years</strong>
            <p>Managing and supporting organisational ICT infrastructure and technology-related activities.</p>
            <ul>
                <li>Manage ICT infrastructure and equipment.</li>
                <li>Maintain computer systems and networks.</li>
                <li>Provide technical support to staff.</li>
                <li>Set up and maintain computer laboratories.</li>
                <li>Support servers, connectivity and ICT systems.</li>
                <li>Manage CBT infrastructure and technical operations.</li>
                <li>Provide ICT training and support digital programmes.</li>
            </ul>
        </div>
        <div class="timeline-item">
            <h3>CBT ZittNet Academy — CBT Academy Manager</h3>
            <strong>2022 – Present</strong>
            <p>Managing CBT technical operations, infrastructure, systems and examination support.</p>
        </div>
        <div class="timeline-item">
            <h3>Fantsuam Foundation — CBT Technical Manager</h3>
            <strong>2014 – 2017</strong>
            <p>Provided technical management and operational support for CBT activities.</p>
        </div>
        <div class="timeline-item">
            <h3>Rumbu Industry Limited, Kano — Technical/Operator Assistant</h3>
            <strong>2020 – 2021</strong>
        </div>
        <div class="timeline-item">
            <h3>Society for Family Health — Community Facilitator</h3>
            <strong>2015 – 2016</strong>
        </div>
    </div>
</section>

<section id="cbt">
    <h2>Computer-Based Testing Experience</h2>
    <p>
        One of my major areas of professional experience is the management and technical operation of Computer-Based Testing centres.
    </p>
    <div class="grid">
        <div class="card"><h3>Centre Setup</h3><p>Planning and deploying CBT computer environments and supporting infrastructure.</p></div>
        <div class="card"><h3>Network Configuration</h3><p>Connecting and configuring large numbers of computers for reliable examination operations.</p></div>
        <div class="card"><h3>Server Support</h3><p>Supporting servers, clients and examination software environments.</p></div>
        <div class="card"><h3>Examination Support</h3><p>Providing technical support before and during examination activities.</p></div>
    </div>
    <div class="achievement">
        <strong>CBT Impact:</strong> Contributed to the successful registration and examination support of thousands of candidates through CBT-related services and infrastructure.
    </div>
</section>

<section>
    <h2>ICT Networking Experience</h2>
    <p>My networking experience includes the planning, installation, configuration and maintenance of computer networks.</p>
    <div class="skills">
        <span class="skill">Structured Cabling</span>
        <span class="skill">Cat6 Installation</span>
        <span class="skill">Router Configuration</span>
        <span class="skill">Switch Configuration</span>
        <span class="skill">Wireless Access Points</span>
        <span class="skill">IPv4 Addressing</span>
        <span class="skill">Network Troubleshooting</span>
        <span class="skill">CCTV Integration</span>
        <span class="skill">Server Connectivity</span>
        <span class="skill">Network Documentation</span>
    </div>
</section>

<section id="impact">
    <h2>Digital Skills Training &amp; Community Impact</h2>
    <p>
        I am passionate about using technology to empower people who may otherwise have limited access to digital opportunities.
    </p>
    <div class="grid">
        <div class="achievement">
            <h3>900+ Women Trained</h3>
            <p>Trained over 900 women in digital literacy through a six-week programme.</p>
        </div>
        <div class="achievement">
            <h3>50 Girls Trained</h3>
            <p>Delivered digital skills training to 50 girls at secondary-school level.</p>
        </div>
        <div class="achievement">
            <h3>Community Empowerment</h3>
            <p>Provided practical digital skills and technology support to community members and young people.</p>
        </div>
    </div>
    <h3>Training Philosophy</h3>
    <p><strong>Simple → Practical → Inclusive → Relevant → Empowering</strong></p>
</section>

<section id="projects">
    <h2>Selected ICT Projects</h2>
    <div class="card">
        <h3>Project 1: CBT Centre Network Deployment</h3>
        <p><strong>Role:</strong> ICT/Technical Lead</p>
        <p>Network planning, structured cabling, switch installation, IP addressing, server/client configuration, testing and troubleshooting.</p>
    </div>
    <br>
    <div class="card">
        <h3>Project 2: Digital Skills Training for Women</h3>
        <p><strong>Role:</strong> ICT Trainer</p>
        <p>Curriculum preparation, practical computer training, internet training, digital literacy and user support for more than 900 women.</p>
    </div>
    <br>
    <div class="card">
        <h3>Project 3: Digital Skills Training for Girls</h3>
        <p><strong>Role:</strong> ICT Trainer</p>
        <p>Delivered computer appreciation, internet skills, digital safety and practical computer training to 50 girls.</p>
    </div>
    <br>
    <div class="card">
        <h3>Project 4: ICT Infrastructure Support</h3>
        <p><strong>Role:</strong> ICT Manager</p>
        <p>Hardware maintenance, network troubleshooting, server support, user support, ICT equipment management and connectivity troubleshooting.</p>
    </div>
</section>

<section>
    <h2>Key Achievements</h2>
    <div class="grid">
        <div class="achievement"><strong>ICT Infrastructure:</strong> Managed and supported ICT infrastructure used by staff, students, candidates and community members.</div>
        <div class="achievement"><strong>CBT Operations:</strong> Supported large-scale CBT registration and examination activities.</div>
        <div class="achievement"><strong>Digital Literacy:</strong> Trained hundreds of women, girls and young people in practical digital skills.</div>
        <div class="achievement"><strong>Network Deployment:</strong> Designed, installed, maintained and troubleshot computer networks.</div>
        <div class="achievement"><strong>Technical Problem Solving:</strong> Resolved hardware, software, networking, server, power and connectivity challenges.</div>
        <div class="achievement"><strong>Community Technology:</strong> Used ICT for education, community development and economic empowerment.</div>
    </div>
</section>

<section id="skills">
    <h2>Technical Skills</h2>
    <h3>Hardware</h3>
    <div class="skills">
        <span class="skill">Desktop Computers</span><span class="skill">Laptops</span><span class="skill">Printers</span>
        <span class="skill">UPS Systems</span><span class="skill">Network Equipment</span><span class="skill">CCTV</span>
        <span class="skill">Servers</span><span class="skill">Storage Devices</span>
    </div>
    <h3>Networking &amp; Systems</h3>
    <div class="skills">
        <span class="skill">TCP/IP</span><span class="skill">IPv4</span><span class="skill">LAN</span>
        <span class="skill">WAN</span><span class="skill">DHCP</span><span class="skill">DNS Fundamentals</span>
        <span class="skill">Routing &amp; Switching</span><span class="skill">Structured Cabling</span>
        <span class="skill">Wireless Networking</span><span class="skill">Windows</span>
        <span class="skill">Moodle</span><span class="skill">CBT Systems</span><span class="skill">Microsoft Office</span>
    </div>
    <h3>Emerging Technology</h3>
    <div class="skills">
        <span class="skill">Cybersecurity Fundamentals</span>
        <span class="skill">Cloud Computing Fundamentals</span>
        <span class="skill">Data Analysis</span>
        <span class="skill">Artificial Intelligence Fundamentals</span>
        <span class="skill">Internet of Things</span>
        <span class="skill">Web Technologies</span>
    </div>
</section>

<section>
    <h2>Education &amp; Professional Development</h2>
    <h3>Academic Background</h3>
    <p><strong>Graduate — Mechanical Engineering</strong></p>
    <h3>ICT &amp; Professional Development</h3>
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

<section id="services">
    <h2>Services I Can Provide</h2>
    <div class="grid">
        <div class="card">
            <h3>ICT Consultancy</h3>
            <ul><li>ICT infrastructure assessment</li><li>Technology planning</li><li>ICT project implementation</li></ul>
        </div>
        <div class="card">
            <h3>Networking</h3>
            <ul><li>Network design</li><li>Installation</li><li>Configuration</li><li>Troubleshooting</li><li>Documentation</li></ul>
        </div>
        <div class="card">
            <h3>CBT Consultancy</h3>
            <ul><li>CBT centre planning</li><li>Network deployment</li><li>Hardware configuration</li><li>Technical operations</li></ul>
        </div>
        <div class="card">
            <h3>Digital Training</h3>
            <ul><li>Computer literacy</li><li>Digital skills</li><li>Internet literacy</li><li>Organisational training</li></ul>
        </div>
        <div class="card">
            <h3>Technical Support</h3>
            <ul><li>Computer troubleshooting</li><li>Hardware maintenance</li><li>Software installation</li><li>Network support</li></ul>
        </div>
    </div>
</section>

<section>
    <h2>My Professional Value</h2>
    <p class="lead">
        I bring together <strong>technical knowledge, practical field experience and community-focused technology implementation</strong>.
    </p>
    <p>My strength is not only in understanding technology, but in making technology work in real-world environments.</p>
    <div class="skills">
        <span class="skill">Plan It</span>
        <span class="skill">Install It</span>
        <span class="skill">Configure It</span>
        <span class="skill">Troubleshoot It</span>
        <span class="skill">Train People</span>
        <span class="skill">Manage It</span>
    </div>
</section>

<section>
    <h2>Professional Mission</h2>
    <blockquote>
        “To use technology to solve real-life problems, improve access to digital opportunities and empower individuals, organisations and communities.”
    </blockquote>
</section>

<section>
    <h2>Career Vision</h2>
    <p>
        My long-term goal is to contribute to organisations and technology projects where ICT can be used to improve productivity,
        education, employment, business development and community impact.
    </p>
    <p>I am particularly interested in opportunities involving:</p>
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

<section id="contact">
    <h2>Contact</h2>
    <div class="contact">
        <div><strong>Name</strong><br>Ibrahim Doni Samaila</div>
        <div><strong>Profession</strong><br>ICT Manager / ICT Trainer</div>
        <div><strong>Email</strong><br>[Your Email Address]</div>
        <div><strong>Phone</strong><br>[Your Phone Number]</div>
        <div><strong>LinkedIn</strong><br>[Your LinkedIn Profile]</div>
        <div><strong>Location</strong><br>Nigeria</div>
    </div>
</section>
</main>

<footer>
    <p><strong>IBRAHIM DONI SAMAILA</strong></p>
    <p>ICT Manager | Network &amp; Systems Technician | ICT Trainer</p>
    <p>“I believe that ICT is most profitable when it is used to solve real-life problems.”</p>
</footer>

</body>
</html>
