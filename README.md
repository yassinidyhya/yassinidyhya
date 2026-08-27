
<style>
  @import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500;700&family=Inter:wght@400;500;600&display=swap');
  *{box-sizing:border-box;margin:0;padding:0}
  .wrap{font-family:'Inter',sans-serif;color:#e6edf3;max-width:680px;padding:0 0 2rem}
  .hero{padding:2rem 0 1.5rem;border-bottom:1px solid #21262d}
  .hero-top{display:flex;align-items:center;gap:1rem;margin-bottom:.75rem}
  .avatar{width:52px;height:52px;border-radius:50%;background:linear-gradient(135deg,#1f6feb,#3fb950);display:flex;align-items:center;justify-content:center;font-family:'JetBrains Mono',monospace;font-weight:700;font-size:1.1rem;color:#fff;flex-shrink:0;border:2px solid #30363d}
  .name-block h1{font-family:'JetBrains Mono',monospace;font-size:1.25rem;font-weight:700;color:#f0f6fc;letter-spacing:-0.02em}
  .name-block .handle{font-size:.8rem;color:#8b949e;font-family:'JetBrains Mono',monospace}
  .tagline{font-family:'JetBrains Mono',monospace;font-size:.85rem;color:#8b949e;margin-bottom:1.25rem;display:flex;align-items:center}
  .tagline span{color:#58a6ff}
  .cursor{display:inline-block;width:9px;height:1em;background:#3fb950;margin-left:2px;animation:blink 1s step-end infinite;vertical-align:text-bottom}
  @keyframes blink{0%,100%{opacity:1}50%{opacity:0}}
  .bio{font-size:.9rem;color:#c9d1d9;line-height:1.65}
  .section{padding:1.25rem 0;border-bottom:1px solid #21262d}
  .sec-label{font-family:'JetBrains Mono',monospace;font-size:.7rem;color:#3fb950;text-transform:uppercase;letter-spacing:.12em;margin-bottom:.85rem}
  .projects{display:flex;flex-direction:column;gap:.6rem}
  .proj{background:#0d1117;border:1px solid #21262d;border-radius:8px;padding:.75rem 1rem;display:flex;justify-content:space-between;align-items:flex-start;gap:1rem;text-decoration:none;transition:border-color .15s}
  .proj:hover{border-color:#30363d}
  .proj-name{font-family:'JetBrains Mono',monospace;font-size:.85rem;font-weight:700;color:#f0f6fc;margin-bottom:.2rem}
  .proj-desc{font-size:.78rem;color:#8b949e;line-height:1.5}
  .proj-right{flex-shrink:0}
  .badge{font-family:'JetBrains Mono',monospace;font-size:.65rem;padding:.15rem .45rem;border-radius:4px;white-space:nowrap}
  .badge-live{background:#1f2d1f;color:#56d364;border:1px solid #238636}
  .badge-wip{background:#2a1f00;color:#e3b341;border:1px solid #9e6a03}
  .badge-personal{background:#1a1f2e;color:#79c0ff;border:1px solid #1f6feb}
  .badge-bored{background:#2a1a1a;color:#f47067;border:1px solid #6e2020}
  .badge-paused{background:#1e1e1e;color:#6e7681;border:1px solid #30363d}
  .about-list{list-style:none;display:flex;flex-direction:column;gap:.35rem}
  .about-list li{font-size:.86rem;color:#c9d1d9;display:flex;align-items:baseline;gap:.5rem;line-height:1.5}
  .bullet{color:#1f6feb;font-size:.75rem;flex-shrink:0}
  .tech-grid{display:flex;flex-wrap:wrap;gap:.4rem}
  .tag{font-family:'JetBrains Mono',monospace;font-size:.72rem;background:#161b22;border:1px solid #30363d;color:#79c0ff;padding:.2rem .55rem;border-radius:4px}
  .tag.core{border-color:#1f6feb;color:#58a6ff}
  .tag.infra{border-color:#3fb950;color:#56d364}
  .tag.ai{border-color:#a371f7;color:#d2a8ff}
  .links-row{display:flex;gap:.75rem;flex-wrap:wrap;padding:1.25rem 0 0}
  .link-btn{display:flex;align-items:center;gap:.4rem;text-decoration:none;font-family:'JetBrains Mono',monospace;font-size:.75rem;color:#8b949e;border:1px solid #30363d;border-radius:6px;padding:.35rem .75rem;background:#0d1117}
  .dot{width:6px;height:6px;border-radius:50%;flex-shrink:0}
  .dot-web{background:#58a6ff}.dot-ig{background:#e1306c}
  .motto{font-family:'JetBrains Mono',monospace;font-size:.78rem;color:#484f58;margin-top:1.5rem;text-align:center;letter-spacing:.04em}
  .motto span{color:#3fb950}
</style>
<div class="wrap">
  <div class="hero">
    <div class="hero-top">
      <div class="avatar">YI</div>
      <div class="name-block">
        <h1>Yassin Idyhya</h1>
        <div class="handle">@yassinidyhya</div>
      </div>
    </div>
    <div class="tagline"><span>$ </span>&nbsp;I ship things. sometimes they even work<div class="cursor"></div></div>
    <p class="bio">I build web apps using AI as my main tool. Started with websites and e-commerce, now building real products. Some are done. Some are for friends. One I built because I was bored at 2am. All of it is real work.</p>
  </div>

  <div class="section">
    <div class="sec-label">// shipped</div>
    <div class="projects">
      <a href="https://taberat.idyhya.dev" class="proj">
        <div>
          <div class="proj-name">taberat</div>
          <div class="proj-desc">Invoice generator. 13 templates, 170+ currencies, 18 languages. No account, no BS, just a PDF.</div>
        </div>
        <div class="proj-right"><span class="badge badge-live">live</span></div>
      </a>
      <a href="https://qubecstream.idyhya.dev" class="proj">
        <div>
          <div class="proj-name">quebecstream</div>
          <div class="proj-desc">French-Canadian IPTV marketing site. Pricing, reseller program, 10-article blog, full SEO. Built it because a friend inspired me. Never launched the business. The site's clean though.</div>
        </div>
        <div class="proj-right"><span class="badge badge-personal">personal</span></div>
      </a>
      <a href="https://rijaltravaux.idyhya.dev" class="proj">
        <div>
          <div class="proj-name">rijal travaux</div>
          <div class="proj-desc">Website for a construction company in Laayoune. Built it randomly out of boredom. They didn't ask. It's live anyway.</div>
        </div>
        <div class="proj-right"><span class="badge badge-bored">bored</span></div>
      </a>
    </div>
  </div>

  <div class="section">
    <div class="sec-label">// cooking</div>
    <div class="projects">
      <a href="https://quoteflow.idyhya.dev" class="proj">
        <div>
          <div class="proj-name">quoteflow</div>
          <div class="proj-desc">AI-generated business quotes. Describe your service, get a professional quote ready to send.</div>
        </div>
        <div class="proj-right"><span class="badge badge-wip">in progress</span></div>
      </a>
      <a href="https://pharmsaf.idyhya.dev" class="proj">
        <div>
          <div class="proj-name">pharmsaf</div>
          <div class="proj-desc">Pharmacy management system for a friend in Essaouira. Stock, distributions, delivery slips. On hold for now.</div>
        </div>
        <div class="proj-right"><span class="badge badge-paused">paused</span></div>
      </a>
    </div>
  </div>

  <div class="section">
    <div class="sec-label">// about me</div>
    <ul class="about-list">
      <li><span class="bullet">▸</span> Use AI like a senior dev uses Stack Overflow — constantly, no shame</li>
      <li><span class="bullet">▸</span> Learning the backend stuff because I got tired of not knowing what's happening</li>
      <li><span class="bullet">▸</span> Once built a full website for a random company just because I was bored</li>
      <li><span class="bullet">▸</span> Once spent 3 hours on a bug. it was a missing semicolon. we don't talk about it</li>
    </ul>
  </div>

  <div class="section">
    <div class="sec-label">// tech I use</div>
    <div class="tech-grid">
      <span class="tag core">TypeScript</span>
      <span class="tag core">Next.js</span>
      <span class="tag core">React</span>
      <span class="tag core">Node.js</span>
      <span class="tag core">PostgreSQL</span>
      <span class="tag">Drizzle</span>
      <span class="tag">Better Auth</span>
      <span class="tag infra">Docker</span>
      <span class="tag infra">Supabase</span>
      <span class="tag infra">Coolify</span>
      <span class="tag ai">Claude</span>
      <span class="tag ai">Cursor</span>
      <span class="tag ai">v0</span>
    </div>
  </div>

  <div class="section">
    <div class="sec-label">// find me</div>
    <div class="links-row">
      <a href="https://idyhya.dev/" class="link-btn"><div class="dot dot-web"></div>idyhya.dev</a>
      <a href="https://instagram.com/yassin_idyhya" class="link-btn"><div class="dot dot-ig"></div>Instagram</a>
    </div>
  </div>

  <div class="motto"><span>Build it.</span> Break it. <span>Fix it.</span> Ship it.</div>
</div>
