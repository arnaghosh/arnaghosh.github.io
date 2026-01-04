---
layout: default
page_title: "Arna Ghosh | Research Scientist"
---
# Arna Ghosh
Briefly introduce yourself here. I am a developer interested in...
---

<div class="main-grid">

  <div class="column">
    ## 📚 Selected Publications
    
    <p><strong>Representation Geometry in ANNs</strong><br>
    <em>A. Ghosh, et al.</em> | Conference Name 2024<br>
    <a href="#">PDF</a> | <a href="#">Abstract</a></p>

    <p><strong>Neural Dynamics of BCI</strong><br>
    <em>A. Ghosh, et al.</em> | Journal Name 2023<br>
    <a href="#">PDF</a></p>
  </div>

  <div class="column">
    ## 🚀 Projects
    
    <div class="project-card">
      <h3>🧠 Representation Geometry & Learning Dynamics</h3>
      <div class="tags">
        <span class="tag">AI</span> <span class="tag">Neuroscience</span> <span class="tag">Self-Supervised Learning</span> <span class="tag">PyTorch</span>
      </div>
      <p>Characterizing the geometry of learned representations in artificial neural networks and connecting these properties to generalization performance. Investigating "functional homologues" between ANNs and the brain across species.</p>
      <a href="https://melodylizx.github.io/llm-geometry-project/" class="project-link" target="_blank">Project page →</a>
    </div>

    <div class="project-card">
      <h3>⌨️ Brexting: Brain Texting</h3>
      <div class="tags">
        <span class="tag">Deep Learning</span> <span class="tag">EEG</span> <span class="tag">FPGA</span> <span class="tag">BCI</span>
      </div>
      <p>Built a DL-powered brain-computer interface on an Intel FPGA board to decode imagined motor movements into real-time typing. Recognized as an Intel Innovate FPGA Grand Finalist.</p>
      <a href="https://github.com/arnaghosh" class="project-link" target="_blank">View Code →</a>
    </div>

    <div class="project-card">
      <h3>🔬 Deep Learning for Neuroimage Analysis</h3>
      <div class="tags">
        <span class="tag">Medical AI</span> <span class="tag">EEG/MRI</span> <span class="tag">Interpretability</span> <span class="tag">Torch</span>
      </div>
      <p>Developed ccCAM (cue-combination for Class Activation Map) to identify discriminative biomarkers from EEG/MRI data. Created a ML-driven brain age prediction system for stroke recovery assessment.</p>
      <a href="https://github.com/arnaghosh" class="project-link" target="_blank">View Project →</a>
    </div>

    <div class="project-card">
      <h3>🚗 Autonomous Ground Vehicle (AGV)</h3>
      <div class="tags">
        <span class="tag">Computer Vision</span> <span class="tag">ROS</span> <span class="tag">LIDAR</span> <span class="tag">Python/C++</span>
      </div>
      <p>Developed perception modules for obstacle and lane detection, fusing camera and LIDAR data for real-time world mapping on Robot Operating System (ROS).</p>
      <a href="https://github.com/arnaghosh" class="project-link" target="_blank">View Repo →</a>
    </div>

  </div>

</div>


---

### Skills
* **Languages:** JavaScript, Python, SQL
* **Tools:** Git, Docker, AWS

---

<button id="theme-toggle" title="Toggle Dark Mode" style="cursor:pointer; background:none; border:none; font-size:1.5rem; position:fixed; top:20px; right:20px; z-index:1000;">🌙</button>

<script>
  const btn = document.getElementById("theme-toggle");
  const prefersDarkScheme = window.matchMedia("(prefers-color-scheme: dark)");
  
  // 1. Determine starting theme
  const currentTheme = localStorage.getItem("theme");
  if (currentTheme === "dark" || (currentTheme === null && prefersDarkScheme.matches)) {
    document.body.classList.add("dark-mode");
    btn.textContent = "☀️";
  }

  // 2. Toggle Logic
  btn.addEventListener("click", function() {
    document.body.classList.toggle("dark-mode");
    let theme = document.body.classList.contains("dark-mode") ? "dark" : "light";
    btn.textContent = theme === "dark" ? "☀️" : "🌙";
    localStorage.setItem("theme", theme);
  });
</script>