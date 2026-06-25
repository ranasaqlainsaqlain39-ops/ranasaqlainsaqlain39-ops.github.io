---
layout: home
title: "Rana Muhammad Saqlain"
---

<style>
.hero-section {
  background: linear-gradient(135deg, #0f0c29, #302b63, #24243e);
  padding: 60px 40px;
  border-radius: 20px;
  margin-bottom: 40px;
  color: white;
  position: relative;
  overflow: hidden;
}
.hero-section::before {
  content: '';
  position: absolute;
  top: -50%;
  right: -20%;
  width: 400px;
  height: 400px;
  background: radial-gradient(circle, rgba(233,69,96,0.15) 0%, transparent 70%);
  border-radius: 50%;
}
.hero-top {
  display: flex;
  align-items: center;
  gap: 32px;
  flex-wrap: wrap;
  margin-bottom: 40px;
}
.hero-badge {
  display: inline-block;
  background: rgba(233,69,96,0.2);
  color: #e94560;
  padding: 6px 16px;
  border-radius: 20px;
  font-size: 13px;
  font-weight: 600;
  letter-spacing: 1px;
  margin-bottom: 12px;
  border: 1px solid rgba(233,69,96,0.4);
}
.hero-name {
  font-size: 2.6rem;
  font-weight: 800;
  margin: 0 0 12px 0;
  line-height: 1.2;
}
.hero-desc {
  color: #a8b2c1;
  font-size: 1rem;
  line-height: 1.8;
  max-width: 540px;
  margin-bottom: 28px;
}
.hero-buttons {
  display: flex;
  gap: 12px;
  flex-wrap: wrap;
}
.btn-primary {
  background: #e94560;
  color: white !important;
  padding: 12px 28px;
  border-radius: 10px;
  text-decoration: none !important;
  font-weight: 700;
  font-size: 14px;
  transition: all 0.3s;
  display: inline-block;
}
.btn-outline {
  background: transparent;
  color: white !important;
  padding: 12px 28px;
  border-radius: 10px;
  text-decoration: none !important;
  font-weight: 700;
  font-size: 14px;
  border: 2px solid rgba(255,255,255,0.4);
  display: inline-block;
}
.stats-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
  gap: 16px;
  padding-top: 32px;
  border-top: 1px solid rgba(255,255,255,0.1);
}
.stat-item {
  text-align: center;
}
.stat-number {
  font-size: 1.8rem;
  font-weight: 800;
  color: #e94560;
}
.stat-label {
  font-size: 12px;
  color: #a8b2c1;
  margin-top: 4px;
}
.info-cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
  margin-bottom: 40px;
}
.info-card {
  background: white;
  border-radius: 16px;
  padding: 28px 24px;
  border-left: 5px solid #e94560;
  box-shadow: 0 4px 20px rgba(0,0,0,0.06);
  transition: transform 0.2s;
}
.info-card:nth-child(2) { border-left-color: #302b63; }
.info-card:nth-child(3) { border-left-color: #e94560; }
.info-card:nth-child(4) { border-left-color: #302b63; }
.info-card-icon { font-size: 2rem; margin-bottom: 12px; }
.info-card-title { font-weight: 700; font-size: 15px; color: #1a1a2e; margin-bottom: 6px; }
.info-card-value { color: #555; font-size: 14px; line-height: 1.5; }
.section-title {
  font-size: 1.6rem;
  font-weight: 800;
  color: #1a1a2e;
  margin-bottom: 8px;
}
.section-subtitle {
  color: #777;
  margin-bottom: 28px;
  font-size: 15px;
}
.topics-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 16px;
  margin-bottom: 48px;
}
.topic-card {
  background: linear-gradient(135deg, #1a1a2e, #302b63);
  color: white;
  border-radius: 14px;
  padding: 24px;
  text-align: center;
}
.topic-icon { font-size: 2.2rem; margin-bottom: 12px; }
.topic-name { font-weight: 700; font-size: 15px; margin-bottom: 6px; }
.topic-desc { font-size: 13px; color: #a8b2c1; line-height: 1.5; }
</style>

<div class="hero-section">
  <div class="hero-top">
    <div>
      <div class="hero-badge">🎓 UET Faisalabad · BSCPE 2025</div>
      <h1 class="hero-name">Rana Muhammad<br>Saqlain</h1>
      <p class="hero-desc">
        Computer Engineering student documenting my semester journey — Python programming, Database Systems, and everything I learn under the guidance of <strong style="color:white;">Dr. Bilal Ahmad</strong> at UET Faisalabad.
      </p>
      <div class="hero-buttons">
        <a href="/categories/" class="btn-primary">📚 Read My Posts</a>
        <a href="/about/" class="btn-outline">👤 About Me</a>
        <a href="https://github.com/ranasaqlainsaqlain39-ops" class="btn-outline">🐙 GitHub</a>
      </div>
    </div>
  </div>
  <div class="stats-grid">
    <div class="stat-item">
      <div class="stat-number">10+</div>
      <div class="stat-label">Blog Posts</div>
    </div>
    <div class="stat-item">
      <div class="stat-number">2</div>
      <div class="stat-label">Courses Covered</div>
    </div>
    <div class="stat-item">
      <div class="stat-number">1st</div>
      <div class="stat-label">Year Engineering</div>
    </div>
    <div class="stat-item">
      <div class="stat-number">UET</div>
      <div class="stat-label">Faisalabad Campus</div>
    </div>
  </div>
</div>

<div class="info-cards">
  <div class="info-card">
    <div class="info-card-icon">🎓</div>
    <div class="info-card-title">Student Info</div>
    <div class="info-card-value">Roll No: 2025-BSCPE-146<br>Section B</div>
  </div>
  <div class="info-card">
    <div class="info-card-icon">🏛️</div>
    <div class="info-card-title">University</div>
    <div class="info-card-value">University of Engineering & Technology, Faisalabad</div>
  </div>
  <div class="info-card">
    <div class="info-card-icon">👨‍🏫</div>
    <div class="info-card-title">Professor</div>
    <div class="info-card-value">Dr. Bilal Ahmad<br>AI · ML · Deep Learning</div>
  </div>
  <div class="info-card">
    <div class="info-card-icon">📧</div>
    <div class="info-card-title">Contact</div>
    <div class="info-card-value">ranasaqlainsaqlain39<br>@email.com</div>
  </div>
</div>

<h2 class="section-title">What I Write About</h2>
<p class="section-subtitle">My posts cover everything I learn this semester — from Python basics to SQL databases.</p>

<div class="topics-grid">
  <div class="topic-card">
    <div class="topic-icon">🐍</div>
    <div class="topic-name">Python Programming</div>
    <div class="topic-desc">Variables, loops, functions, file handling and more from Programming Fundamentals</div>
  </div>
  <div class="topic-card">
    <div class="topic-icon">🗄️</div>
    <div class="topic-name">Database Systems</div>
    <div class="topic-desc">SQL queries, normalization, ER diagrams and real database design</div>
  </div>
  <div class="topic-card">
    <div class="topic-icon">🎯</div>
    <div class="topic-name">Student Life</div>
    <div class="topic-desc">Exams, struggles, lessons learned and UET engineering journey</div>
  </div>
  <div class="topic-card">
    <div class="topic-icon">🤖</div>
    <div class="topic-name">AI & ML Concepts</div>
    <div class="topic-desc">Introduction to Machine Learning as taught by Dr. Bilal Ahmad</div>
  </div>
</div>

---
