# Medico-
Help for medico service 
<!-- Save as index.html and upload to GitHub repo (enable GitHub Pages) -->
<!doctype html>
<html lang="hi">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>MedLink Network — Connect Hospitals & Doctors</title>
  <style>
    body{font-family:Arial,Helvetica,sans-serif;margin:0;color:#222}
    header{background:#0b5; padding:28px 16px; text-align:center}
    header h1{margin:0;color:#033}
    .container{max-width:900px;margin:24px auto;padding:0 16px}
    .grid{display:grid;grid-template-columns:1fr;gap:18px}
    .card{padding:18px;border:1px solid #e6e6e6;border-radius:8px}
    .btn{display:inline-block;padding:10px 16px;background:#0366d6;color:#fff;border-radius:6px;text-decoration:none}
    form input, form textarea{width:100%;padding:10px;margin:8px 0;border:1px solid #ccc;border-radius:6px}
    footer{text-align:center;padding:18px;color:#666;font-size:14px}
    @media(min-width:800px){ .grid{grid-template-columns:1fr 1fr} }
  </style>
</head>
<body>
  <header>
    <h1>MedLink Network</h1>
    <p>Hospitals • Labs • Doctors • Pharma — ek saath</p>
  </header>

  <main class="container">
    <section class="grid">
      <div class="card">
        <h2>About</h2>
        <p>MedLink Network local doctors aur medical centers ko connect karne ka platform hai. Onboard karne ke liye niche form bharein.</p>
        <p><strong>Features:</strong> Referrals, Reports, Direct Messaging, Premium Listing.</p>
        <a class="btn" href="#join">Join Now</a>
      </div>

      <div class="card">
        <h2>How it Works</h2>
        <ol>
          <li>Register — Profile banayein</li>
          <li>Search — Nearby hospitals / labs</li>
          <li>Connect — Referral aur reports</li>
        </ol>
      </div>
    </section>

    <section id="join" class="card" style="margin-top:18px">
      <h2>Join / Contact</h2>
      <!-- Example using Formspree: replace "YOUR_FORMSPREE_ID" with real ID -->
      <form action="https://formspree.io/f/YOUR_FORMSPREE_ID" method="POST">
        <label>Naam / Organization</label>
        <input type="text" name="name" required>
        <label>Role (Doctor / Hospital / Lab / Pharma)</label>
        <input type="text" name="role" required>
        <label>City</label>
        <input type="text" name="city" required>
        <label>Contact (WhatsApp / Phone / Email)</label>
        <input type="text" name="contact" required>
        <label>Message</label>
        <textarea name="message" rows="4"></textarea>
        <button class="btn" type="submit">Send</button>
      </form>
    </section>
  </main>

  <footer>
    © MedLink Network — Built for local medical connectivity
  </foote
