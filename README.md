# Maharlika-debig.github.Io
Maharlika Republic 
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>The Maharlika Republic</title>
  <style>
    body { font-family: 'Segoe UI', sans-serif; margin: 0; background: linear-gradient(135deg, #ffc107, #ff5722); color: #222; }
    header, footer { background-color: #212121; color: white; padding: 1rem; text-align: center; }
    nav { display: flex; justify-content: space-around; background: #ff9800; padding: 0.5rem; }
    nav a { color: white; text-decoration: none; font-weight: bold; }
    section { padding: 2rem; }
    .slide { display: none; }
    .active { display: block; }
    .gavel { animation: gavelHit 2s infinite; display: inline-block; font-size: 2rem; margin-top: 1rem; }
    @keyframes gavelHit {
      0%, 100% { transform: rotate(0deg); }
      50% { transform: rotate(-30deg); }
    }
    form input, form button { padding: 0.5rem; margin: 0.5rem 0; display: block; width: 100%; }
    .poster { font-size: 1.5rem; font-weight: bold; color: #d32f2f; background: #fff; padding: 1rem; margin: 1rem 0; border: 3px dashed #000; }
    .presidents, .vps { background: #fff3e0; padding: 1rem; border-radius: 8px; }
  </style>
</head>
<body>
  <header>
    <h1>🇵🇭 The Maharlika Republic</h1>
    <div class="gavel">🔨</div>
  </header>  <nav>
    <a href="#constitution">Saligang Batas</a>
    <a href="#recruitment">Recruitment</a>
    <a href="#signup">Citizenship</a>
    <a href="#presidency">Leadership</a>
  </nav>  <section id="constitution" class="slide active">
    <h2>Saligang Batas ng Maharlika (Sections 1-100)</h2>
    <p>[FULL TEXT OF THE 100 SECTION CONSTITUTION GOES HERE]</p>
  </section>  <section id="recruitment" class="slide">
    <h2>Recruitment Time Na!</h2>
    <div class="poster">🚨 JOIN THE MAHARLIKA REPUBLIC! 🚨<br />
      Magkaisa! Magsaya! Maglingkod sa Bayan!<br />
      Be a Senator, Representative, o kahit Kalihim ng Fishball Department! 😁</div>
    <p>Kailangan ka ng Maharlika! Tara na sa bagong gobyerno na may puso at may pa-pizza pag may meeting! 🍕🇵🇭</p>
  </section>  <section id="signup" class="slide">
    <h2>Apply for Maharlika Citizenship</h2>
    <form>
      <input type="text" placeholder="Full Name" required />
      <input type="email" placeholder="Email Address" required />
      <input type="text" placeholder="Reason for Joining" required />
      <button type="submit">Submit</button>
    </form>
  </section>  <section id="presidency" class="slide">
    <h2>Mga Pangulo ng Maharlika</h2>
    <div class="presidents">
      <ul>
        <li>Neil Christian R Adalin (2024 - 2025)</li>
        <li>Thirdy (Aisher) Gomez (June 1 - July 26)</li>
        <li>Rey Dela Cruz (June 26 - Present)</li>
      </ul>
    </div>
    <h3>Mga Pangalawang Pangulo</h3>
    <div class="vps">
      <ul>
        <li>Thirdy (Aisher) Gomez (2024 - 2025)</li>
        <li>Rey Dela Cruz (June 5 - July 19)</li>
        <li>Zfeyd Ramoso (June 26 - Present)</li>
      </ul>
    </div>
  </section>  <footer>
    <p>&copy; 2025 The Maharlika Republic | Taglish powered nation | 🇵🇭</p>
  </footer>  <script>
    const navLinks = document.querySelectorAll("nav a");
    const slides = document.querySelectorAll(".slide");
    navLinks.forEach(link => {
      link.addEventListener("click", e => {
        e.preventDefault();
        const target = link.getAttribute("href").replace("#", "");
        slides.forEach(s => s.classList.remove("active"));
        document.getElementById(target).classList.add("active");
      });
    });
  </script></body>
</html>
