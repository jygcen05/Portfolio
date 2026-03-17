<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Jigme Wangchuk – Forestry & Conservation</title>
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
<style>
/* Reset & base styles */
* { margin:0; padding:0; box-sizing:border-box; }
body { font-family:'Roboto', sans-serif; color:#333; line-height:1.6; background:#f5f5f5; }
a { text-decoration:none; color:#2a5d34; }
a:hover { text-decoration:underline; }

/* Header / Hero */
header { background:#2a5d34; color:#fff; padding:60px 20px; text-align:center; }
header h1 { font-size:2.5rem; margin-bottom:10px; }
header p { font-size:1.1rem; margin-bottom:15px; }
header .btn { display:inline-block; padding:10px 20px; background:#fff; color:#2a5d34; border-radius:5px; font-weight:bold; transition:0.3s; }
header .btn:hover { background:#e0e0e0; }

/* Navigation */
nav { background:#3a7a49; display:flex; justify-content:center; flex-wrap:wrap; }
nav a { padding:15px 25px; color:#fff; font-weight:500; transition:0.3s; }
nav a:hover { background:#2a5d34; }

/* Sections */
section { padding:60px 20px; max-width:1000px; margin:auto; background:#fff; margin-bottom:20px; border-radius:10px; box-shadow:0 3px 10px rgba(0,0,0,0.05); }
section h2 { color:#2a5d34; border-bottom:2px solid #2a5d34; padding-bottom:5px; margin-bottom:20px; }

/* Grid for projects / skills */
.grid { display:grid; grid-template-columns:1fr 1fr; gap:20px; }
.project-card { background:#f9f9f9; padding:20px; border-radius:10px; box-shadow:0 2px 8px rgba(0,0,0,0.1); transition:transform 0.3s; }
.project-card:hover { transform:translateY(-5px); }
.project-card img { width:100%; border-radius:8px; margin-bottom:15px; }
.project-card h3 { margin-bottom:10px; }

/* Skills */
.skills ul { display:grid; grid-template-columns:1fr 1fr; gap:20px; list-style:none; padding-left:0; }
.skills li { background:#e0f0e3; padding:10px 15px; border-radius:5px; margin-bottom:10px; }

/* Contact */
.contact a { color:#2a5d34; font-weight:bold; }

/* Footer */
footer { text-align:center; padding:20px; background:#3a7a49; color:#fff; }

/* Responsive */
@media (max-width:768px) {
    .grid, .skills ul { grid-template-columns:1fr; }
}
</style>
</head>
<body>

<header>
<h1>Jigme Wangchuk</h1>
<p>Senior Forestry Officer | Department of Forests and Park Services</p>
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
<p>Forestry and conservation leader specializing in biodiversity conservation, forest fire resilience, and ecosystem management in Bhutan. Experienced in policy implementation, inter-agency coordination, GIS, remote sensing, and field-based monitoring. Passionate about sustainable forest management, high conservation value areas, and community empowerment for ecological stewardship.</p>
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
<li>Forest Fire Risk Mapping – National and landscape-level planning</li>
<li>Fish Diversity Studies – Dagana Division, Bhutan</li>
<li>Community & Social Forestry Programs</li>
<li>Forest Pest & Disease Monitoring</li>
<li>High Conservation Value (HCV) Area Management</li>
<li>Field Data Collection & Analysis: Wildlife, insects, and aquatic biodiversity</li>
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
<div class="skills">
<ul>
<li>GIS & Remote Sensing (ArcGIS, QGIS)</li>
<li>Data Analysis: R, Excel</li>
<li>Field Surveys & Monitoring (Wildlife, Fish, Insects, HCV areas)</li>
<li>Forest Management & Firefighting</li>
<li>Project & Financial Management</li>
<li>Research & Reporting</li>
<li>Leadership & Capacity Building</li>
<li>Teamwork & Collaboration</li>
<li>Communication & Stakeholder Engagement</li>
<li>Gender Mainstreaming</li>
</ul>
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
