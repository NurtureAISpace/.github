# NurtureAISpace

<div align="center">
  <img src="nurtureaispace-badge.jpg" alt="NurtureAISpace Official Mission Emblem" width="220" style="border-radius: 50%; box-shadow: 0 10px 25px rgba(0,0,0,0.5);" />
  <br />
  <h2>NurtureAI Space — Health Monitoring for Astronauts</h2>
  <p>NASA Space Apps Challenge 2026: <em>Create Health Monitoring Software for Astronauts on Space Missions</em>.<br />Personal-baseline health monitoring, storage vitamin degradation kinetics, and bio-nutritional meal optimization.</p>
  <p><strong>Developed by Team NurtureAISpace</strong></p>
  <p>
    <a href="https://nurtureaispace.github.io"><strong>Open the Live Demo »</strong></a> • 
    <a href="https://nurtureaispace.github.io/app/"><strong>Astronaut App »</strong></a> • 
    <a href="https://nurtureaispace.github.io/slides.html"><strong>Official 7-Slide Deck »</strong></a>
  </p>
</div>

---

### 👥 Team NurtureAISpace
* **Suleyman Hajizadeh** — Lead Systems Architect & Research ([`suleyman.hacizade1@gmail.com`](mailto:suleyman.hacizade1@gmail.com))
* **Banu Gurbanzada** — Frontend Architecture & UI/UX Design ([`banugurbanzade@gmail.com`](mailto:banugurbanzade@gmail.com))
* **Yunis Allahverdi** — AI/ML & Degradation Modeling ([`allahverdiyunis@gmail.com`](mailto:allahverdiyunis@gmail.com))
* **Faruk Karimli** — Computer Engineering & Life Support Simulation ([`fkarimli23291@ada.edu.az`](mailto:fkarimli23291@ada.edu.az))

---

### 🌐 Official Live Platform & Repositories
- **Crew Dashboard (Live Demo Snapshot):** [https://nurtureaispace.github.io](https://nurtureaispace.github.io)
- **Astronaut App (Offline-First Daily Check-In):** [https://nurtureaispace.github.io/app/](https://nurtureaispace.github.io/app/)
- **Official 7-Slide Pitch Deck:** [https://nurtureaispace.github.io/slides.html](https://nurtureaispace.github.io/slides.html)
- **Primary Source Code:** [https://github.com/NurtureAISpace/mars-food-intelligence](https://github.com/NurtureAISpace/mars-food-intelligence)
- **Live Deployment Repository:** [https://github.com/NurtureAISpace/NurtureAISpace.github.io](https://github.com/NurtureAISpace/NurtureAISpace.github.io)

---

### 🚀 Technical Overview & Key Features
- **NASA Evidence & Personal Baseline:** Leverages real NASA Open Science Data Repository (OSDR) Inspiration4 datasets (OSD-569 and OSD-575) comparing each astronaut against their own pre-flight baseline to catch subtle sub-clinical micronutrient shifts early.
- **First-Principles Chemical Thermodynamics:** Non-linear Arrhenius degradation kinetics (`k(T) = A * exp(-Ea / R*T)`) modeling Vitamin C and Thiamine (B1) loss across storage temperature fluctuations.
- **SciPy Multi-Objective Optimizer:** Solves daily crew meal compositions (`scipy.optimize.linprog`, HiGHS solver) balancing stored rations with bio-regenerative fresh crops (microgreens, cherry tomatoes) to satisfy nutritional constraints while minimizing mass and chiller power.
- **Offline-First PWA:** Astronaut check-in app works fully offline on mobile devices with local IndexedDB storage, biometric pseudonymization, and zero-server dependency for mission autonomy.

---

### 📋 Code, Data Sources and Honesty Notes
This is a research prototype built for NASA Space Apps Challenge 2026, Ganja.
- Real NASA data used: NASA OSDR OSD-569 and OSD-575 (Inspiration4). NASA publications and exploration nutrition requirements are cited as scientific references.
- Parameter provenance: Every parameter and reference is cataloged in `docs/DATA_SOURCES.md` in the `mars-food-intelligence` repository.
- Built before vs. during the hackathon: Transparently documented in `README.md` of `mars-food-intelligence`.
