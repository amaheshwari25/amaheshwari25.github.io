---
layout: default
title: Research Experience
permalink: /research/
description: Summaries of my primary research experiences in college. 
nav: true
nav_order: 3
display_categories: [work, fun]
horizontal: false
---
<div class="projects-container">
  <!-- Project 1 -->
  <div class="project">
    <button class="toggle" onclick="toggleDetails(this)">Algorithmic Game Theory: Matroid Prophet Inequalities <a href="../assets/pdf/JP_AryaMaheshwari.pdf" target="_blank">[View Paper]</a></button>
    <div class="details" style="display: none;">
      <p>Short description of the first research project. This is a two-sentence blurb that explains what the project is about.</p>
    </div>
  </div>
  <!-- Project 2 -->
  <div class="project">
    <button class="toggle" onclick="toggleDetails(this)">Algorithmic Graph Theory: Hypergraphic Degree Sequences <a href="../assets/pdf/JP_AryaMaheshwari.pdf" target="_blank">[View Paper]</a></button>
    <div class="details" style="display: none;">
      <p>Short description of the second research project. This is a two-sentence blurb that explains what the project is about.</p>
    </div>
  </div>
  <!-- Project 3 -->
  <div class="project">
    <button class="toggle" onclick="toggleDetails(this)">Quantum Computing; Space-Depth Tradeoffs in Hamiltonian Simulation Circuits<a href="../assets/pdf/JP_AryaMaheshwari.pdf" target="_blank">[View Paper]</a></button>
    <div class="details" style="display: none;">
      <p>Short description of the third research project. This is a two-sentence blurb that explains what the project is about.</p>
    </div>
  </div>
</div>
<script>
  function toggleDetails(button) {
    const details = button.nextElementSibling;
    if (details.style.display === "none") {
      details.style.display = "block";
    } else {
      details.style.display = "none";
    }
  }
</script>