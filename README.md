# BlueWaveCleaningCO
/
  index.html
  styles.css
  script.js
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>BlueWave Cleaning | El Cajon & La Mesa</title>

  <meta name="description" content="BlueWave Cleaning provides detailed, reliable residential and light commercial cleaning in El Cajon and La Mesa. Instant quote request, flexible scheduling, consistent results." />
  <meta name="theme-color" content="#0b4aa2" />

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="styles.css" />
</head>

<body>
  <header class="site-header">
    <div class="container header-inner">
      <a class="brand" href="#top" aria-label="Home">
        <span class="brand-dot"></span>
        <span class="brand-name">BlueWave Cleaning</span>
      </a>

      <nav class="nav">
        <a href="#services">Services</a>
        <a href="#pricing">Packages</a>
        <a href="#quote">Request a Quote</a>
        <a class="btn btn-small" href="#quote">Get Quote</a>
      </nav>

      <button class="menu-btn" aria-label="Open menu" id="menuBtn">☰</button>
    </div>

    <div class="mobile-nav" id="mobileNav" hidden>
      <a href="#services">Services</a>
      <a href="#pricing">Packages</a>
      <a href="#quote">Request a Quote</a>
    </div>
  </header>

  <main id="top">
    <!-- HERO -->
    <section class="hero">
      <div class="container hero-grid">
        <div class="hero-copy">
          <div class="banner" role="status">
            <span class="dot"></span>
            <span><strong>Fast response:</strong> Quote requests answered within 1–2 hours (typical).</span>
          </div>

          <p class="pill">El Cajon • La Mesa • East County San Diego</p>
          <h1>Clean that feels like a fresh start.</h1>
          <p class="subhead">
            Detailed residential and light commercial cleaning with consistent, checklist-based results.
            One-time, move-out, or recurring—done right.
          </p>

          <div class="cta-row">
            <a class="btn" href="#quote">Request a Quote</a>
            <a class="btn btn-ghost" href="#services">View Services</a>
          </div>

          <div class="trust-row">
            <div class="trust-card">
              <strong>✔ Consistent</strong>
              <span>Checklist-driven quality</span>
            </div>
            <div class="trust-card">
              <strong>✔ Punctual</strong>
              <span>Clear arrival windows</span>
            </div>
            <div class="trust-card">
              <strong>✔ Local</strong>
              <span>East County focused</span>
            </div>
          </div>

          <div class="quick-actions">
            <!-- OPTIONAL: add your phone number in script.js -->
            <a class="action" id="callBtn" href="#" aria-label="Call BlueWave Cleaning">📞 Call</a>
            <a class="action" id="textBtn" href="#" aria-label="Text BlueWave Cleaning">💬 Text</a>
            <a class="action" id="emailBtn" href="mailto:BlueWaveCleaningSD@gmail.com?subject=Quote%20Request%20-%20BlueWave%20Cleaning" aria-label="Email BlueWave Cleaning">✉️ Email</a>
          </div>

          <p class="fineprint">
            Serving El Cajon, La Mesa, and nearby East County neighborhoods. Fully customizable clean plans.
          </p>
        </div>

        <!-- MASCOT SVG -->
        <div class="hero-mascot" aria-hidden="true">
          <svg viewBox="0 0 640 520" role="img" aria-label="Blue wave crashing over a setting sun">
            <defs>
              <linearGradient id="waveGrad" x1="0" y1="0" x2="1" y2="1">
                <stop offset="0%" stop-color="#0a66ff"/>
                <stop offset="60%" stop-color="#0b4aa2"/>
                <stop offset="100%" stop-color="#062a5c"/>
              </linearGradient>
              <linearGradient id="skyGrad" x1="0" y1="0" x2="0" y2="1">
                <stop offset="0%" stop-color="#0b1b3a"/>
                <stop offset="60%" stop-color="#142b52"/>
                <stop offset="100%" stop-color="#0a1a33"/>
              </linearGradient>
              <radialGradient id="sunGrad" cx="50%" cy="50%" r="60%">
                <stop offset="0%" stop-color="#ffd36b"/>
                <stop offset="55%" stop-color="#ff9f3d"/>
                <stop offset="100%" stop-color="#ff6b2c"/>
              </radialGradient>
              <filter id="softShadow" x="-20%" y="-20%" width="140%" height="140%">
                <feDropShadow dx="0" dy="12" stdDeviation="14" flood-color="#000" flood-opacity="0.25"/>
              </filter>
            </defs>

            <rect x="0" y="0" width="640" height="520" rx="28" fill="url(#skyGrad)"/>
            <circle cx="420" cy="250" r="86" fill="url(#sunGrad)" filter="url(#softShadow)"/>
            <rect x="0" y="288" width="640" height="232" fill="#0a1a33" opacity="0.25"/>

            <path fill="url(#waveGrad)" filter="url(#softShadow)"
              d="M 20 410
                 C 90 320, 220 300, 300 320
                 C 350 180, 520 180, 560 290
                 C 590 370, 520 430, 420 438
                 C 320 445, 240 420, 180 460
                 C 120 500, 60 485, 20 450 Z" />

            <path fill="#6fb7ff" opacity="0.85"
              d="M 270 330
                 C 310 250, 420 230, 480 270
                 C 430 260, 370 290, 360 330
                 C 350 370, 400 395, 455 395
                 C 380 430, 285 410, 270 330 Z" />

            <g fill="#cfeaff" opacity="0.9">
              <circle cx="505" cy="300" r="6"/>
              <circle cx="520" cy="318" r="4"/>
              <circle cx="488" cy="320" r="5"/>
              <circle cx="458" cy="305" r="3.5"/>
              <circle cx="438" cy="325" r="4"/>
              <circle cx="420" cy="308" r="3"/>
              <circle cx="404" cy="330" r="3.5"/>
              <circle cx="468" cy="344" r="3"/>
            </g>

            <path d="M 80 430 C 150 390, 210 395, 260 420"
              stroke="#9bd2ff" stroke-width="6" opacity="0.35" fill="none" stroke-linecap="round"/>

            <text x="36" y="70" fill="#d7e9ff" opacity="0.85" font-family="Inter, system-ui" font-size="20" font-weight="600">
              BlueWave Cleaning
            </text>
          </svg>
        </div>
      </div>
    </section>

    <!-- TRUST STRIP -->
    <section class="strip">
      <div class="container strip-inner">
        <div class="strip-item"><strong>⭐ Satisfaction-first</strong><span>We fix misses fast</span></div>
        <div class="strip-item"><strong>🧼 Detail focus</strong><span>High-touch areas prioritized</span></div>
        <div class="strip-item"><strong>📍 Local</strong><span>El Cajon & La Mesa</span></div>
      </div>
    </section>

    <!-- SERVICES -->
    <section class="section" id="services">
      <div class="container">
        <h2>Services</h2>
        <p class="section-sub">Pick what you need. Add-ons and recurring plans available.</p>

        <div class="cards">
          <article class="card">
            <h3>Standard Clean</h3>
            <p>Maintenance clean for homes and apartments—best for recurring clients.</p>
            <ul>
              <li>Bathrooms, kitchen, floors, dusting</li>
              <li>Tidy-up + high-touch wipe-downs</li>
              <li>Weekly / biweekly / monthly</li>
            </ul>
          </article>

          <article class="card">
            <h3>Deep Clean Reset</h3>
            <p>For first-time clients or when you want a true reset.</p>
            <ul>
              <li>Edges, buildup zones, extra detail</li>
              <li>Baseboards & focus areas (as needed)</li>
              <li>Recommended first visit</li>
            </ul>
          </article>

          <article class="card">
            <h3>Move-In / Move-Out</h3>
            <p>Perfect for keys, deposits, and real estate photos.</p>
            <ul>
              <li>Empty-home attention to detail</li>
              <li>Add appliances/cabinets if needed</li>
              <li>Fast turnaround</li>
            </ul>
          </article>

          <article class="card">
            <h3>Office / Light Commercial</h3>
            <p>Keep your workplace looking professional.</p>
            <ul>
              <li>Restrooms, breakrooms, floors</li>
              <li>After-hours options</li>
              <li>Recurring schedules</li>
            </ul>
          </article>
        </div>
      </div>
    </section>

    <!-- PACKAGES -->
    <section class="section section-alt" id="pricing">
      <div class="container split">
        <div>
          <h2>Packages that sell</h2>
          <p class="section-sub">
            Presenting packages increases bookings. Use these as your website “menu” and confirm final pricing after details.
          </p>

          <div class="price-grid">
            <div class="price">
              <div class="price-top"><strong>Maintenance</strong><span>Best value</span></div>
              <div class="price-body">
                <p><strong>Standard Clean</strong> + high-touch focus</p>
                <p class="muted">Weekly / biweekly options</p>
              </div>
              <button class="btn btn-small ghostlike" data-package="Maintenance">Choose</button>
            </div>

            <div class="price">
              <div class="price-top"><strong>Reset</strong><span>Most popular</span></div>
              <div class="price-body">
                <p><strong>Deep Clean Reset</strong> + detail work</p>
                <p class="muted">Ideal first booking</p>
              </div>
              <button class="btn btn-small ghostlike" data-package="Reset">Choose</button>
            </div>

            <div class="price">
              <div class="price-top"><strong>Move-Out</strong><span>High ROI</span></div>
              <div class="price-body">
                <p><strong>Move-In/Move-Out</strong> photo-ready</p>
                <p class="muted">Great for deposits</p>
              </div>
              <button class="btn btn-small ghostlike" data-package="Move-Out">Choose</button>
            </div>
          </div>

          <div class="addons">
            <h3>Add-ons</h3>
            <div class="addon-grid">
              <div class="addon">Inside fridge</div>
              <div class="addon">Inside oven</div>
              <div class="addon">Inside cabinets</div>
              <div class="addon">Interior windows</div>
              <div class="addon">Baseboards focus</div>
              <div class="addon">Laundry (by request)</div>
            </div>
            <p class="muted tiny">Add-ons are confirmed during quoting.</p>
          </div>
        </div>

        <aside class="cta-panel">
          <h3>Want the fastest booking?</h3>
          <p>Send a quote request with your home size + preferred day. We’ll reply with pricing and next openings.</p>

          <div class="cta-stack">
            <a class="btn" href="#quote">Request a Quote</a>
            <a class="btn btn-ghost" href="mailto:BlueWaveCleaningSD@gmail.com?subject=Quote%20Request%20-%20BlueWave%20Cleaning">Email Instead</a>
          </div>

          <div class="mini">
            <div><strong>Typical hours</strong></div>
            <div class="muted">Mon–Sat • 8am–6pm</div>
            <div class="muted tiny">You can change this anytime.</div>
          </div>
        </aside>
      </div>
    </section>

    <!-- QUOTE FORM (MAILTO) -->
    <section class="section" id="quote">
      <div class="container">
        <h2>Request a Quote</h2>
        <p class="section-sub">
          This will open your email app with everything filled out. No accounts, no logins.
        </p>

        <div class="form-grid">
          <form class="card form" id="quoteForm">
            <div class="field-row">
              <div class="field">
                <label for="q_name">Full name</label>
                <input id="q_name" name="name" required autocomplete="name" />
              </div>
              <div class="field">
                <label for="q_phone">Phone (optional)</label>
                <input id="q_phone" name="phone" autocomplete="tel" placeholder="So we can text you openings" />
              </div>
            </div>

            <div class="field-row">
              <div class="field">
                <label for="q_email">Email</label>
                <input id="q_email" name="email" type="email" required autocomplete="email" />
              </div>
              <div class="field">
                <label for="q_service">Service</label>
                <select id="q_service" name="service" required>
                  <option value="" selected disabled>Select one</option>
                  <option>Standard Clean</option>
                  <option>Deep Clean Reset</option>
                  <option>Move-In / Move-Out</option>
                  <option>Office / Light Commercial</option>
                </select>
              </div>
            </div>

            <div class="field-row">
              <div class="field">
                <label for="q_size">Size</label>
                <select id="q_size" name="size" required>
                  <option value="" selected disabled>Select</option>
                  <option>Studio / 1 bed</option>
                  <option>2 bed</option>
                  <option>3 bed</option>
                  <option>4+ bed</option>
                  <option>Office (small)</option>
                  <option>Office (medium)</option>
                </select>
              </div>
              <div class="field">
                <label for="q_area">Area (zip/neighborhood)</label>
                <input id="q_area" name="area" required placeholder="Example: La Mesa 91942" />
              </div>
            </div>

            <div class="field-row">
              <div class="field">
                <label for="q_day">Preferred day</label>
                <input id="q_day" name="day" placeholder="Example: Friday or 2/23" />
              </div>
              <div class="field">
                <label for="q_window">Preferred time window</label>
                <input id="q_window" name="window" placeholder="Example: 10am–1pm" />
              </div>
            </div>

            <div class="field">
              <label>Add-ons (optional)</label>
              <div class="checks">
                <label><input type="checkbox" name="addons" value="Inside fridge"> Inside fridge</label>
                <label><input type="checkbox" name="addons" value="Inside oven"> Inside oven</label>
                <label><input type="checkbox" name="addons" value="Inside cabinets"> Inside cabinets</label>
                <label><input type="checkbox" name="addons" value="Interior windows"> Interior windows</label>
              </div>
            </div>

            <div class="field">
              <label for="q_notes">Notes</label>
              <textarea id="q_notes" name="notes" rows="4" placeholder="Pets, parking, priorities, condition, etc."></textarea>
            </div>

            <button class="btn" type="submit">Open Email to Send</button>
            <p class="muted tiny">This uses your device’s email app. If you don’t have one set up, use the Email button above.</p>
          </form>

          <aside class="card sidebar">
            <h3>What we need to quote fast</h3>
            <ul>
              <li>Home size (beds/baths)</li>
              <li>Zip / neighborhood</li>
              <li>Service type + add-ons</li>
              <li>Ideal day/time window</li>
            </ul>

            <div class="divider"></div>

            <h3>Make it recurring</h3>
            <p class="muted">
              Recurring clients are the most profitable. Offer:
            </p>
            <ul>
              <li>Biweekly priority scheduling</li>
              <li>Small discount after first deep clean</li>
              <li>Monthly “mini reset” add-on</li>
            </ul>
          </aside>
        </div>
      </div>
    </section>

    <!-- FAQ + SOCIAL PROOF -->
    <section class="section section-alt" id="faq">
      <div class="container">
        <h2>FAQ</h2>

        <div class="faq">
          <details class="card">
            <summary>Do I have to be home?</summary>
            <p>You can be home or away. Many clients share a door code or key instructions securely.</p>
          </details>

          <details class="card">
            <summary>What supplies do you use?</summary>
            <p>We bring standard supplies. If you prefer specific products, put it in your request.</p>
          </details>

          <details class="card">
            <summary>How do you price jobs?</summary>
            <p>Pricing depends on size, condition, and add-ons. We confirm clearly before the appointment.</p>
          </details>

          <details class="card">
            <summary>Do you offer recurring discounts?</summary>
            <p>Yes—recurring clients get priority scheduling and may qualify for a reduced rate.</p>
          </details>
        </div>

        <div class="reviews-cta card">
          <div>
            <h3>Reviews help you rank locally</h3>
            <p class="muted">Once you have a Google Business Profile, link it here and ask every happy client for a review.</p>
          </div>
          <a class="btn btn-small" id="reviewsBtn" href="#" target="_blank" rel="noopener">Google Reviews Link</a>
        </div>
      </div>
    </section>
  </main>

  <footer class="footer">
    <div class="container footer-inner">
      <div>
        <strong>BlueWave Cleaning</strong>
        <div class="muted">El Cajon • La Mesa • East County San Diego</div>
        <div class="muted tiny">Email: BlueWaveCleaningSD@gmail.com</div>
      </div>
      <div class="muted">© <span id="year"></span> BlueWave Cleaning</div>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
