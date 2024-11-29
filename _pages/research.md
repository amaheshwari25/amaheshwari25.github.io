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
    <div class="project-header">
      <span class="triangle" onclick="toggleDetails(this)">▶</span>
      <span class="project-title">Algorithmic Game Theory: Matroid Prophet Inequalities <a href="../assets/pdf/JP_AryaMaheshwari.pdf" target="_blank">[paper]</a></span>
    </div>
    <div class="details" style="display: none;">
      <p>Short description of the first research project. This is a two-sentence blurb that explains what the project is about.</p>
    </div>
  </div>
  <div class="project">
    <div class="project-header">
      <span class="triangle" onclick="toggleDetails(this)">▶</span>
      <span class="project-title">Algorithmic Graph Theory: Hypergraphic Degree Sequences</span>
    </div>
    <div class="details" style="display: none;">
      <p> We studied the <i>degree sequence graphicality</i> problem for 3-uniform hypergraphs, which asks whether a given degree sequence is realized by a 3-uniform hypergraph. I worked on this project with Prof. István Miklós (Rényi Institute) and two other students while at the Budapest Semesters in Mathematics. </p>
    </div>
  </div>
  <div class="project">
    <div class="project-header">
      <span class="triangle" onclick="toggleDetails(this)">▶</span>
      <span class="project-title">Quantum Computing; Space-Depth Tradeoffs in Hamiltonian Simulation Circuits</span>
    </div>
    <div class="details" style="display: none;">
      <p>Short description of the first research project. This is a two-sentence blurb that explains what the project is about.</p>
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