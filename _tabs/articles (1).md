---
layout: page
title: Articles
icon: fas fa-newspaper
order: 1
---

<style>
  .section-header {
    margin-bottom: 32px;
  }
  .section-header h2 {
    font-size: 1.6rem;
    font-weight: 700;
    color: #ffffff;
    margin-bottom: 6px;
  }
  .section-header p {
    font-size: 0.95rem;
    color: #888888;
  }

  .cards-list {
    display: flex;
    flex-direction: column;
    gap: 16px;
    max-width: 860px;
  }

  .article-card {
    display: flex;
    background: #2a2a2a;
    border-radius: 12px;
    overflow: hidden;
    border: 1px solid #3a3a3a;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.5);
    transition: transform 0.22s ease, box-shadow 0.22s ease, border-color 0.22s ease;
  }
  .article-card:hover {
    transform: translateY(-3px);
    box-shadow: 0 8px 24px rgba(0, 0, 0, 0.6);
    border-color: #4a90e2;
  }

  .card-thumb {
    width: 195px;
    min-width: 195px;
    overflow: hidden;
    flex-shrink: 0;
  }
  .card-thumb img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    display: block;
    transition: transform 0.35s ease;
    filter: brightness(0.9);
  }
  .article-card:hover .card-thumb img {
    transform: scale(1.06);
    filter: brightness(1);
  }

  .card-body {
    padding: 18px 22px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    flex: 1;
  }

  .card-meta-top {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 10px;
  }
  .badge {
    font-size: 0.72rem;
    font-weight: 600;
    padding: 3px 11px;
    border-radius: 999px;
    background: #1a3a5c;
    color: #4a90e2;
    letter-spacing: 0.03em;
    border: 1px solid #2a5080;
  }
  .card-date {
    font-size: 0.78rem;
    color: #777777;
  }

  .card-title {
    font-size: 1rem;
    font-weight: 700;
    color: #eeeeee;
    margin-bottom: 8px;
    line-height: 1.4;
  }

  .card-excerpt {
    font-size: 0.855rem;
    color: #999999;
    line-height: 1.65;
    margin-bottom: 14px;
  }

  .card-meta-bottom {
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  .read-time {
    font-size: 0.78rem;
    color: #666666;
  }
  .btn-read {
    font-size: 0.8rem;
    font-weight: 600;
    padding: 6px 16px;
    border-radius: 8px;
    border: 1px solid #2a5080;
    background: #1a3a5c;
    color: #4a90e2;
    cursor: pointer;
    transition: background 0.18s, color 0.18s, border-color 0.18s;
    text-decoration: none;
  }
  .btn-read:hover {
    background: #4a90e2;
    color: #ffffff;
    border-color: #4a90e2;
    text-decoration: none;
  }

  @media (max-width: 600px) {
    .article-card { flex-direction: column; }
    .card-thumb { width: 100%; min-width: unset; height: 175px; }
  }
</style>

<div class="section-header">
  <h2>Latest Articles</h2>
  <p>Weekly notes from my lab tasks and computer engineering coursework.</p>
</div>

<div class="cards-list">

  <div class="article-card">
    <div class="card-thumb">
      <img src="https://images.unsplash.com/photo-1555066931-4365d14bab8c?w=400&q=80" alt="HTML Structure"/>
    </div>
    <div class="card-body">
      <div>
        <div class="card-meta-top">
          <span class="badge">HTML & CSS</span>
          <span class="card-date">18 Mar 2026</span>
        </div>
        <div class="card-title">Understanding HTML Document Structure</div>
        <div class="card-excerpt">A beginner breakdown of how HTML documents are structured — from doctype to semantic tags and why they matter for accessibility.</div>
      </div>
      <div class="card-meta-bottom">
        <span class="read-time">5 min read</span>
        <a href="#" class="btn-read">Read More</a>
      </div>
    </div>
  </div>

  <div class="article-card">
    <div class="card-thumb">
      <img src="https://images.unsplash.com/photo-1517180102446-f3ece451e9d8?w=400&q=80" alt="Flexbox"/>
    </div>
    <div class="card-body">
      <div>
        <div class="card-meta-top">
          <span class="badge">CSS Layout</span>
          <span class="card-date">24 Mar 2026</span>
        </div>
        <div class="card-title">Mastering Flexbox for Responsive Pages</div>
        <div class="card-excerpt">How I used Flexbox in my lab assignment to align cards and navigation bars without breaking the layout on mobile screens.</div>
      </div>
      <div class="card-meta-bottom">
        <span class="read-time">4 min read</span>
        <a href="#" class="btn-read">Read More</a>
      </div>
    </div>
  </div>

  <div class="article-card">
    <div class="card-thumb">
      <img src="https://images.unsplash.com/photo-1579468118864-1b9ea3c0db4a?w=400&q=80" alt="JavaScript"/>
    </div>
    <div class="card-body">
      <div>
        <div class="card-meta-top">
          <span class="badge">JavaScript</span>
          <span class="card-date">30 Mar 2026</span>
        </div>
        <div class="card-title">JavaScript Events & DOM Manipulation</div>
        <div class="card-excerpt">My notes from the weekly lab on handling click events, updating text dynamically, and toggling CSS classes with JavaScript.</div>
      </div>
      <div class="card-meta-bottom">
        <span class="read-time">6 min read</span>
        <a href="#" class="btn-read">Read More</a>
      </div>
    </div>
  </div>

  <div class="article-card">
    <div class="card-thumb">
      <img src="https://images.unsplash.com/photo-1593720213428-28a5b9e94613?w=400&q=80" alt="GitHub Pages"/>
    </div>
    <div class="card-body">
      <div>
        <div class="card-meta-top">
          <span class="badge">Deployment</span>
          <span class="card-date">03 Apr 2026</span>
        </div>
        <div class="card-title">Deploying My First Site on GitHub Pages</div>
        <div class="card-excerpt">Step-by-step notes on how I pushed my first project to GitHub and got it live on the internet using GitHub Pages for free.</div>
      </div>
      <div class="card-meta-bottom">
        <span class="read-time">5 min read</span>
        <a href="#" class="btn-read">Read More</a>
      </div>
    </div>
  </div>

</div>
