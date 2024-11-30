---
layout: page
title: Miscellaneous Projects
permalink: /projects/
description: Here's a list of some miscellaneous projects I've worked on. 
nav: true
nav_order: 3
display_categories: [work, fun]
horizontal: false
---

<div class="projects-container">
  <!-- Project 1 -->
  <div class="project">
    <div class="project-header" id="project-matroids">
      <span class="triangle" onclick="toggleDetails(this)">▶</span>
      <span class="project-title"><b> 1. Combinatorial BMM </b> <a href="../assets/pdf/CombinatorialBMM_Survey.pdf" target="_blank">[paper]</a></span>
    </div>
    <div class="details" style="display: none;">
    <p> Survey of recent breakthrough in fine-grained complexity on combinatorial boolean matrix multiplication. Final project for COS521: Advanced Algorithm Design (Graduate) with Huacheng Yu. </p>
    </div>
  </div>
  <br>
  <div class="project">
    <div class="project-header" id="project-graphs">
      <span class="triangle" onclick="toggleDetails(this)">▶</span>
      <span class="project-title"><b> 2. Incentive Compatible AMMs in Binary Prediction Markets </b> <a href="../assets/pdf/COS473_Paper.pdf" target="_blank">[paper]</a> <a href="../assets/pdf/COS473_Poster.pdf" target="_blank">[poster]</a></span>
    </div>
    <div class="details" style="display: none;">
    <p> Theoretical study and simulations of <i> liquidity-sensitive </i> market scoring rule implemented in automated market makers (COS473 final project). Won Outstanding Poster award at Princeton’s 2023 DeCenter Conference on blockchains.</p>
    </div>
  </div>
  <br>
  <div class="project">
    <div class="project-header" id="project-qc">
      <span class="triangle" onclick="toggleDetails(this)">▶</span>
      <span class="project-title"><b> 3. Spectral Graph Theory </b> (Directed Reading Program)</span>
    </div>
    <div class="details" style="display: none;">
      <p> Studied Spielman’s manuscript and worked on computational project on Graph Hot Spots Conjecture with PhD student mentor.</p>
    </div>
  </div>
  <br>
  <div class="project">
    <div class="project-header" id="project-qc">
      <span class="triangle" onclick="toggleDetails(this)">▶</span>
      <span class="project-title"><b> 4. Miscellaneous Quantum Computing Projects </b> </span>
    </div>
    <div class="details" style="display: none;">
      <p> Developed a full Python pipeline for using variational quantum algorithms (QAOA) to generate thermal states with Dr. Esin Tureci and Dr. Teague Tomesh. Also worked on quantum machine learning project, focused on testing the efficacy of quantum kernel methods (COS396 final project), and placed 2nd in Princeton Qiskit 2022 Fall Fest focused on quantum search (Grover's Algorithm). </p>
    </div>
  </div>
  <br>
  <div class="project">
    <div class="project-header" id="project-qc">
      <span class="triangle" onclick="toggleDetails(this)">▶</span>
      <span class="project-title"><b> 5. Applying GPT-3 and Dense Embeddings to NLProofS  </b> <a href="../assets/pdf/COS484_Paper.pdf" target="_blank">[paper]</a> <a href="../assets/pdf/COS484_Poster.pdf" target="_blank">[poster]</a></span>
    </div>
    <div class="details" style="display: none;">
      <p> Investigated recent natural language proof generation model through two ablation studies (COS484 final project). </p>
    </div>
  </div>
  <br>
  <div class="project">
    <div class="project-header" id="project-qc">
      <span class="triangle" onclick="toggleDetails(this)">▶</span>
      <span class="project-title"><b> 6. High School Astrophysics Research </b> </span>
    </div>
    <div class="details" style="display: none;">
      <p> Worked on research projects on stellar stream formation (with Princeton faculty and NASA Advanced Supercomputing scientists); supernova light-curve modeling (Yale Summer Program in Astrophysics); and rare star classification (UC Santa Cruz). Papers published in <a href="https://emerginginvestigators.org/articles/photometric-analysis-and-light-curve-modeling-of-apparent-transient-2020pni">Harvard JEI</a>; in submission to the Astrophysical Journal. Presentations at <a href="http://adsabs.harvard.edu/abs/2019AAS...23337101M"> 233rd AAS Meeting</a> and <a href="http://meetings.aps.org/Meeting/FWS20/Session/L01.1">2020 APS Meeting</a> (first-author). </p>
    </div>
  </div>
  <!-- Repeat for other projects -->
</div>

<script>
  function toggleDetails(triangle) {
    const details = triangle.parentElement.nextElementSibling; // Get the details section
    const isOpen = details.style.display === "block";

    // Toggle details visibility
    details.style.display = isOpen ? "none" : "block";

    // Rotate the triangle
    if (isOpen) {
      triangle.classList.remove("open");
    } else {
      triangle.classList.add("open");
    }
  }
</script>
<!-- 
<div>
<b> 1. Combinatorial BMM </b> <a href="../assets/pdf/CombinatorialBMM.pdf" target="_blank">[paper]</a>
</div>

<div>

</div>

<div>
<b> 3. Spectral Graph Theory </b>
Studied Spielman’s manuscript and worked on computational project on Graph Hot Spots Conjecture with PhD student mentor.
</div>

<div>
<b> 4. Miscellaneous Quantum Computing Projects </b>
Developed a full Python pipeline for using variational quantum algorithms (QAOA) to generate thermal states with Dr. Esin Tureci and Dr. Teague Tomesh. Also worked on quantum machine learning project, focused on testing the efficacy of quantum kernel methods (COS396 final project), and placed 2nd in Princeton Qiskit 2022 Fall Fest focused on quantum search (Grover's Algorithm). </div>

<div>
<b> 5. Applying GPT-3 and Dense Embeddings to NLProofS </b>
Investigated recent natural language proof generation model through two ablation studies (COS484 final project). 
</div> -->