:root{
  --bg:#07162f;
  --panel:rgba(255,255,255,0.06);
  --panel2:rgba(255,255,255,0.10);
  --text:#eaf2ff;
  --muted:rgba(234,242,255,0.72);
  --brand:#0a66ff;
  --brand2:#0b4aa2;
  --stroke:rgba(255,255,255,0.14);
  --radius:18px;
  --shadow:0 16px 40px rgba(0,0,0,0.35);
}

*{box-sizing:border-box}
html,body{
  margin:0;padding:0;
  font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif;
  background:radial-gradient(1200px 800px at 10% 10%, #0b2b5e 0%, var(--bg) 55%);
  color:var(--text);
}
a{color:inherit;text-decoration:none}
.container{max-width:1120px;margin:0 auto;padding:0 18px}

.site-header{
  position:sticky;top:0;z-index:50;
  background:rgba(7,22,47,0.78);
  backdrop-filter:blur(12px);
  border-bottom:1px solid var(--stroke);
}
.header-inner{display:flex;align-items:center;justify-content:space-between;padding:14px 0;gap:14px}
.brand{display:flex;align-items:center;gap:10px;font-weight:800;letter-spacing:.2px}
.brand-dot{
  width:14px;height:14px;border-radius:999px;
  background:linear-gradient(135deg,var(--brand),#6fb7ff);
  box-shadow:0 0 0 6px rgba(10,102,255,0.18);
}
.brand-name{font-size:16px}

.nav{display:flex;gap:18px;align-items:center}
.nav a{color:var(--muted);font-weight:700}
.nav a:hover{color:var(--text)}

.menu-btn{
  display:none;background:transparent;
  border:1px solid var(--stroke);color:var(--text);
  border-radius:12px;padding:8px 10px;
}
.mobile-nav{
  border-top:1px solid var(--stroke);
  padding:10px 18px 16px;
  display:flex;flex-direction:column;gap:10px;
}
.mobile-nav a{color:var(--muted);font-weight:800}

.hero{padding:42px 0 18px}
.hero-grid{display:grid;grid-template-columns:1.1fr 0.9fr;gap:26px;align-items:center}

.banner{
  display:flex;align-items:center;gap:10px;
  background:rgba(111,183,255,0.10);
  border:1px solid rgba(111,183,255,0.20);
  border-radius:999px;
  padding:10px 12px;
  color:rgba(234,242,255,0.9);
  font-weight:650;
}
.banner .dot{
  width:10px;height:10px;border-radius:999px;
  background:#6fb7ff;
  box-shadow:0 0 0 6px rgba(111,183,255,0.16);
}

.pill{
  display:inline-block;
  margin-top:14px;
  background:rgba(255,255,255,0.06);
  border:1px solid rgba(255,255,255,0.12);
  padding:8px 12px;border-radius:999px;
  color:var(--muted);font-weight:800;font-size:13px;
}
h1{font-size:46px;line-height:1.05;margin:14px 0 10px;letter-spacing:-0.02em}
.subhead{color:var(--muted);font-size:16px;line-height:1.7;max-width:56ch}

.cta-row{display:flex;gap:12px;margin-top:18px;flex-wrap:wrap}
.btn{
  background:linear-gradient(135deg,var(--brand),var(--brand2));
  border:0;color:white;
  padding:12px 16px;border-radius:14px;
  font-weight:900;cursor:pointer;
  display:inline-flex;align-items:center;justify-content:center;
  box-shadow:0 14px 30px rgba(10,102,255,0.25);
}
.btn:hover{filter:brightness(1.07)}
.btn-ghost{
  background:transparent;border:1px solid rgba(255,255,255,0.18);
  color:var(--text);box-shadow:none;
}
.btn-small{padding:10px 12px;border-radius:12px;font-weight:900}
.ghostlike{background:transparent;border:1px solid rgba(255,255,255,0.18);box-shadow:none}

.trust-row{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;margin-top:18px}
.trust-card{
  background:var(--panel);
  border:1px solid var(--stroke);
  border-radius:var(--radius);
  padding:12px;
}
.trust-card strong{display:block;margin-bottom:4px}
.trust-card span{color:var(--muted);font-size:13px}

.quick-actions{display:flex;gap:10px;margin-top:16px;flex-wrap:wrap}
.action{
  background:rgba(255,255,255,0.06);
  border:1px solid rgba(255,255,255,0.14);
  border-radius:999px;
  padding:10px 12px;
  color:rgba(234,242,255,0.88);
  font-weight:800;
}
.action:hover{background:rgba(255,255,255,0.10)}
.fineprint{color:var(--muted);font-size:13px;margin-top:14px}

.hero-mascot svg{
  width:100%;height:auto;
  border-radius:22px;
  border:1px solid rgba(255,255,255,0.12);
  box-shadow:var(--shadow);
}

.strip{padding:16px 0;border-top:1px solid var(--stroke);border-bottom:1px solid var(--stroke);background:rgba(255,255,255,0.02)}
.strip-inner{display:grid;grid-template-columns:repeat(3,1fr);gap:10px}
.strip-item{
  background:rgba(255,255,255,0.04);
  border:1px solid rgba(255,255,255,0.10);
  border-radius:14px;
  padding:12px;
}
.strip-item span{display:block;color:var(--muted);margin-top:4px}

.section{padding:42px 0}
.section-alt{background:rgba(255,255,255,0.03);border-top:1px solid var(--stroke);border-bottom:1px solid var(--stroke)}
h2{font-size:30px;margin:0 0 8px;letter-spacing:-0.01em}
.section-sub{color:var(--muted);margin:0 0 18px;line-height:1.7}

.cards{display:grid;grid-template-columns:repeat(4,1fr);gap:14px}
.card{
  background:var(--panel);
  border:1px solid var(--stroke);
  border-radius:var(--radius);
  padding:16px;
}
.card p,.card li{color:var(--muted);line-height:1.7}
.card ul{margin:10px 0 0;padding-left:18px}

.split{display:grid;grid-template-columns:1.2fr 0.8fr;gap:18px;align-items:start}

.price-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:12px;margin-top:14px}
.price{
  background:rgba(255,255,255,0.05);
  border:1px solid rgba(255,255,255,0.12);
  border-radius:var(--radius);
  padding:14px;
}
.price-top{display:flex;justify-content:space-between;color:rgba(234,242,255,0.9);font-weight:900}
.price-body{margin-top:8px}
.addons{margin-top:18px}
.addon-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;margin-top:10px}
.addon{
  border:1px solid rgba(255,255,255,0.12);
  background:rgba(255,255,255,0.05);
  border-radius:999px;
  padding:10px 12px;
  color:rgba(234,242,255,0.88);
  font-weight:750;
  text-align:center;
}

