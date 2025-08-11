---
layout: default
title: Portfolio
---

<div class="container">
  <header>
    <h1>{{ site.title }}</h1>
    <p>{{ site.description }}</p>
  </header>

  <section id="hero">
    <h2>Creative technologist & storyteller</h2>
    <p>Focused on AR prototyping, documentary filmmaking, and visual storytelling. B.S. Integrated Design & Media at NYU Tandon.</p>
    <p>
      <a href="#projects">See Projects</a> •
      <a href="#contact">Contact</a>
    </p>
  </section>

  <section id="projects">
    <h2>Major Projects</h2>
    <div class="grid">
      <div class="card">
        <h3>Medical AR Prototype (2024)</h3>
        <p>AR tool to improve hospital patient intake. Built with Meta Spark AR & Figma; iterated with user testing.</p>
        <p><a href="/projects/ar-prototype.html">Case Study</a></p>
      </div>
      <div class="card">
        <h3>Thalidomide Documentary (2025)</h3>
        <p>1st Place Regional, 1st Place State, Top 20 National Finalist — National History Day.</p>
        <p><a href="https://youtube.com" target="_blank" rel="noopener">Watch</a></p>
      </div>
      <div class="card">
        <h3>Fallout Documentary (2024)</h3>
        <p>1st Place Regional, 2nd Place State, Top 20 National Finalist — National History Day.</p>
        <p><a href="https://youtube.com" target="_blank" rel="noopener">Watch</a></p>
      </div>
      <div class="card">
        <h3>Honduras Mission Portfolios (2023 & 2024)</h3>
        <p>10+ videos documenting community outreach, education programs, and cultural exchange.</p>
        <p><a href="https://youtube.com" target="_blank" rel="noopener">Playlist</a></p>
      </div>
    </div>
  </section>

  <section id="reel">
    <h2>Reel</h2>
    <div class="video-embed">
      <!-- Replace VIDEO_ID below -->
      <iframe src="https://www.youtube.com/embed/VIDEO_ID" title="Reel" frameborder="0" allowfullscreen></iframe>
    </div>
  </section>

  <section id="about">
    <h2>About</h2>
    <p>Filmmaker and photographer recognized in national and regional competitions. Co‑captain of varsity tennis; president of Speed Cubing Club. Fluent in English and Korean.</p>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <ul>
      <li>Email: <a href="mailto:email@email.com">email@email.com</a></li>
      <li>Instagram: <a href="https://instagram.com/davidnfilms" target="_blank" rel="noopener">@davidnfilms</a></li>
      <li>LinkedIn: <a href="https://linkedin.com/in/daviddwnoh" target="_blank" rel="noopener">linkedin.com/in/daviddwnoh</a></li>
    </ul>
  </section>

  <footer>
    <small>© {{ "now" | date: "%Y" }} {{ site.title }}</small>
  </footer>
</div>
