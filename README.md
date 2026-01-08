<style>
  :root {
    --bg: #ffffff;
    --text: #0f172a;
    --muted: #475569;
    --line: #e5e7eb;
    --accent: #2563eb;
  }

  body {
    margin: 0;
    padding: 0;
  }

  .container {
    max-width: 980px;
    margin: 0 auto;
    padding: 48px 32px;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI",
                 Inter, Roboto, Helvetica, Arial, sans-serif;
    color: var(--text);
    background: var(--bg);
  }

  h1 {
    font-size: 42px;
    font-weight: 700;
    letter-spacing: -0.02em;
    margin-bottom: 8px;
  }

  h2 {
    font-size: 22px;
    font-weight: 600;
    margin: 0 0 16px 0;
  }

  h3 {
    font-size: 16px;
    font-weight: 600;
    margin-bottom: 8px;
  }

  p {
    font-size: 15px;
    line-height: 1.7;
    color: var(--muted);
    margin: 0 0 16px 0;
  }

  .subtitle {
    font-size: 18px;
    color: var(--muted);
    margin-bottom: 40px;
  }

  .divider {
    border-top: 1px solid var(--line);
    margin: 48px 0;
  }

  .grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 40px;
  }

  ul {
    padding-left: 18px;
    margin: 0;
  }

  li {
    font-size: 14px;
    line-height: 1.7;
    color: var(--muted);
    margin-bottom: 8px;
  }

  .section-title {
    font-size: 13px;
    font-weight: 600;
    text-transform: uppercase;
    letter-spacing: 0.08em;
    color: var(--accent);
    margin-bottom: 12px;
  }

  .tag-row {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
  }

  .tag {
    font-size: 13px;
    padding: 6px 10px;
    border: 1px solid var(--line);
    border-radius: 6px;
    color: var(--muted);
  }

  @media (max-width: 760px) {
    .grid {
      grid-template-columns: 1fr;
    }
  }
</style>

<div class="container">

  <!-- HEADER -->
  <h1>Unity Game Developer</h1>
  <div class="subtitle">
    Interactive Systems Engineer · Gameplay · Architecture · Performance
  </div>

  <p>
    I build scalable, performance-driven game systems in Unity, focusing on
    clean architecture, long-term maintainability, and production-ready design.
    My work spans the full development lifecycle — from early prototypes to
    shipped gameplay systems.
  </p>

  <div class="divider"></div>

  <!-- ABOUT -->
  <div class="section-title">About</div>
  <p>
    With 5+ years of professional Unity development experience, I approach game
    development as an engineering discipline. I focus on structured gameplay
    systems, clear separation of responsibilities, and architectures that scale
    with growing production demands.
  </p>

  <div class="divider"></div>

  <!-- EXPERTISE -->
  <div class="section-title">Core Expertise</div>
  <div class="grid">
    <ul>
      <li>Gameplay systems & state-driven architecture</li>
      <li>Player, combat, AI, and interaction systems</li>
      <li>Performance-focused real-time programming</li>
      <li>Modular and reusable Unity frameworks</li>
    </ul>
    <ul>
      <li>Production-grade Unity project structure</li>
      <li>Clean, maintainable C# codebases</li>
      <li>Mobile & PC optimization strategies</li>
      <li>Scalable system design for teams</li>
    </ul>
  </div>

  <div class="divider"></div>

  <!-- TECH STACK -->
  <div class="section-title">Technology Stack</div>
  <div class="tag-row">
    <span class="tag">Unity 3D</span>
    <span class="tag">C#</span>
    <span class="tag">Gameplay Architecture</span>
    <span class="tag">State Machines</span>
    <span class="tag">Scriptable Objects</span>
    <span class="tag">Animation Systems</span>
    <span class="tag">Save & Persistence</span>
    <span class="tag">Performance Profiling</span>
    <span class="tag">Git Workflows</span>
  </div>

  <div class="divider"></div>

  <!-- SYSTEMS -->
  <div class="section-title">Systems & Architecture</div>
  <p>
    Strong focus on engineering-level systems rather than isolated features.
    I design gameplay frameworks that are modular, extendable, and easy for
    teams to work with under production pressure.
  </p>

  <ul>
    <li>Reusable combat and ability systems</li>
    <li>Weapon, character, and enemy architectures</li>
    <li>Data-driven gameplay logic</li>
    <li>Clear separation of logic, data, and presentation</li>
  </ul>

  <div class="divider"></div>

  <!-- EXPERIENCE -->
  <div class="section-title">Game Genres & Experience</div>
  <p>
    Experience across a wide range of game types, from fast-iteration mobile
    titles to system-heavy core gameplay projects.
  </p>

  <div class="tag-row">
    <span class="tag">Action</span>
    <span class="tag">Fighting</span>
    <span class="tag">Racing</span>
    <span class="tag">Hyper-Casual</span>
    <span class="tag">RPG Systems</span>
    <span class="tag">Single Player</span>
    <span class="tag">Multiplayer Foundations</span>
  </div>

  <div class="divider"></div>

  <!-- WORKFLOW -->
  <div class="section-title">Workflow & Collaboration</div>
  <ul>
    <li>Production-first development mindset</li>
    <li>Clear communication with designers and artists</li>
    <li>Feature-based Git workflows</li>
    <li>Clean handoff and documentation practices</li>
  </ul>

  <div class="divider"></div>

  <!-- SERVICES -->
  <div class="section-title">Professional Services</div>
  <p>
    Available for freelance and contract-based Unity development, including
    gameplay programming, system architecture, performance optimization, and
    technical consultation.
  </p>

</div>
