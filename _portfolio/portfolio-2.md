---
title: "CLAM"
excerpt: "CGCLMA - Competitive Gaming for Children's Learning through Mathematical Application"
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