.cta-panel{
  background:linear-gradient(135deg, rgba(10,102,255,0.18), rgba(111,183,255,0.08));
  border:1px solid rgba(111,183,255,0.24);
  border-radius:var(--radius);
  padding:18px;
  box-shadow:var(--shadow);
}
.cta-panel p{color:var(--muted);line-height:1.7}
.cta-stack{display:flex;flex-direction:column;gap:10px;margin-top:12px}
.mini{margin-top:14px}
.muted{color:var(--muted)}
.tiny{font-size:12px}

.form-grid{display:grid;grid-template-columns:1fr 0.55fr;gap:14px;align-items:start}
.field{display:flex;flex-direction:column;gap:6px;margin-bottom:12px}
.field-row{display:grid;grid-template-columns:1fr 1fr;gap:12px}
label{font-weight:800;font-size:13px;color:rgba(234,242,255,0.92)}

input,select,textarea{
  background:rgba(255,255,255,0.06);
  border:1px solid rgba(255,255,255,0.14);
  border-radius:12px;color:var(--text);
  padding:12px;font-size:14px;outline:none;
}
input:focus,select:focus,textarea:focus{
  border-color:rgba(111,183,255,0.55);
  box-shadow:0 0 0 6px rgba(111,183,255,0.12);
}
.checks{display:grid;grid-template-columns:1fr 1fr;gap:8px}
.checks label{font-weight:650;color:var(--muted);display:flex;gap:8px;align-items:center}

