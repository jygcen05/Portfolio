<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jigme Wangchuk – Forestry & Conservation Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Roboto', sans-serif; margin:0; background:#f9f9f9; color:#333; line-height:1.6; }
        header { background:#2a5d34; color:#fff; padding:30px 20px; text-align:center; }
        header h1 { margin:0; font-size:2rem; }
        header p { margin:5px 0; }
        nav { display:flex; justify-content:center; background:#3a7a49; flex-wrap: wrap; }
        nav a { color:#fff; padding:15px 20px; text-decoration:none; font-weight:bold; }
        nav a:hover { background:#2a5d34; }
        section { padding:40px 20px; max-width:1000px; margin:auto; }
        h2 { color:#2a5d34; border-bottom:2px solid #2a5d34; padding-bottom:5px; }
        ul { list-style:none; padding-left:0; }
        li { margin-bottom:10px; }
        .contact a { color:#2a5d34; text-decoration:none; font-weight:bold; }
        .contact a:hover { text-decoration:underline; }
        footer { text-align:center; padding:20px; background:#3a7a49; color:#fff; }
        .grid { display:grid; grid-template-columns:1fr 1fr; gap:20px; }
        .project-card { background:#fff; padding:20px; border-radius:10px; box-shadow:0 2px 8px rgba(0,0,0,0.1); transition: transform 0.2s; }
        .project-card:hover { transform: scale(1.03); }
        .project-card img { max-width:100%; border-radius:8px; margin-bottom:10px; }
        .btn { display:inline-block; padding:10px 20px; background:#2a5d34; color:#fff; border-radius:5px; text-decoration:none; margin-top:10px; }
        .btn:hover { background:#1f4525; }
        @media (max-width:768px) { .grid { grid-template-columns:1fr; } }
    </style>
</head>
<body>

<header>
    <h1>Jigme Wangchuk</h1>
    <p>Senior Forestry Officer | Biodiversity & Conservation Specialist</p>
    <p>Thimphu, Bhutan | +975 77385897 | <a href="mailto:jigmewangchuk@moenr.gov.bt" class="contact">Email</a></p>
    <p><a href="#" class="contact">LinkedIn</a> | <a href="#" class="contact">ResearchGate</a></p>
    <a href="Jigme_Wangchuk_CV.pdf" class="btn" download>Download CV</a>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#research">Research</a>
    <a href="#projects">Projects</a>
    <a href="#publications">Publications</a>
    <a href="#skills">Skills</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about">
    <h2>About Me</h2>
    <p>Forestry and conservation leader specializing in biodiversity conservation, forest fire resilience, and ecosystem management in Bhutan.
       Experienced in policy implementation, inter-agency coordination, GIS, remote sensing, and field-based monitoring.
       Passionate about sustainable forest management, high conservation value areas, and community empowerment for ecological stewardship.</p>
</section>

<section id="research">
    <h2>Research</h2>
    <div class="grid">
        <div class="project-card">
            <img src="images/fish_study.jpg" alt="Freshwater Fishes of Dagana">
            <h3>The Freshwater Fishes of Dagana (2025)</h3>
            <p>Documented 47 freshwater fish species and established baseline data for aquatic biodiversity monitoring using GIS and field surveys.</p>
            <a href="reports/fish_study.pdf" class="btn" target="_blank">View Report</a>
        </div>
        <div class="project-card">
            <img src="images/climate_vulnerability.jpg" alt="Climate Vulnerability">
            <h3>Socio-economic & Climate Vulnerability (2024)</h3>
            <p>Conducted surveys and vulnerability assessments to recommend adaptive capacity building and community resilience measures.</p>
            <a href="reports/climate_vulnerability.pdf" class="btn" target="_blank">View Report</a>
        </div>
        <div class="project-card">
            <img src="images/biodiversity.jpg" alt="Rapid Biodiversity Assessment">
            <h3>Rapid Biodiversity Assessment (2023)</h3>
            <p>Recorded 288 floral species, 40 mammals, 647 birds, 144 butterflies, 15 amphibians, 27 reptiles, and 16 lady beetle species.</p>
            <a href="reports/biodiversity.pdf" class="btn" target="_blank">View Report</a>
        </div>
    </div>
</section>

<section id="projects">
    <h2>Projects</h2>
    <ul>
        <li><strong>Forest Fire Risk Mapping:</strong> National and landscape-level planning</li>
        <li><strong>Fish Diversity Studies:</strong> Dagana Division, Bhutan</li>
        <li><strong>Community & Social Forestry Programs</strong></li>
        <li><strong>Forest Pest & Disease Monitoring</strong></li>
        <li><strong>High Conservation Value (HCV) Area Management</strong></li>
        <li><strong>Field Data Collection & Analysis:</strong> Wildlife, insects, and aquatic biodiversity</li>
    </ul>
</section>

<section id="publications">
    <h2>Publications</h2>
    <ul>
        <li>Divisional Forest Office Management Plan – Dagana (2026)</li>
        <li>Conflicts to Co-existence (C2C) Strategy – Lhamoizingkha & Trashiding Gewogs (2026)</li>
        <li>A Pictorial Guide to the Freshwater Fishes of Dagana – 2025</li>
        <li>Carnivores Recorded in Sakteng Wildlife Sanctuary – Journal of Animal Diversity (2025)</li>
        <li>Diversity and Distribution of Ladybird Beetles in Zhemgang – Bhutan Journal of Natural Resources & Development (2024)</li>
        <li>Socio-economic Status & Climate Vulnerability of DFO Dagana – 2024</li>
        <li>Rapid Biodiversity Assessment Report – Dagana, 2023</li>
        <li>Forest Firefighting Training Manual for Gyalsung – 2023</li>
        <li>Six Species of Coccinellidae New to Bhutan – Oriental Insects (2021)</li>
    </ul>
</section>

<section id="skills">
    <h2>Skills</h2>
    <div class="grid">
        <div>
            <h3>Technical</h3>
            <ul>
                <li>GIS & Remote Sensing (ArcGIS, QGIS)</li>
                <li>Data Analysis: R, Excel</li>
                <li>Field Surveys & Monitoring (Wildlife, Fish, Insects, HCV areas)</li>
                <li>Forest Management & Firefighting</li>
                <li>Project & Financial Management</li>
                <li>Research & Reporting</li>
            </ul>
        </div>
        <div>
            <h3>Soft Skills</h3>
            <ul>
                <li>Leadership & Capacity Building</li>
                <li>Teamwork & Collaboration</li>
                <li>Communication & Stakeholder Engagement</li>
                <li>Gender Mainstreaming</li>
            </ul>
        </div>
    </div>
</section>

<section id="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:jigmewangchuk@moenr.gov.bt">jigmewangchuk@moenr.gov.bt</a></p>
    <p>Phone: +975 77385897</p>
    <p>LinkedIn: <a href="#">Profile</a></p>
    <p>ResearchGate: <a href="#">Profile</a></p>
</section>

<footer>
    <p>&copy; 2026 Jigme Wangchuk | All Rights Reserved</p>
</footer>

</body>
</html>
