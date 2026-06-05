---
title: "Menta-rey"
excerpt: "A Flutter-based gamified educational app for children featuring Mathematical Quizzing and Indian Sign Language (ISL) learning with LLM (Gemini API) integration."
collection: portfolio
---

<style>
.proj-card { border: 0.5px solid #d0cfc8; border-radius: 12px; padding: 1.25rem 1.5rem; margin-bottom: 1.5rem; }
.proj-header { display: flex; align-items: flex-start; justify-content: space-between; gap: 1rem; margin-bottom: 0.75rem; }
.proj-number { font-size: 11px; font-weight: 500; color: #888; text-transform: uppercase; letter-spacing: 0.08em; margin-bottom: 3px; }
.proj-title { font-size: 17px; font-weight: 600; margin: 0 0 2px; }
.proj-subtitle { font-size: 13px; color: #666; margin: 0; }
.badge { display: inline-flex; align-items: center; gap: 4px; font-size: 11px; font-weight: 500; padding: 3px 9px; border-radius: 4px; white-space: nowrap; flex-shrink: 0; }
.badge-gold { background: #faeeda; color: #854f0b; }
.badge-wip { background: #f1f0ea; color: #666; border: 0.5px solid #ccc; }
.proj-tags { display: flex; gap: 6px; flex-wrap: wrap; margin-bottom: 0.85rem; }
.tag { font-size: 11px; padding: 2px 7px; border-radius: 4px; background: #f4f3ee; color: #555; border: 0.5px solid #ddd; }
.proj-desc { font-size: 14px; color: #444; line-height: 1.65; margin-bottom: 0.85rem; }
.arch-label { font-size: 11px; font-weight: 600; color: #999; text-transform: uppercase; letter-spacing: 0.07em; margin-bottom: 5px; }
.pub-block { background: #f7f6f1; border-radius: 6px; padding: 10px 14px; font-size: 13px; color: #555; line-height: 1.55; margin-top: 0.75rem; }
.pub-title { font-weight: 600; color: #222; }
.proj-links { display: flex; gap: 8px; margin-top: 0.85rem; }
.proj-link { font-size: 12px; padding: 4px 10px; border-radius: 6px; border: 0.5px solid #ccc; color: #555; text-decoration: none; display: inline-flex; align-items: center; gap: 4px; }
.proj-link:hover { background: #f4f3ee; text-decoration: none; }
.proj-divider { border: none; border-top: 0.5px solid #e0dfd8; margin: 0.85rem 0; }
</style>
<div class="proj-card">
  <div class="proj-header">
    <div>
      <div class="proj-number">Project 01 &mdash; Complete</div>
      <div class="proj-title">Menta-Ray</div>
      <div class="proj-subtitle">Gamified 2D learning platform for children</div>
    </div>
    <span class="badge badge-gold">🏅 Best Paper &middot; ICESM-2026</span>
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

<div class="proj-card">
  <div class="proj-header">
    <div>
      <div class="proj-number">Project 02 &mdash; Ongoing</div>
      <div class="proj-title">CGCLMA</div>
      <div class="proj-subtitle">Competitive Gaming for Children&rsquo;s Learning through Mathematical Application</div>
    </div>
    <span class="badge badge-wip">In progress</span>
  </div>
  <div class="proj-tags">
    <span class="tag">Flutter / Flame</span>
    <span class="tag">FastAPI</span>
    <span class="tag">ClickHouse</span>
    <span class="tag">Redis</span>
    <span class="tag">PyTorch / DKT</span>
    <span class="tag">Learning Analytics</span>
    <span class="tag">Game AI</span>
  </div>
  <div class="proj-desc">
    A multiplayer competitive math game for children with millisecond-level focus telemetry. Interaction data streams directly into ClickHouse (columnar analytics) via an async FastAPI gateway; compute-heavy tasks are dispatched through a Redis queue to isolated workers. A Deep Knowledge Tracing layer (PyTorch) is planned to model per-child mastery over knowledge components in real time.
  </div>
  <div class="arch-label">Backend pipeline</div>
  <svg width="100%" viewBox="0 0 620 180" xmlns="http://www.w3.org/2000/svg" style="display:block;margin-bottom:0.5rem;">
    <defs>
      <marker id="a2" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse">
        <path d="M2 1L8 5L2 9" fill="none" stroke="#888" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
      </marker>
    </defs>
    <!-- Flutter -->
    <rect x="10" y="65" width="110" height="50" rx="8" fill="#e1f5ee" stroke="#0f6e56" stroke-width="0.5"/>
    <text x="65" y="87" text-anchor="middle" font-size="13" font-weight="600" fill="#085041" font-family="sans-serif">Flutter</text>
    <text x="65" y="103" text-anchor="middle" font-size="11" fill="#0f6e56" font-family="sans-serif">Telemetry streams</text>
    <!-- arrow -->
    <line x1="122" y1="90" x2="150" y2="90" stroke="#aaa" stroke-width="1" marker-end="url(#a2)"/>
    <text x="136" y="82" text-anchor="middle" font-size="10" fill="#999" font-family="sans-serif">HTTP</text>
    <!-- FastAPI -->
    <rect x="152" y="55" width="132" height="70" rx="8" fill="#eeedfe" stroke="#534ab7" stroke-width="0.5"/>
    <text x="218" y="82" text-anchor="middle" font-size="13" font-weight="600" fill="#3c3489" font-family="sans-serif">FastAPI</text>
    <text x="218" y="98" text-anchor="middle" font-size="11" fill="#534ab7" font-family="sans-serif">Gateway · Auth</text>
    <text x="218" y="113" text-anchor="middle" font-size="11" fill="#534ab7" font-family="sans-serif">Route + enqueue</text>
    <!-- arrows -->
    <line x1="286" y1="72" x2="326" y2="45" stroke="#aaa" stroke-width="1" marker-end="url(#a2)"/>
    <text x="314" y="50" text-anchor="start" font-size="10" fill="#999" font-family="sans-serif">writes</text>
    <line x1="286" y1="108" x2="326" y2="135" stroke="#aaa" stroke-width="1" marker-end="url(#a2)"/>
    <text x="314" y="132" text-anchor="start" font-size="10" fill="#999" font-family="sans-serif">enqueue</text>
    <!-- ClickHouse -->
    <rect x="328" y="14" width="130" height="50" rx="8" fill="#faeeda" stroke="#854f0b" stroke-width="0.5"/>
    <text x="393" y="36" text-anchor="middle" font-size="13" font-weight="600" fill="#633806" font-family="sans-serif">ClickHouse</text>
    <text x="393" y="52" text-anchor="middle" font-size="11" fill="#854f0b" font-family="sans-serif">Columnar analytics</text>
    <!-- Redis -->
    <rect x="328" y="116" width="130" height="50" rx="8" fill="#faece7" stroke="#993c1d" stroke-width="0.5"/>
    <text x="393" y="138" text-anchor="middle" font-size="13" font-weight="600" fill="#4a1b0c" font-family="sans-serif">Redis queue</text>
    <text x="393" y="154" text-anchor="middle" font-size="11" fill="#993c1d" font-family="sans-serif">Task broker</text>
    <!-- arrow to worker -->
    <line x1="460" y1="141" x2="490" y2="141" stroke="#aaa" stroke-width="1" stroke-dasharray="3 2" marker-end="url(#a2)"/>
    <!-- PyTorch Worker (planned) -->
    <rect x="492" y="116" width="118" height="50" rx="8" fill="#f1f0ea" stroke="#aaa" stroke-width="0.5" stroke-dasharray="4 3"/>
    <text x="551" y="138" text-anchor="middle" font-size="13" font-weight="600" fill="#555" font-family="sans-serif">PyTorch</text>
    <text x="551" y="154" text-anchor="middle" font-size="11" fill="#888" font-family="sans-serif">DKT · planned</text>
  </svg>
  <div class="proj-links">
    <a class="proj-link" href="https://github.com/sherlyn-samuel/CLAM" target="_blank">↗ GitHub</a>
  </div>
</div> 