.sidebar ul{color:var(--muted);line-height:1.7}
.divider{height:1px;background:var(--stroke);margin:14px 0}

.faq{display:grid;grid-template-columns:1fr 1fr;gap:12px}
details summary{cursor:pointer;font-weight:900}
details p{margin-top:10px}

.reviews-cta{
  margin-top:14px;
  display:flex;align-items:center;justify-content:space-between;
  gap:12px;
}

.footer{padding:24px 0;border-top:1px solid var(--stroke)}
.footer-inner{display:flex;justify-content:space-between;gap:12px;flex-wrap:wrap}

@media (max-width:980px){
  .hero-grid{grid-template-columns:1fr}
  .cards{grid-template-columns:repeat(2,1fr)}
  .split{grid-template-columns:1fr}
  .form-grid{grid-template-columns:1fr}
  .strip-inner{grid-template-columns:1fr}
  .addon-grid{grid-template-columns:repeat(2,1fr)}
  h1{font-size:40px}
}
@media (max-width:640px){
  .nav{display:none}
  .menu-btn{display:inline-flex}
  .cards{grid-template-columns:1fr}
  .trust-row{grid-template-columns:1fr}
  .field-row{grid-template-columns:1fr}
  .faq{grid-template-columns:1fr}
  .addon-grid{grid-template-columns:1fr}
  .reviews-cta{flex-direction:column;align-items:stretch}
}
// Edit these 2 values if you want click-to-call and click-to-text.
// If you don't have a business number yet, leave them blank.
const CONFIG = {
  phoneE164: "", // Example: "+16195551234"
  reviewsUrl: "" // Example: "https://g.page/r/XXXXX/review" or your GBP link
};

