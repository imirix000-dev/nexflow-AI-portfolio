<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>NexFlow AI | Automation & AI Agents</title>
<meta name="description" content="NexFlow AI builds intelligent AI agents and business automation workflows using n8n.">

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  scroll-behavior: smooth;
}

body {
  font-family: Arial, sans-serif;
  background: #080d18;
  color: #ffffff;
  line-height: 1.6;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 22px 8%;
  background: #0d1423;
  position: sticky;
  top: 0;
  z-index: 10;
  border-bottom: 1px solid #1c2940;
}

.logo {
  font-size: 25px;
  font-weight: bold;
  color: #38bdf8;
}

nav a {
  color: #cbd5e1;
  text-decoration: none;
  margin-left: 22px;
  font-size: 14px;
}

nav a:hover {
  color: #38bdf8;
}

.hero {
  min-height: 85vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 50px 20px;
  background: radial-gradient(circle at top, #142b49, #080d18 65%);
}

.hero h1 {
  font-size: clamp(38px, 7vw, 68px);
  margin-bottom: 20px;
}

.hero h1 span {
  color: #38bdf8;
}

.hero p {
  max-width: 650px;
  color: #a9b8ca;
  font-size: 18px;
  margin-bottom: 30px;
}

.btn {
  display: inline-block;
  padding: 13px 25px;
  border-radius: 8px;
  background: #0ea5e9;
  color: white;
  text-decoration: none;
  font-weight: bold;
  margin: 6px;
  transition: .3s;
}

.btn:hover {
  background: #0284c7;
  transform: translateY(-3px);
}

.btn-outline {
  background: transparent;
  border: 1px solid #38bdf8;
}

section {
  padding: 75px 8%;
}

.section-title {
  text-align: center;
  font-size: 34px;
  margin-bottom: 40px;
}

.section-title span {
  color: #38bdf8;
}

.about {
  max-width: 850px;
  margin: auto;
  text-align: center;
  color: #a9b8ca;
  font-size: 17px;
}

.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
  gap: 22px;
}

.card {
  background: #111c2e;
  border: 1px solid #23344c;
  padding: 28px;
  border-radius: 14px;
  transition: .3s;
}

.card:hover {
  transform: translateY(-6px);
  border-color: #38bdf8;
}

.card h3 {
  color: #38bdf8;
  margin-bottom: 12px;
}

.card p {
  color: #a9b8ca;
}

.skills {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 12px;
}

.skill {
  padding: 12px 20px;
  background: #13243a;
  border: 1px solid #28415d;
  border-radius: 30px;
  color: #7dd3fc;
}

.contact {
  text-align: center;
  background: #0d1423;
}

.contact p {
  color: #a9b8ca;
  margin-bottom: 20px;
}

footer {
  text-align: center;
  padding: 25px;
  color: #7c8da3;
  border-top: 1px solid #1c2940;
}

@media(max-width: 650px) {
  header {
    flex-direction: column;
    gap: 15px;
  }
  nav a {
    margin: 0 7px;
    font-size: 12px;
  }
}
</style>
</head>

<body>

<header>
  <div class="logo">NexFlow AI.</div>
  <nav>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section class="hero">
  <h1>Automate Your Business<br><span>With AI.</span></h1>
  <p>
    I build intelligent AI agents and automation workflows
    that help businesses save time, improve customer support
    and grow faster.
  </p>
  <div>
    <a href="#contact" class="btn">Work With Me</a>
    <a href="#projects" class="btn btn-outline">View Projects</a>
  </div>
</section>

<section id="about">
  <h2 class="section-title">About <span>Me</span></h2>
  <div class="about">
    <p>
      I'm the creator of NexFlow AI, an automation specialist
      focused on building practical AI-powered solutions for businesses.
      I work with n8n to connect applications, automate repetitive tasks
      and create intelligent workflows.
    </p>
    <br>
    <p><strong>Experience Level:</strong> Intermediate</p>
  </div>
</section>

<section id="services">
  <h2 class="section-title">My <span>Services</span></h2>
  <div class="grid">
    <div class="card">
      <h3>AI Agents</h3>
      <p>Intelligent agents that understand messages and automate business tasks.</p>
    </div>
    <div class="card">
      <h3>WhatsApp Automation</h3>
      <p>Automated WhatsApp responses and customer communication workflows.</p>
    </div>
    <div class="card">
      <h3>Customer Support</h3>
      <p>Smart customer support systems that organize and manage incoming requests.</p>
    </div>
    <div class="card">
      <h3>Lead Generation</h3>
      <p>Automated lead collection, organization and follow-up workflows.</p>
    </div>
  </div>
</section>

<section>
  <h2 class="section-title">My <span>Skills</span></h2>
  <div class="skills">
    <div class="skill">n8n</div>
    <div class="skill">AI Agents</div>
    <div class="skill">Workflow Automation</div>
    <div class="skill">Webhooks</div>
    <div class="skill">Google Sheets</div>
    <div class="skill">API Integration</div>
    <div class="skill">WhatsApp Integration</div>
  </div>
</section>

<section id="projects">
  <h2 class="section-title">Demo <span>Projects</span></h2>
  <div class="grid">
    <div class="card">
      <h3>WhatsApp AI Agent</h3>
      <p>An example workflow for automated WhatsApp customer conversations.</p>
    </div>
    <div class="card">
      <h3>Customer Support Tracker</h3>
      <p>An example system connecting customer messages with Google Sheets.</p>
    </div>
    <div class="card">
      <h3>Lead Capture Workflow</h3>
      <p>An example automation for collecting and organizing potential customers.</p>
    </div>
  </div>
  <p style="text-align:center;color:#8193aa;margin-top:20px">
    These are demonstration concepts, not paid client projects.
  </p>
</section>

<section id="contact" class="contact">
  <h2 class="section-title">Let's <span>Work Together</span></h2>
  <p>Have a business task you want to automate? Let's talk.</p>

  <a class="btn"
     href="https://wa.me/212767018041"
     target="_blank">
     Contact on WhatsApp
  </a>

  <a class="btn btn-outline"
     href="mailto:imirix000@gmail.com">
     Send an Email
  </a>
</section>

<footer>
  © 2026 NexFlow AI. All Rights Reserved.
</footer>

</body>
</html>
