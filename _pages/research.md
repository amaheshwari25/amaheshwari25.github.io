---
layout: default
title: Research Experience
permalink: /research/
description: Summaries of my primary research experiences in college. 
nav: true
nav_order: 2
display_categories: [work, fun]
horizontal: false
---

<div class="projects-container">
  <!-- Project 1 -->
  <div class="project">
    <div class="project-header" id="project-matroids">
      <span class="triangle" onclick="toggleDetails(this)">▶</span>
      <span class="project-title">Algorithmic Game Theory: Matroid Prophet Inequalities <a href="../assets/pdf/JP_AryaMaheshwari.pdf" target="_blank">[paper]</a></span>
    </div>
    <div class="details" style="display: none;">
      <p>- Junior paper under Matt Weinberg on lower bound constructions for the <i> matroid intersection </i> prophet inequality problem. Current senior thesis on improving sample complexity of reductions to truthful auction mechanisms for an additive buyer.</p>
    </div>
  </div>
  <div class="project">
    <div class="project-header" id="project-graphs">
      <span class="triangle" onclick="toggleDetails(this)">▶</span>
      <span class="project-title">Algorithmic Graph Theory: Hypergraphic Degree Sequences</span>
    </div>
    <div class="details" style="display: none;">
      <p> We studied the <i>degree sequence graphicality</i> problem for 3-uniform hypergraphs, which asks whether a given degree sequence is realized by a 3-uniform hypergraph. I worked on this project with Prof. István Miklós (Rényi Institute) and two other students while at the Budapest Semesters in Mathematics. </p>
      <p><b>Publication</b>: In submission to Journal of Combinatorial Theory. Upcoming presentation at Joint Mathematics Meeting 2025.</p>
    </div>
  </div>
  <div class="project">
    <div class="project-header" id="project-qc">
      <span class="triangle" onclick="toggleDetails(this)">▶</span>
      <span class="project-title">Quantum Computing; Space-Depth Tradeoffs in Hamiltonian Simulation Circuits</span>
    </div>
    <div class="details" style="display: none;">
      <p> I worked on both theoretical research and implementations for new quantum compilation algorithms at IBM Quantum with Dr. Ali Javadi-Abhari. I proved a new result on <i>space-depth tradeoff</i> between additional qubits and additional depth in parity synthesis for Hamiltonian simulation circuits. Specifically, I devised a new algorithmic framework that enables finer-grained control of this tradeoff than previously possible.</p>
      <p> <b>Publication:</b> Paper on theoretical results currently being drafted. Code used for benchmarks in another recent paper.</p>
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