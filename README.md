# WebsiteAnalyzer
Help read the static index.html file 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <meta name="description" content="GEM Cybersecurity Assist & Alliance Trust Realty – Financial protection, digital security, and real estate expertise." />
  <title>GEM Cybersecurity & ATR Realty</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: 'Roboto', sans-serif; background: #f5f7fa; color: #333; }
    header { background: #14213d; color: #fff; padding: 1rem 2rem; display: flex; justify-content: space-between; align-items: center; }
    header h1 { font-size: 1.5rem; }
    nav a { color: #fff; margin-left: 1.5rem; text-decoration: none; font-weight: 500; }
    .hero { background: #e5e5e5 url('https://images.unsplash.com/photo-1556740749-887f6717d7e4') center/cover no-repeat; padding: 5rem 2rem; text-align: center; color: #14213d; }
    .hero h2 { font-size: 2.5rem; margin-bottom: 1rem; }
    .section { padding: 3rem 2rem; max-width: 1000px; margin: auto; }
    .section h3 { font-size: 2rem; margin-bottom: 1rem; }
    .services-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 2rem; }
    .card { background: #fff; border: 1px solid #ddd; border-radius: 8px; padding: 1.5rem; box-shadow: 0 0 10px rgba(0,0,0,0.05); }
    .card h4 { margin-bottom: 0.5rem; }
    footer { background: #14213d; color: #fff; text-align: center; padding: 1rem 2rem; font-size: 0.9rem; }
    footer a { color: #fca311; text-decoration: none; }
  </style>
</head>
<body>

  <header>
    <h1>GEM Cybersecurity & ATR Realty</h1>
    <nav>
      <a href="#services">Services</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Secure Your Digital World & Your Real Estate Future</h2>
    <p>Powered by GEM Cyber Assist & Alliance Trust Realty, since 2015.</p>
  </section>

  <section class="section" id="services">
    <h3>Our Services</h3>
    <div class="services-grid">
      <div class="card">
        <h4>Cybersecurity Monitoring</h4>
        <p>Real-time protection, vulnerability assessment, and endpoint monitoring.</p>
      </div>
      <div class="card">
        <h4>Digital Asset Recovery</h4>
        <p>Recover lost or stolen crypto and digital accounts with legal and forensic support.</p>
      </div>
      <div class="card">
        <h4>QFS Integration</h4>
        <p>Quantum Financial System onboarding, advisory, and implementation support.</p>
      </div>
      <div class="card">
        <h4>Real Estate Leasing</h4>
        <p>Commercial and residential leasing across California, managed by ATR LLC.</p>
      </div>
      <div class="card">
        <h4>Mortgage Advisory</h4>
        <p>We help clients plan, apply, and negotiate mortgage and refinance packages.</p>
      </div>
      <div class="card">
        <h4>401k & Retirement Planning</h4>
        <p>Secure your financial legacy with tailored 401k strategies under compliance.</p>
      </div>
    </div>
  </section>

  <section class="section" id="about">
    <h3>About GEM & ATR</h3>
    <p>
      GEM Cybersecurity Assist was established in 2015 with the mission to protect individuals and organizations against digital threats and fraud. Alliance Trust Realty, our real estate division, manages leasing and property advisory across key metropolitan areas.
      <br><br>
      Together, we bring innovation and trust to both digital security and property solutions.
    </p>
  </section>

  <section class="section" id="contact">
    <h3>Contact Us</h3>
    <p>Email: <a href="mailto:legal@gemcybersecurityassist.com">legal@gemcybersecurityassist.com</a></p>
    <p>Support: <a href="mailto:support@gemcybersecurityassist.com">support@gemcybersecurityassist.com</a></p>
    <p>Phone: <a href="tel:+18603054376">+1 (860) 305-4376</a></p>
    <p>WhatsApp: Available on request</p>
  </section>

  <footer>
    &copy; 2015 – <span id="year"></span> GEM Cybersecurity Assist & Alliance Trust Realty LLC. All rights reserved.
  </footer>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>
</body>
</html>