const BUSINESS_EMAIL = "BlueWaveCleaningSD@gmail.com";

(function init() {
  // Footer year
  const yearEl = document.getElementById("year");
  if (yearEl) yearEl.textContent = new Date().getFullYear();

  // Mobile menu
  const menuBtn = document.getElementById("menuBtn");
  const mobileNav = document.getElementById("mobileNav");
  if (menuBtn && mobileNav) {
    menuBtn.addEventListener("click", () => {
      const isHidden = mobileNav.hasAttribute("hidden");
      if (isHidden) mobileNav.removeAttribute("hidden");
      else mobileNav.setAttribute("hidden", "");
    });
    mobileNav.querySelectorAll("a").forEach(a => {
      a.addEventListener("click", () => mobileNav.setAttribute("hidden", ""));
    });
  }

  // Call/Text buttons
  const callBtn = document.getElementById("callBtn");
  const textBtn = document.getElementById("textBtn");

  if (CONFIG.phoneE164) {
    if (callBtn) callBtn.href = `tel:${CONFIG.phoneE164}`;
    if (textBtn) textBtn.href = `sms:${CONFIG.phoneE164}`;
  } else {
    // If no phone provided, hide these actions so it doesn't look broken
    if (callBtn) callBtn.style.display = "none";
    if (textBtn) textBtn.style.display = "none";
  }

  // Reviews link
  const reviewsBtn = document.getElementById("reviewsBtn");
  if (CONFIG.reviewsUrl) {
    reviewsBtn.href = CONFIG.reviewsUrl;
  } else {
    // If you don't have it yet, make it mailto so the button still does something useful
    reviewsBtn.href = `mailto:${BUSINESS_EMAIL}?subject=Review%20Request%20Link%20-%20BlueWave%20Cleaning`;
    reviewsBtn.textContent = "Set Up Reviews";
  }

  // Quote form -> mailto
  const form = document.getElementById("quoteForm");
  if (!form) return;

  // Package buttons auto-fill service + scroll to form
  document.querySelectorAll("[data-package]").forEach(btn => {
    btn.addEventListener("click", () => {
      const pkg = btn.getAttribute("data-package");
      const serviceSelect = document.getElementById("q_service");
      if (serviceSelect) {
        if (pkg === "Maintenance") serviceSelect.value = "Standard Clean";
        if (pkg === "Reset") serviceSelect.value = "Deep Clean Reset";
        if (pkg === "Move-Out") serviceSelect.value = "Move-In / Move-Out";
      }
      document.getElementById("quote").scrollIntoView({ behavior: "smooth" });
    });
  });

  form.addEventListener("submit", (e) => {
    e.preventDefault();

    const fd = new FormData(form);
    const addons = fd.getAll("addons").join(", ") || "None";

    const name = fd.get("name") || "";
    const phone = fd.get("phone") || "";
    const email = fd.get("email") || "";
    const service = fd.get("service") || "";
    const size = fd.get("size") || "";
    const area = fd.get("area") || "";
    const day = fd.get("day") || "";
    const window = fd.get("window") || "";
    const notes = fd.get("notes") || "";

    const subject = encodeURIComponent(`Quote Request — ${service} (${area})`);
    const body = encodeURIComponent(
`Hi BlueWave Cleaning,

I'd like a quote.

Name: ${name}
Email: ${email}
Phone: ${phone}

Service: ${service}
Size: ${size}
Area: ${area}
Preferred day: ${day}
Preferred window: ${window}

Add-ons: ${addons}

Notes:
${notes}

Thanks!`
    );

    window.location.href = `mailto:${BUSINESS_EMAIL}?subject=${subject}&body=${body}`;
  });
})();
