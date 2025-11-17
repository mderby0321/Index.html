<div class="action-network-widget" data-campaign-id="XXXX" data-form-id="XXXX"></div>
<script src="https://actionnetwork.org/widgets/v3/form/derby-for-iowa"></script>
<script src="https://actionnetwork.org/widgets/v3/petition/your-form-slug"></script>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Marcques Derby for Iowa | House District 99</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="description" content="Official campaign page for Marcques Derby for Iowa House District 99." />
  <style>
    :root {
      --blue: #1d4ed8;
      --blue-dark: #1e3a8a;
      --gold: #facc15;
      --bg: #020617;
      --bg-alt: #0b1120;
      --text: #f9fafb;
      --muted: #9ca3af;
      --card: #020617;
      --radius-lg: 1.5rem;
      --radius-md: 0.9rem;
      --shadow: 0 18px 45px rgba(15, 23, 42, 0.8);
      --transition: 0.2s ease-out;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      background: radial-gradient(circle at top, #1f2937 0, #020617 40%, #000 100%);
      color: var(--text);
      line-height: 1.6;
      scroll-behavior: smooth;
    }

    a {
      color: inherit;
      text-decoration: none;
    }

    img {
      max-width: 100%;
      display: block;
    }

    .page {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
    }

    .container {
      width: 100%;
      max-width: 1120px;
      margin: 0 auto;
      padding: 0 1.25rem;
    }

    /* Header / Nav */

    header {
      position: sticky;
      top: 0;
      z-index: 40;
      backdrop-filter: blur(18px);
      background: linear-gradient(to bottom, rgba(15, 23, 42, 0.95), rgba(15, 23, 42, 0.75), transparent);
      border-bottom: 1px solid rgba(148, 163, 184, 0.25);
    }

    .nav {
      height: 4.25rem;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 1rem;
    }

    .nav-left {
      display: flex;
      align-items: center;
      gap: 0.75rem;
    }

    .brand-mark {
      height: 2.5rem;
      width: 2.5rem;
      border-radius: 999px;
      background: radial-gradient(circle at 30% 15%, #bfdbfe, #1d4ed8 45%, #020617 80%);
      display: flex;
      align-items: center;
      justify-content: center;
      font-weight: 800;
      font-size: 1.2rem;
      box-shadow: 0 0 0 1px rgba(191, 219, 254, 0.9),
                  0 12px 30px rgba(15, 23, 42, 0.9);
    }

    .brand-text {
      display: flex;
      flex-direction: column;
    }

    .brand-name {
      font-weight: 700;
      letter-spacing: 0.06em;
      font-size: 0.95rem;
      text-transform: uppercase;
    }

    .brand-tagline {
      font-size: 0.75rem;
      color: var(--muted);
    }

    .nav-links {
      display: flex;
      align-items: center;
      gap: 1.2rem;
      font-size: 0.9rem;
    }

    .nav-links a {
      position: relative;
      padding: 0.15rem 0;
      color: var(--muted);
      transition: color var(--transition);
    }

    .nav-links a::after {
      content: "";
      position: absolute;
      left: 0;
      bottom: -0.2rem;
      width: 0;
      height: 2px;
      border-radius: 999px;
      background: linear-gradient(90deg, var(--gold), var(--blue));
      transition: width var(--transition);
    }

    .nav-links a:hover {
      color: var(--text);
    }

    .nav-links a:hover::after {
      width: 100%;
    }

    .nav-cta {
      padding: 0.5rem 1rem;
      border-radius: 999px;
      background: linear-gradient(135deg, var(--gold), var(--blue));
      border: 1px solid rgba(254, 249, 195, 0.7);
      font-size: 0.8rem;
      font-weight: 700;
      text-transform: uppercase;
      letter-spacing: 0.09em;
      box-shadow: 0 16px 40px rgba(15, 23, 42, 0.9);
      display: inline-flex;
      align-items: center;
      gap: 0.3rem;
      cursor: pointer;
      transition: transform var(--transition), box-shadow var(--transition), opacity var(--transition);
    }

    .nav-cta span {
      font-size: 1.1rem;
    }

    .nav-cta:hover {
      transform: translateY(-1px);
      box-shadow: 0 22px 55px rgba(15, 23, 42, 0.98);
      opacity: 0.96;
    }

    .nav-cta:active {
      transform: translateY(0);
      box-shadow: 0 10px 25px rgba(15, 23, 42, 0.95);
    }

    .nav-toggle {
      display: none;
      font-size: 1.6rem;
      cursor: pointer;
      color: var(--muted);
    }

    /* Hero */

    .hero {
      padding: 4rem 0 3.5rem;
    }

    .hero-inner {
      display: grid;
      grid-template-columns: minmax(0, 1.4fr) minmax(0, 1.1fr);
      gap: 2.7rem;
      align-items: center;
    }

    .hero-eyebrow {
      display: inline-flex;
      align-items: center;
      gap: 0.4rem;
      padding: 0.2rem 0.7rem 0.2rem 0.45rem;
      border-radius: 999px;
      background: rgba(15, 23, 42, 0.92);
      border: 1px solid rgba(148, 163, 184, 0.7);
      color: var(--muted);
      font-size: 0.78rem;
      margin-bottom: 1.1rem;
    }

    .hero-eyebrow-dot {
      width: 0.6rem;
      height: 0.6rem;
      border-radius: 999px;
      background: radial-gradient(circle, #4ade80, #16a34a);
      box-shadow: 0 0 0 4px rgba(22, 163, 74, 0.25);
    }

    .hero-title {
      font-size: clamp(2.3rem, 4.1vw, 3.2rem);
      line-height: 1.1;
      letter-spacing: 0.01em;
      margin-bottom: 0.75rem;
      text-transform: uppercase;
    }

    .hero-title span {
      display: block;
      background: linear-gradient(120deg, var(--gold), #f97316, var(--gold));
      -webkit-background-clip: text;
      color: transparent;
    }

    .hero-subtitle {
      color: var(--muted);
      max-width: 35rem;
      font-size: 0.98rem;
      margin-bottom: 1.5rem;
    }

    .hero-subtitle strong {
      color: #e5e7eb;
      font-weight: 600;
    }

    .hero-cta-row {
      display: flex;
      flex-wrap: wrap;
      gap: 0.8rem;
      align-items: center;
      margin-bottom: 1.2rem;
    }

    .btn {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: 0.4rem;
      border-radius: 999px;
      padding: 0.7rem 1.4rem;
      border: 1px solid transparent;
      font-size: 0.88rem;
      font-weight: 700;
      cursor: pointer;
      text-transform: uppercase;
      letter-spacing: 0.08em;
      transition: transform var(--transition), box-shadow var(--transition), background var(--transition), color var(--transition), border-color var(--transition), opacity var(--transition);
    }

    .btn-primary {
      background: linear-gradient(135deg, var(--blue), var(--blue-dark));
      border-color: rgba(191, 219, 254, 0.9);
      box-shadow: 0 18px 45px rgba(15, 23, 42, 0.9);
    }

    .btn-primary:hover {
      transform: translateY(-1px);
      box-shadow: 0 24px 55px rgba(15, 23, 42, 1);
      opacity: 0.96;
    }

    .btn-outline {
      background: rgba(15, 23, 42, 0.96);
      border-color: rgba(148, 163, 184, 0.95);
      color: var(--muted);
    }

    .btn-outline:hover {
      color: var(--text);
      border-color: rgba(191, 219, 254, 0.95);
      background: rgba(15, 23, 42, 1);
      transform: translateY(-1px);
      box-shadow: 0 18px 50px rgba(15, 23, 42, 0.98);
    }

    .hero-meta {
      font-size: 0.82rem;
      color: var(--muted);
    }

    .hero-meta strong {
      color: #e5e7eb;
    }

    /* Hero card */

    .hero-card {
      border-radius: var(--radius-lg);
      background: radial-gradient(circle at top, rgba(37, 99, 235, 0.8), #020617 70%);
      border: 1px solid rgba(191, 219, 254, 0.7);
      padding: 1.3rem 1.25rem;
      box-shadow: var(--shadow);
      position: relative;
      overflow: hidden;
      isolation: isolate;
    }

    .hero-card::before {
      content: "";
      position: absolute;
      inset: -40%;
      background:
        radial-gradient(circle at 0% 0%, rgba(250, 204, 21, 0.34) 0, transparent 45%),
        radial-gradient(circle at 100% 0%, rgba(129, 140, 248, 0.34) 0, transparent 40%);
      opacity: 0.9;
      z-index: -1;
    }

    .hero-card-header {
      display: flex;
      justify-content: space-between;
      gap: 0.75rem;
      align-items: center;
      margin-bottom: 0.85rem;
      font-size: 0.86rem;
      text-transform: uppercase;
      letter-spacing: 0.12em;
    }

    .hero-card-pill {
      padding: 0.25rem 0.75rem;
      border-radius: 999px;
      border: 1px solid rgba(219, 234, 254, 0.9);
      background: rgba(15, 23, 42, 0.9);
      font-size: 0.72rem;
    }

    .hero-card-body {
      border-radius: var(--radius-md);
      background: rgba(15, 23, 42, 0.96);
      border: 1px solid rgba(191, 219, 254, 0.8);
      padding: 0.95rem 1.05rem;
      font-size: 0.86rem;
      margin-bottom: 0.85rem;
    }

    .hero-card-body p + p {
      margin-top: 0.6rem;
    }

    .hero-card-list {
      margin-top: 0.7rem;
      display: grid;
      grid-template-columns: repeat(2, minmax(0, 1fr));
      gap: 0.7rem 1rem;
      font-size: 0.78rem;
    }

    .hero-card-label {
      text-transform: uppercase;
      letter-spacing: 0.14em;
      color: #cbd5f5;
      font-size: 0.7rem;
    }

    .hero-card-value {
      font-weight: 600;
      font-size: 0.9rem;
    }

    .hero-card-footer {
      font-size: 0.78rem;
      color: #e5e7eb;
    }

    /* Sections */

    section {
      padding: 3.5rem 0 3rem;
    }

    .section-heading {
      display: flex;
      justify-content: space-between;
      align-items: baseline;
      gap: 1rem;
      margin-bottom: 1.9rem;
    }

    .section-title {
      font-size: 1.5rem;
      text-transform: uppercase;
      letter-spacing: 0.12em;
    }

    .section-title span {
      color: var(--gold);
    }

    .section-subtitle {
      font-size: 0.9rem;
      max-width: 26rem;
      color: var(--muted);
    }

    /* About */

    .about-grid {
      display: grid;
      grid-template-columns: minmax(0, 1.5fr) minmax(0, 1.1fr);
      gap: 2.25rem;
      align-items: flex-start;
    }

    .about-text {
      font-size: 0.95rem;
      color: #e5e7eb;
    }

    .about-text p + p {
      margin-top: 0.9rem;
    }

    .about-highlight {
      margin-top: 1.1rem;
      padding: 0.8rem 1rem;
      border-radius: var(--radius-md);
      background: rgba(15, 23, 42, 0.96);
      border: 1px solid rgba(148, 163, 184, 0.75);
      font-size: 0.88rem;
      color: var(--muted);
    }

    .about-highlight strong {
      color: var(--gold);
    }

    .about-cards {
      display: grid;
      grid-template-columns: repeat(2, minmax(0, 1fr));
      gap: 0.9rem;
    }

    .stat-card {
      border-radius: var(--radius-md);
      background: rgba(15, 23, 42, 0.96);
      border: 1px solid rgba(148, 163, 184, 0.8);
      padding: 0.95rem;
      font-size: 0.86rem;
      box-shadow: 0 12px 30px rgba(15, 23, 42, 0.9);
    }

    .stat-label {
      color: var(--muted);
      margin-bottom: 0.2rem;
      text-transform: uppercase;
      letter-spacing: 0.12em;
      font-size: 0.72rem;
    }

    .stat-value {
      font-size: 1rem;
      font-weight: 600;
    }

    /* Priorities */

    .cards-grid {
      display: grid;
      grid-template-columns: repeat(3, minmax(0, 1fr));
      gap: 1.2rem;
    }

    .card {
      border-radius: var(--radius-md);
      background: radial-gradient(circle at top, rgba(37, 99, 235, 0.6), #020617 70%);
      padding: 1.15rem 1.1rem;
      border: 1px solid rgba(191, 219, 254, 0.75);
      box-shadow: var(--shadow);
      display: flex;
      flex-direction: column;
      gap: 0.35rem;
      font-size: 0.88rem;
    }

    .card-kicker {
      text-transform: uppercase;
      letter-spacing: 0.12em;
      font-size: 0.74rem;
      color: var(--gold);
    }

    .card-title {
      font-weight: 600;
      font-size: 1rem;
    }

    .card-body {
      margin-top: 0.3rem;
      color: #e5e7eb;
      font-size: 0.86rem;
      flex: 1;
    }

    .card-body ul {
      padding-left: 1.1rem;
      margin-top: 0.4rem;
    }

    .card-body li + li {
      margin-top: 0.25rem;
    }

    .card-footer {
      margin-top: 0.9rem;
      font-size: 0.75rem;
      color: var(--muted);
    }

    /* Action / Contact */

    .action-grid {
      display: grid;
      grid-template-columns: minmax(0, 1.15fr) minmax(0, 1.15fr);
      gap: 2rem;
      align-items: flex-start;
    }

    .action-card {
      border-radius: var(--radius-lg);
      background: radial-gradient(circle at top, rgba(37, 99, 235, 0.7), rgba(15, 23, 42, 0.98));
      border: 1px solid rgba(191, 219, 254, 0.9);
      padding: 1.25rem 1.2rem;
      box-shadow: var(--shadow);
      font-size: 0.9rem;
      color: #e5e7eb;
    }

    .action-card h3 {
      font-size: 1rem;
      text-transform: uppercase;
      letter-spacing: 0.12em;
      margin-bottom: 0.4rem;
    }

    .action-card p + p {
      margin-top: 0.7rem;
    }

    .action-steps {
      margin-top: 0.7rem;
      padding-left: 1.1rem;
      font-size: 0.86rem;
    }

    .action-steps li + li {
      margin-top: 0.25rem;
    }

    form {
      border-radius: var(--radius-lg);
      background: rgba(15, 23, 42, 0.98);
      border: 1px solid rgba(148, 163, 184, 0.9);
      padding: 1.25rem 1.2rem;
      box-shadow: var(--shadow);
      font-size: 0.9rem;
    }

    .form-grid {
      display: grid;
      grid-template-columns: repeat(2, minmax(0, 1fr));
      gap: 0.9rem 0.9rem;
    }

    .form-group {
      display: flex;
      flex-direction: column;
      gap: 0.25rem;
      font-size: 0.86rem;
    }

    .form-group label {
      color: #e5e7eb;
      font-size: 0.8rem;
      letter-spacing: 0.06em;
      text-transform: uppercase;
    }

    input, textarea {
      font: inherit;
      background: rgba(15, 23, 42, 0.96);
      border-radius: 0.6rem;
      border: 1px solid rgba(148, 163, 184, 0.9);
      padding: 0.55rem 0.7rem;
      color: var(--text);
      outline: none;
      transition: border-color var(--transition), box-shadow var(--transition), background var(--transition);
    }

    input::placeholder,
    textarea::placeholder {
      color: rgba(148, 163, 184, 0.8);
    }

    input:focus,
    textarea:focus {
      border-color: var(--gold);
      box-shadow: 0 0 0 1px rgba(250, 204, 21, 0.7);
      background: #020617;
    }

    textarea {
      min-height: 110px;
      resize: vertical;
    }

    .form-full {
      grid-column: 1 / -1;
    }

    .form-footer {
      margin-top: 1rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 0.8rem;
      flex-wrap: wrap;
      font-size: 0.8rem;
      color: var(--muted);
    }

    .required-note {
      font-size: 0.75rem;
    }

    /* Footer */

    footer {
      border-top: 1px solid rgba(148, 163, 184, 0.4);
      padding: 1.6rem 0 1.8rem;
      background: #020617;
      margin-top: auto;
      font-size: 0.78rem;
      color: var(--muted);
    }

    .footer-inner {
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 1rem;
      flex-wrap: wrap;
    }

    .footer-paid {
      text-transform: uppercase;
      letter-spacing: 0.12em;
      font-size: 0.75rem;
      color: #e5e7eb;
    }

    .footer-links {
      display: flex;
      gap: 1rem;
      flex-wrap: wrap;
    }

    .footer-links a {
      text-decoration: underline;
      text-decoration-style: dotted;
    }

    /* Responsive */

    @media (max-width: 900px) {
      .hero-inner,
      .about-grid,
      .cards-grid,
      .action-grid {
        grid-template-columns: minmax(0, 1fr);
      }

      .hero {
        padding-top: 3.2rem;
      }

      .hero-card {
        order: -1;
      }

      .about-cards {
        grid-template-columns: minmax(0, 1fr);
      }
    }

    @media (max-width: 768px) {
      .nav-links {
        position: absolute;
        inset-inline: 1.25rem;
        top: 4.1rem;
        background: rgba(15, 23, 42, 0.98);
        border-radius: 0.9rem;
        border: 1px solid rgba(148, 163, 184, 0.75);
        padding: 0.75rem 0.9rem;
        flex-direction: column;
        align-items: flex-start;
        gap: 0.65rem;
        font-size: 0.9rem;
        box-shadow: var(--shadow);
        max-height: 0;
        overflow: hidden;
        opacity: 0;
        pointer-events: none;
        transform: translateY(-6px);
        transition: max-height 0.22s ease, opacity 0.22s ease, transform 0.22s ease;
      }

      .nav-links.open {
        max-height: 280px;
        opacity: 1;
        pointer-events: auto;
        transform: translateY(0);
      }

      .nav-cta {
        display: none;
      }

      .nav-toggle {
        display: block;
      }
    }

    @media (max-width: 520px) {
      .hero-title {
        font-size: 2rem;
      }

      .section-heading {
        flex-direction: column;
        align-items: flex-start;
      }

      .form-grid {
        grid-template-columns: minmax(0, 1fr);
      }
    }
  </style>
</head>
<body>
<div class="page">
  <!-- Header -->
  <header>
    <div class="container">
      <nav class="nav">
        <div class="nav-left">
          <div class="brand-mark">MD</div>
          <div class="brand-text">
            <div class="brand-name">Marcques Derby</div>
            <div class="brand-tagline">For Iowa House District 99</div>
          </div>
        </div>

        <div class="nav-links" id="navLinks">
          <a href="#about">Meet Marcques</a>
          <a href="#priorities">Priorities</a>
          <a href="#action">Get Involved</a>
          <a href="#contact">Contact</a>
        </div>

        <button class="nav-cta" onclick="scrollToId('action')">
          <span>★</span> Donate / Volunteer
        </button>

        <button class="nav-toggle" id="navToggle" aria-label="Toggle navigation">
          ☰
        </button>
      </nav>
    </div>
  </header>

  <!-- Main -->
  <main>
    <!-- Hero -->
    <section class="hero" id="top">
      <div class="container hero-inner">
        <div>
          <div class="hero-eyebrow">
            <span class="hero-eyebrow-dot"></span>
            Husband. Father. UAW Member. Army Veteran.
          </div>
          <h1 class="hero-title">
            <span>Marcques Derby</span>
            For Iowa House District 99
          </h1>
          <p class="hero-subtitle">
            I’m a Burlington kid who grew up in this community, left school my senior year to enlist in the Army at 19,
            worked my way to Sergeant, and came home to raise a family and work the factory floor.
            I know what it’s like to worry about the mortgage, drive an older car with high miles, and still show up
            every day to do the job. I’m running because working people like us deserve a voice in Des Moines.
          </p>

          <div class="hero-cta-row">
            <button class="btn btn-primary" onclick="scrollToId('action')">
              Get Involved
            </button>
            <button class="btn btn-outline" onclick="scrollToId('priorities')">
              View Priorities
            </button>
          </div>

          <div class="hero-meta">
            <strong>Built on service.</strong> 14-year UAW member, Bargaining Chairman representing more than 200 workers,
            and a 100% disabled Army veteran raising three kids right here in Southeast Iowa.
          </div>
        </div>

        <aside class="hero-card" aria-label="Quick facts">
          <div class="hero-card-header">
            <span>Meet Your Neighbor</span>
            <span class="hero-card-pill">Derby for Iowa</span>
          </div>
          <div class="hero-card-body">
            <p>
              This campaign is about the people who make Iowa work — the men and women who punch a clock, bust their knuckles,
              raise families, and keep this region alive. I’m not running as an insider. I’m running as one of you.
            </p>
            <p>
              When plants close, when jobs disappear, when Des Moines cuts unemployment and turns a blind eye, it’s families like ours
              who pay the price. I’m running to change that.
            </p>

            <div class="hero-card-list">
              <div>
                <div class="hero-card-label">Roots</div>
                <div class="hero-card-value">Grew up in Burlington, Iowa</div>
              </div>
              <div>
                <div class="hero-card-label">Service</div>
                <div class="hero-card-value">Army Veteran, former Sergeant</div>
              </div>
              <div>
                <div class="hero-card-label">Work</div>
                <div class="hero-card-value">14+ years at CNH, UAW Local 807</div>
              </div>
              <div>
                <div class="hero-card-label">Family</div>
                <div class="hero-card-value">Husband &amp; father of three</div>
              </div>
            </div>
          </div>
          <div class="hero-card-footer">
            “Des Moines has forgotten who built this state. It’s time working Iowans had one of our own in the Iowa House.”
          </div>
        </aside>
      </div>
    </section>

    <!-- About -->
    <section id="about">
      <div class="container">
        <div class="section-heading">
          <h2 class="section-title"><span>Meet</span> Marcques</h2>
          <p class="section-subtitle">
            A Burlington kid who enlisted, came home, went to work on the line, and stepped up to lead when workers and families needed it most.
          </p>
        </div>

        <div class="about-grid">
          <div class="about-text">
            <p>
              My name is <strong>Marcques Derby</strong>, and I’m running for the Iowa House of Representatives in District 99
              because the people who built this community — the workers, parents, and families who hold this region together —
              deserve a representative who understands their lives firsthand.
            </p>
            <p>
              I grew up right here in Burlington. I went to Burlington Community High School, and like many young people trying
              to find their way, my path wasn’t a straight line. I left school during my senior year and enlisted in the Army at
              age 19 because I wanted to serve, to grow, and to build something better for myself and my future family.
            </p>
            <p>
              I worked my way to the rank of <strong>Sergeant</strong>, learning leadership, responsibility, and what it means to be
              accountable for the people around you. I’m proud of my service and the lessons it taught me — lessons I carry into
              every part of my life today.
            </p>
            <p>
              <strong>After my service, I remained home in Burlington — because this community is where my roots are. It’s where my
              family is. And it’s where I chose to raise my three children with my wife, Kaylyn.</strong>
            </p>
            <p>
              For the past fourteen years, I’ve worked at the CNH plant as a proud member of <strong>UAW Local 807</strong>, serving in multiple
              union leadership roles and now as the <strong>Bargaining Chairman</strong>, representing the more than 200 workers who keep this
              facility running. I’ve been in the trenches with workers facing layoffs, closures, and uncertainty — and I’ve seen
              firsthand how state policy either helps people survive these moments… or pushes them off a cliff.
            </p>
            <p>
              Iowa’s so-called “Right to Work” law is killing our communities one factory at a time. You can see the devastation in
              Southeast Iowa and just across the river — closure after closure, jobs shipped away, families forced to uproot or start over.
              All while Des Moines turns a blind eye.
            </p>
            <p>
              Instead of helping workers, the Legislature has cut unemployment benefits, added waiting periods, and made it harder to access
              the support families need after a layoff. Those decisions force people to choose between the house payment and feeding their kids.
              <strong>I know, because I was one of those Iowans.</strong> There was a time when foreclosure was a real possibility for my family,
              when every bill felt like a crisis and every decision came with a cost.
            </p>
            <p>
              I was fortunate enough to find a way out from under that vise grip. But too many of our neighbors never get that chance.
            </p>
            <div class="about-highlight">
              <strong>Why I’m Running:</strong> This campaign is about the people who make Iowa work — the men and women who get up
              early, work hard, raise families, and hold our communities together, even as Des Moines turns away from the real challenges
              we face. I’m running so working Iowans don’t get left out to pasture anymore.
            </div>
          </div>

          <div class="about-cards">
            <div class="stat-card">
              <div class="stat-label">Service</div>
              <div class="stat-value">Army Veteran</div>
              <p>Enlisted at 19, worked up to Sergeant, and carries those lessons of duty, teamwork, and responsibility into public life.</p>
            </div>
            <div class="stat-card">
              <div class="stat-label">Labor</div>
              <div class="stat-value">UAW Leadership</div>
              <p>14-year UAW member and current Bargaining Chairman for Local 807, standing up for more than 200 workers at CNH.</p>
            </div>
            <div class="stat-card">
              <div class="stat-label">Family</div>
              <div class="stat-value">Husband &amp; Dad</div>
              <p>Raising three kids — Bryson, Lucille, and Naomi — in the same community that raised him, with his wife, Kaylyn.</p>
            </div>
            <div class="stat-card">
              <div class="stat-label">Community</div>
              <div class="stat-value">Southeast Iowa</div>
              <p>Deeply rooted in this region, committed to rebuilding local opportunity and ensuring rural Iowa isn’t left behind.</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Priorities -->
    <section id="priorities">
      <div class="container">
        <div class="section-heading">
          <h2 class="section-title"><span>Core</span> Priorities</h2>
          <p class="section-subtitle">
            This campaign is focused on the real issues working Iowans face: jobs, wages, schools, healthcare, and keeping our communities strong.
          </p>
        </div>

        <div class="cards-grid">
          <!-- Jobs & Workers' Rights -->
          <article class="card">
            <div class="card-kicker">Jobs &amp; Workers’ Rights</div>
            <h3 class="card-title">Putting Working Iowans First</h3>
            <div class="card-body">
              <p>
                Iowa’s “Right to Work” law is killing our communities one factory at a time. From Southeast Iowa to our neighbors
                to the south, we see the same pattern: closure after closure, good jobs disappearing, and families pushed to the edge.
              </p>
              <p>
                Meanwhile, Des Moines cuts unemployment benefits, adds waiting periods, and makes it harder for laid-off workers to stay afloat.
                These aren’t abstract decisions — they create families who have to choose between the mortgage and groceries.
              </p>
              <ul>
                <li>Fight to protect and expand workers’ rights and collective bargaining.</li>
                <li>Oppose attacks on unemployment benefits and support laid-off workers.</li>
                <li>Back policies that keep good-paying jobs in Iowa instead of shipping them away.</li>
              </ul>
            </div>
            <div class="card-footer">
              “Right to Work is killing our communities one factory at a time. It’s time Des Moines stood with workers, not against them.”
            </div>
          </article>

          <!-- Education -->
          <article class="card">
            <div class="card-kicker">Education</div>
            <h3 class="card-title">Strong Public Schools for Every Child</h3>
            <div class="card-body">
              <p>
                Iowa used to lead the nation in education. We can get back there, but only if we stop treating public schools as a political
                battleground and start treating them as the backbone of our future.
              </p>
              <ul>
                <li>Fully fund public schools and support competitive pay for teachers and staff.</li>
                <li>Protect special education, counselors, and support services.</li>
                <li>Ensure rural and small-town schools have the resources they need to thrive.</li>
              </ul>
            </div>
            <div class="card-footer">
              “When we weaken our schools, we weaken our communities. Our kids deserve better than constant cuts and chaos.”
            </div>
          </article>

          <!-- Healthcare -->
          <article class="card">
            <div class="card-kicker">Healthcare</div>
            <h3 class="card-title">Healthcare That Works in Real Life</h3>
            <div class="card-body">
              <p>
                As a 100% disabled Army veteran and the father of a son with cochlear implants, I’ve lived what it means to fight for care:
                long drives, long waits, denied claims, and systems that don’t see the person behind the paperwork.
              </p>
              <ul>
                <li>Strengthen rural clinics, hospitals, and community health centers.</li>
                <li>Protect Medicaid and expand access to mental health and addiction services.</li>
                <li>Ensure families don’t have to choose between basic bills and essential care.</li>
              </ul>
            </div>
            <div class="card-footer">
              “Healthcare shouldn’t depend on your ZIP code, your employer, or your ability to battle bureaucracy.”
            </div>
          </article>
        </div>
      </div>
    </section>

    <!-- Take Action & Contact -->
    <section id="action">
      <div class="container">
        <div class="section-heading">
          <h2 class="section-title"><span>Take</span> Action</h2>
          <p class="section-subtitle">
            This campaign is powered by ordinary Iowans — workers, parents, retirees, and young people who are ready for something better.
          </p>
        </div>

        <div class="action-grid">
          <div class="action-card">
            <h3>Stand With Working Iowans</h3>
            <p>
              If you’re tired of plant closures, tired of being ignored, and tired of watching Des Moines put corporate interests ahead
              of working families, this campaign is for you.
            </p>
            <ul class="action-steps">
              <li><strong>Volunteer:</strong> Knock doors, talk to neighbors, and help spread the word.</li>
              <li><strong>Chip in:</strong> Every small donation helps us reach more voters.</li>
              <li><strong>Share your story:</strong> Tell us how state policy is affecting your family and your community.</li>
            </ul>
            <p style="margin-top: 0.8rem;">
              <em>We’ll be integrating Action Network forms here for volunteering, donating, and email sign-ups.</em>
            </p>
          </div>

          <div id="contact">
            <!-- ACTION NETWORK: replace this form with your embed code when ready -->
            <!-- Example:
            <div class="action-network-widget" data-campaign-id="xxx" data-form-id="xxx"></div>
            <script src="https://actionnetwork.org/widgets/v3/form/derby-for-iowa"></script>
            -->
            <form id="contactForm">
              <h3 style="font-size:1rem; text-transform:uppercase; letter-spacing:0.12em; margin-bottom:0.5rem;">
                Contact the Campaign
              </h3>
              <p style="font-size:0.86rem; color:var(--muted); margin-bottom:0.9rem;">
                Have a question, want to volunteer, or have a story to share about what’s happening in your corner of District 99?
                Send a note and we’ll follow up.
              </p>

              <div class="form-grid">
                <div class="form-group">
                  <label for="name">Name *</label>
                  <input id="name" type="text" name="name" placeholder="Your full name" required />
                </div>
                <div class="form-group">
                  <label for="email">Email *</label>
                  <input id="email" type="email" name="email" placeholder="you@example.com" required />
                </div>
                <div class="form-group">
                  <label for="phone">Phone</label>
                  <input id="phone" type="tel" name="phone" placeholder="Optional" />
                </div>
                <div class="form-group">
                  <label for="zip">ZIP Code</label>
                  <input id="zip" type="text" name="zip" placeholder="ZIP" />
                </div>
                <div class="form-group form-full">
                  <label for="message">Message *</label>
                  <textarea id="message" name="message" placeholder="How would you like to get involved, or what’s on your mind?" required></textarea>
                </div>
              </div>

              <div class="form-footer">
                <button type="submit" class="btn btn-primary" style="font-size:0.8rem;">
                  Send Message
                </button>
                <div class="required-note">
                  * Required fields. This is a placeholder form — later we’ll replace it with your Action Network form embed.
                </div>
              </div>
            </form>
          </div>
        </div>
      </div>
    </section>
  </main>

  <!-- Footer -->
  <footer>
    <div class="container footer-inner">
      <div>
        <div class="footer-paid">
          Paid for by Marcques Derby for Iowa House District 99
        </div>
        <div>© <span id="year"></span> Marcques Derby. All rights reserved.</div>
      </div>
      <div class="footer-links">
        <a href="#">Privacy</a>
        <a href="#">Terms</a>
      </div>
    </div>
  </footer>
</div>

<script>
  // Mobile nav toggle
  const navToggle = document.getElementById('navToggle');
  const navLinks = document.getElementById('navLinks');

  if (navToggle && navLinks) {
    navToggle.addEventListener('click', () => {
      navLinks.classList.toggle('open');
    });

    navLinks.querySelectorAll('a').forEach(link => {
      link.addEventListener('click', () => {
        navLinks.classList.remove('open');
      });
    });
  }

  // Smooth scroll helper
  function scrollToId(id) {
    const el = document.getElementById(id);
    if (!el) return;
    const y = el.getBoundingClientRect().top + window.scrollY - 70;
    window.scrollTo({ top: y, behavior: 'smooth' });
  }

  // Contact form (front-end only placeholder)
  const contactForm = document.getElementById('contactForm');
  if (contactForm) {
    contactForm.addEventListener('submit', function (e) {
      e.preventDefault();
      const name = this.name.value.trim();
      const email = this.email.value.trim();
      const message = this.message.value.trim();

      if (!name || !email || !message) {
        alert('Please fill in the required fields (Name, Email, Message).');
        return;
      }

      alert('Thank you for reaching out! This is a placeholder form. Once Action Network is connected, your message will go directly to the campaign.');
      this.reset();
    });
  }

  // Footer year
  const yearSpan = document.getElementById('year');
  if (yearSpan) {
    yearSpan.textContent = new Date().getFullYear();
  }
</script>
</body>
</html>
