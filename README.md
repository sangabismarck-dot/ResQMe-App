<!-- ResQMe Landing Page - Style E (Mix of modern, friendly, and professional)
     This single-file HTML/CSS template is ready for GitHub Pages or any static host.
     Includes local image reference to the proposal image at:
     /mnt/data/A_business_proposal_document_for_"Rescue_Alert_App.png
-->

<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>ResQMe — Your Emergency Companion</title>
  <meta name="description" content="ResQMe: real-time emergency app & wearable. Panic button, drug-detection watch, community assist, SAPS/EMS integration.">
  <style>
    :root{--red:#E53935;--dark:#111827;--muted:#6B7280;--bg:#F8FAFC;--card:#FFFFFF}
    *{box-sizing:border-box}
    body{margin:0;font-family:Inter,system-ui,Segoe UI,Roboto,'Helvetica Neue',Arial; background:var(--bg); color:var(--dark);}
    header{background:linear-gradient(90deg,rgba(229,57,53,0.06),transparent);padding:28px 20px;display:flex;align-items:center;justify-content:space-between}
    .brand{display:flex;align-items:center;gap:14px}
    .logo{width:56px;height:56px;border-radius:12px;background:var(--card);display:flex;align-items:center;justify-content:center;box-shadow:0 6px 18px rgba(17,24,39,0.06)}
    .logo img{max-width:46px;max-height:46px}
    nav a{color:var(--dark);text-decoration:none;margin:0 10px;font-weight:600}
    .container{max-width:1100px;margin:28px auto;padding:0 20px}
    .hero{display:grid;grid-template-columns:1fr 420px;gap:28px;align-items:center}
    .card{background:var(--card);padding:20px;border-radius:12px;box-shadow:0 10px 30px rgba(2,6,23,0.04)}
    h1{font-size:28px;margin:0 0 12px}
    p.lead{color:var(--muted);margin-top:0}
    .cta{display:flex;gap:12px;margin-top:18px}
    .btn{background:var(--red);color:#fff;padding:10px 16px;border-radius:10px;border:none;font-weight:700;cursor:pointer}
    .btn.ghost{background:transparent;color:var(--red);border:2px solid rgba(229,57,53,0.12)}
    .features{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin-top:22px}
    .feature{padding:14px;border-radius:10px;background:linear-gradient(180deg,#fff,#fbfbfb);border:1px solid rgba(17,24,39,0.03)}
    .watch-visual{display:flex;align-items:center;justify-content:center;height:100%;}
    .partners{display:grid;grid-template-columns:repeat(4,1fr);gap:12px;margin-top:18px}
    footer{margin-top:36px;padding:28px 20px;background:#fff;border-top:1px solid #eee}
    .grid2{display:grid;grid-template-columns:1fr 1fr;gap:16px}
    .muted{color:var(--muted)}
    @media(max-width:900px){.hero{grid-template-columns:1fr;}.features{grid-template-columns:1fr 1fr}.partners{grid-template-columns:repeat(2,1fr)}.grid2{grid-template-columns:1fr}}
    @media(max-width:520px){.features{grid-template-columns:1fr}.partners{grid-template-columns:1fr}}
    /* small utility */
    .pill{display:inline-block;background:rgba(16,185,129,0.08);color:#059669;padding:6px 10px;border-radius:999px;font-weight:700}
  </style>
</head>
<body>
  <header>
    <div class="brand container">
      <div class="logo card"><img src='/mnt/data/A_business_proposal_document_for_"Rescue_Alert_App.png' alt='ResQMe logo'></div>
      <div>
        <div style="font-weight:800">ResQMe</div>
        <div style="font-size:12px;color:var(--muted)">Your Emergency Companion</div>
      </div>
    </div>
    <nav style="padding-right:20px">
      <a href="#features">Features</a>
      <a href="#partners">Partners</a>
      <a href="#get">Get Involved</a>
    </nav>
  </header>

  <main class="container">
    <section class="hero">
      <div>
        <div class="card">
          <h1>ResQMe — Rapid rescue, where you are</h1>
          <p class="lead">A mobile & smartwatch emergency platform that connects you instantly to emergency services, family, and a community of responders. Panic button, drug-detection watch, offline alerts, and ride-share monitoring — all in one place.</p>
          <div class="cta">
            <button class="btn">Join Beta (Free)</button>
            <button class="btn ghost">Request Partnership</button>
          </div>

          <div class="features" id="features">
            <div class="feature">
              <h3>One-Touch Panic</h3>
              <p class="muted">Instant alert from phone or watch with GPS, medical profile & audio recording.</p>
            </div>
            <div class="feature">
              <h3>ResQMe Shield™</h3>
              <p class="muted">Drink & post-ingestion detection, flashing watch alert, rapid escalation to EMS & SAPS.</p>
            </div>
            <div class="feature">
              <h3>Community Assist</h3>
              <p class="muted">Help strangers nearby — report incidents even if they don't have the app.</p>
            </div>
          </div>

        </div>

        <div class="card" style="margin-top:16px">
          <h3>Why South Africa Needs ResQMe</h3>
          <p class="muted">High GBV rates, kidnappings, and delayed emergency response make a unified, real-time rescue platform a national priority. ResQMe bridges the gap between danger and help.</p>
        </div>

      </div>

      <aside>
        <div class="card" style="text-align:center">
          <div style="font-weight:800;font-size:18px">ResQMe Watch</div>
          <div class="watch-visual" style="padding:18px">
            <!-- simple watch mockup -->
            <div style="width:220px;height:220px;border-radius:36px;background:linear-gradient(180deg,#111827,#0f172a);display:flex;align-items:center;justify-content:center;color:#fff;box-shadow:0 10px 30px rgba(2,6,23,0.18)">
              <div style="text-align:center">
                <div style="font-size:22px;font-weight:800">ResQMe</div>
                <div style="font-size:12px;color:#f3f4f6;margin-top:6px">Drug Detection • Panic • SOS</div>
                <div style="margin-top:10px;background:rgba(255,255,255,0.08);padding:8px;border-radius:8px;font-weight:700">Flashing Alert</div>
              </div>
            </div>
          </div>
          <p class="muted" style="margin-top:12px">Wearable-first design with biometric monitoring, breath/saliva sensor support, and a visible flashing alarm to warn bystanders.</p>
          <div style="margin-top:12px">
            <button class="btn" onclick="alert('Beta sign-up sent!')">Sign Up for Watch Beta</button>
          </div>
        </div>

        <div class="card" style="margin-top:16px">
          <h4>Quick Stats</h4>
          <div class="grid2">
            <div><strong>1 in 3</strong><div class="muted">Women affected by GBV</div></div>
            <div><strong>5000+</strong><div class="muted">Kidnappings reported annually</div></div>
          </div>
          <p class="muted" style="margin-top:10px">ResQMe focuses on prevention, rapid response, and community empowerment.</p>
        </div>
      </aside>
    </section>

    <section class="card" style="margin-top:24px">
      <h3 id="partners">Partners & Benefits</h3>
      <p class="muted">We collaborate with emergency services, telcos, NGOs, universities, and corporate sponsors. Partners gain CSR value, improved public safety outcomes, and access to new user bases.</p>
      <div class="partners">
        <div class="card"><strong>SAPS</strong><div class="muted">Faster crime response</div></div>
        <div class="card"><strong>MTN / Vodacom</strong><div class="muted">Zero-rated data & rural reach</div></div>
        <div class="card"><strong>CSIR / SAMRC</strong><div class="muted">Validation & testing</div></div>
        <div class="card"><strong>NGOs</strong><div class="muted">GBV support & outreach</div></div>
      </div>
    </section>

    <section class="card" style="margin-top:18px">
      <h3>How It Works</h3>
      <ol class="muted">
        <li>User taps panic or watch auto-detects danger.</li>
        <li>Control room receives location, medical profile & auto-recordings.</li>
        <li>Operators triage & dispatch SAPS/EMS/Fire and notify next-of-kin.</li>
        <li>Community Assist alerts nearby ResQMe users to help if safe.</li>
      </ol>
    </section>

    <section class="card" id="get" style="margin-top:18px">
      <h3>Get Involved</h3>
      <p class="muted">Join our beta, partner with us, or sponsor community access. We welcome telcos, universities, NGOs, and investors.</p>
      <div style="display:flex;gap:12px;margin-top:12px">
        <button class="btn">Join Beta</button>
        <button class="btn ghost">Contact Partnerships</button>
      </div>

      <div style="margin-top:16px">
        <h4>Contact</h4>
        <p class="muted">Email: hello@resqme.example (replace with your contact)</p>
        <p class="muted">Address: Pretoria, South Africa</p>
      </div>
    </section>

  </main>

  <footer>
    <div class="container">
      <div style="display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:12px">
        <div>
          <strong>ResQMe</strong>
          <div class="muted">Copyright © 2025 ResQMe Technologies (Pty) Ltd</div>
        </div>
        <div style="display:flex;gap:12px;align-items:center">
          <a href="#">Privacy</a>
          <a href="#">Terms</a>
          <a href="#">NDA</a>
        </div>
      </div>
    </div>
  </footer>

</body>
</html>
