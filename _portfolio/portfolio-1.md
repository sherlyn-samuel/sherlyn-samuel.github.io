---
title: "Menta-rey"
excerpt: "A Flutter-based gamified educational app for children featuring Mathematical Quizzing and Indian Sign Language (ISL) learning with LLM (Gemini API) integration."
collection: portfolio

--- 

<style>
.proj { border-left: 3px solid #f0c4b8; padding: 0 0 2rem 1.25rem; margin-bottom: 0.5rem; }
.proj-meta { display: flex; align-items: center; gap: 8px; flex-wrap: wrap; margin-bottom: 0.3rem; }
.proj-num { font-size: 11px; color: #999; text-transform: uppercase; letter-spacing: 0.08em; }
.proj-title { font-size: 1.1rem; font-weight: 700; margin: 0 0 2px; }
.proj-subtitle { font-size: 13px; color: #666; margin: 0 0 0.7rem; }
.badge-gold { font-size: 11px; font-weight: 500; background: #fde9c4; color: #7a4800; padding: 2px 8px; border-radius: 3px; }
.badge-wip  { font-size: 11px; font-weight: 500; background: #e8f0fb; color: #3a5a99; padding: 2px 8px; border-radius: 3px; }
.proj-tags  { display: flex; gap: 5px; flex-wrap: wrap; margin-bottom: 0.7rem; }
.tag { font-size: 11px; padding: 1px 7px; border-radius: 3px; background: #f0eef8; color: #4a3f80; }
.proj-desc  { font-size: 14px; color: #444; line-height: 1.65; margin-bottom: 0.8rem; }
.arch-label { font-size: 11px; font-weight: 600; color: #aaa; text-transform: uppercase; letter-spacing: 0.07em; margin-bottom: 5px; }
.pub-block  { border-left: 2px solid #fde9c4; padding: 6px 12px; font-size: 13px; color: #555; line-height: 1.55; margin: 0.7rem 0; }
.proj-links { display: flex; gap: 8px; margin-top: 0.7rem; }
.proj-link  { font-size: 12px; padding: 3px 10px; border-radius: 4px; border: 1px solid #ddd; color: #555; text-decoration: none; }
.proj-link:hover { background: #f7f7f7; text-decoration: none; }
</style>

<div class="proj-card">
  <div class="proj-header">
    <div>
      <div class="proj-subtitle">Gamified 2D learning platform for children</div>
    </div>
    <span class="badge badge-gold">🏅 Best Paper &middot; ICESM-2026</span><br>
  </div>
  <div class="proj-tags">
    <span class="tag">Flutter / Flame</span>
    <span class="tag">Spring Boot</span>
    <span class="tag">Gemini API</span>
    <span class="tag">MySQL</span>
    <span class="tag">HCI</span>
    <span class="tag">EdTech</span>
  </div>
  <div class="proj-desc">
    An underwater pixel-art learning platform combining adaptive math quizzing (LLM-powered via Gemini API) with an Indian Sign Language alphabet game. Designed for children under 12, with offline-first architecture, JWT authentication, leaderboards, and a parent analytics dashboard.
  </div>
  <div class="arch-label">System architecture</div>
  <svg width="100%" viewBox="0 0 620 110" xmlns="http://www.w3.org/2000/svg" style="display:block;margin-bottom:0.5rem;">
    <defs>
      <marker id="a1" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse">
        <path d="M2 1L8 5L2 9" fill="none" stroke="#888" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
      </marker>
    </defs>
    <!-- Flutter / Flame -->
    <rect x="10" y="30" width="138" height="50" rx="8" fill="#e1f5ee" stroke="#0f6e56" stroke-width="0.5"/>
    <text x="79" y="52" text-anchor="middle" font-size="13" font-weight="600" fill="#085041" font-family="sans-serif">Flutter / Flame</text>
    <text x="79" y="68" text-anchor="middle" font-size="11" fill="#0f6e56" font-family="sans-serif">Frontend · Game engine</text>
    <!-- arrow -->
    <line x1="150" y1="55" x2="182" y2="55" stroke="#aaa" stroke-width="1" marker-end="url(#a1)"/>
    <text x="166" y="48" text-anchor="middle" font-size="10" fill="#999" font-family="sans-serif">REST</text>
    <!-- Spring Boot -->
    <rect x="184" y="30" width="148" height="50" rx="8" fill="#eeedfe" stroke="#534ab7" stroke-width="0.5"/>
    <text x="258" y="52" text-anchor="middle" font-size="13" font-weight="600" fill="#3c3489" font-family="sans-serif">Spring Boot</text>
    <text x="258" y="68" text-anchor="middle" font-size="11" fill="#534ab7" font-family="sans-serif">Auth · Business logic</text>
    <!-- arrows to right nodes -->
    <line x1="334" y1="46" x2="372" y2="30" stroke="#aaa" stroke-width="1" marker-end="url(#a1)"/>
    <line x1="334" y1="64" x2="372" y2="80" stroke="#aaa" stroke-width="1" marker-end="url(#a1)"/>
    <!-- MySQL -->
    <rect x="374" y="10" width="118" height="38" rx="8" fill="#faeeda" stroke="#854f0b" stroke-width="0.5"/>
    <text x="433" y="33" text-anchor="middle" font-size="13" font-weight="600" fill="#633806" font-family="sans-serif">MySQL</text>
    <!-- Gemini -->
    <rect x="374" y="62" width="118" height="38" rx="8" fill="#faece7" stroke="#993c1d" stroke-width="0.5"/>
    <text x="433" y="85" text-anchor="middle" font-size="13" font-weight="600" fill="#4a1b0c" font-family="sans-serif">Gemini API</text>
    <text x="433" y="107" text-anchor="middle" font-size="10" fill="#993c1d" font-family="sans-serif">Dynamic question gen.</text>
  </svg>
  <hr class="proj-divider"/>
  <div class="pub-block">
    <span class="pub-title">"Redesigning Digital Habits in Early Adolescents through Gamification"</span><br>
    Second International Conference on Engineering, Science and Management (ICESM-2026)<br>
    <strong>Best Paper Presentation Award, UG Category</strong>
  </div>
  <div class="proj-links">
    <a class="proj-link" href="https://github.com/sherlyn-samuel/menta-ray" target="_blank">↗ GitHub</a>
  </div>
</div>

--- 