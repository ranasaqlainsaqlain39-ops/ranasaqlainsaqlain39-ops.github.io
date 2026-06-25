---
layout: page
title: About
icon: fas fa-user
order: 1
---

<style>
.about-hero {
  background: linear-gradient(135deg, #0f0c29, #302b63);
  border-radius: 20px;
  padding: 48px 40px;
  color: white;
  margin-bottom: 36px;
}
.about-name { font-size: 2rem; font-weight: 800; margin-bottom: 8px; }
.about-role { color: #e94560; font-weight: 600; margin-bottom: 20px; font-size: 15px; }
.about-bio { color: #a8b2c1; line-height: 1.9; font-size: 15px; max-width: 600px; }
.about-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 20px;
  margin-bottom: 32px;
}
.about-card {
  background: white;
  border-radius: 14px;
  padding: 28px;
  box-shadow: 0 4px 20px rgba(0,0,0,0.07);
  border-top: 4px solid #e94560;
}
.about-card:nth-child(2) { border-top-color: #302b63; }
.about-card h3 { font-size: 16px; font-weight: 700; margin-bottom: 16px; color: #1a1a2e; }
.about-card p, .about-card li { font-size: 14px; color: #555; line-height: 1.8; }
.about-card ul { padding-left: 20px; }
.prof-card {
  background: linear-gradient(135deg, #1a1a2e, #302b63);
  border-radius: 16px;
  padding: 32px;
  color: white;
  margin-bottom: 32px;
}
.prof-card h3 { font-size: 1.3rem; font-weight: 800; margin-bottom: 8px; }
.prof-card p { color: #a8b2c1; line-height: 1.8; font-size: 14px; }
.prof-links { display: flex; gap: 12px; flex-wrap: wrap; margin-top: 20px; }
.prof-link {
  background: rgba(233,69,96,0.2);
  color: #e94560 !important;
  padding: 8px 18px;
  border-radius: 8px;
  text-decoration: none !important;
  font-size: 13px;
  font-weight: 600;
  border: 1px solid rgba(233,69,96,0.3);
}
.connect-card {
  background: #f8f9fa;
  border-radius: 14px;
  padding: 28px;
  text-align: center;
}
.connect-card a {
  display: inline-block;
  margin: 6px;
  padding: 10px 22px;
  border-radius: 8px;
  background: #1a1a2e;
  color: white !important;
  text-decoration: none !important;
  font-size: 14px;
  font-weight: 600;
}
</style>

<div class="about-hero">
  <div class="about-name">Rana Muhammad Saqlain</div>
  <div class="about-role">🎓 Computer Engineering Student · UET Faisalabad</div>
  <p class="about-bio">
    I am a first-year Computer Engineering student at the University of Engineering and Technology, Faisalabad Campus. I created this blog to document my academic journey — every concept I learn, every challenge I face, and every small win I celebrate along the way. My goal is to leave a meaningful digital footprint as a student and grow into a skilled engineer.
  </p>
</div>

<div class="about-grid">
  <div class="about-card">
    <h3>📋 My Details</h3>
    <ul>
      <li><strong>Name:</strong> Rana Muhammad Saqlain</li>
      <li><strong>Roll No:</strong> 2025-BSCPE-146</li>
      <li><strong>Section:</strong> B</li>
      <li><strong>Degree:</strong> BS Computer Engineering</li>
      <li><strong>Campus:</strong> UET Faisalabad</li>
      <li><strong>Year:</strong> 1st Year (2025–2026)</li>
    </ul>
  </div>
  <div class="about-card">
    <h3>💻 This Semester</h3>
    <ul>
      <li>🐍 Programming Fundamentals (Python)</li>
      <li>🗄️ Database Systems (SQL)</li>
      <li>⚡ Digital Logic Design</li>
      <li>📐 Object Oriented Programming</li>
    </ul>
    <p style="margin-top:12px;">Writing blog posts about Python and DBS as part of my coursework under Dr. Bilal Ahmad.</p>
  </div>
</div>

<div class="prof-card">
  <h3>👨‍🏫 About My Professor — Dr. Bilal Ahmad</h3>
  <p>
    Dr. Bilal Ahmad is our professor for Programming Fundamentals and Database Systems at UET Faisalabad. He is an expert in Artificial Intelligence, Machine Learning, and Deep Learning — with a focus on training ML models on real-world problems, particularly using medical datasets known for their precision and accuracy. His teaching style connects first-year fundamentals to cutting-edge AI research, which makes every lecture genuinely inspiring.
  </p>
  <div class="prof-links">
    <a href="https://www.linkedin.com/in/drbilalphd/" class="prof-link">🔗 LinkedIn</a>
    <a href="https://scholar.google.com.au/citations?user=8nZ0jVkAAAAJ&hl=en" class="prof-link">📚 Google Scholar</a>
    <a href="https://www.facebook.com/Dr.BilalAhm" class="prof-link">📘 Facebook</a>
  </div>
</div>

<div class="connect-card">
  <h3 style="margin-bottom:16px;">🤝 Connect With Me</h3>
  <a href="https://github.com/ranasaqlainsaqlain39-ops">🐙 GitHub</a>
  <a href="mailto:ranasaqlainsaqlain39@email.com">📧 Email Me</a>
</div>
