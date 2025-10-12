---
layout: page
title: Research Experience
permalink: /research/
description: Summaries of my primary research experiences thus far. 
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
      <span class="project-title">1. Algorithmic Game Theory & Mechanism Design</span>
    </div>
    <div class="details" style="display: none;">
      <p>I've worked on two main projects in this area with Prof. Matt Weinberg.</p>
      <!-- <br style="line-height:5px;"/> -->
      <h5> <b>Junior Paper: Matroid Prophet Inequalities</b> <a href="../assets/pdf/JP_AryaMaheshwari.pdf" target="_blank">[report]</a></h5>
      <p> For my Junior Paper at Princeton, I studied new lower bound constructions for the <i> matroid intersection 
      </i> prophet inequality problem. Prophet inequalities are a class of online selection problems that ask how well an agent choosing online from a sequence of items, under some set of feasibility constraints, can approximate the offline optimal feasible subset of items. 
      <!-- The <i> approximation ratio </i> is the ratio of the offline optimal value to what the online agent can achieve, and the goal in a prophet inequality is to determine how large this can be. --> 
      The prophet inequality for matroid intersection constraints is a decade-old open problem, with an asymptotic gap between linear upper bounds and roughly-square-root lower bounds on the approximation ratio, and what's especially intriguing is that the existing lower bound construction satisfies many special conditions that need not hold in general—yet no alternate constructions have been explored.</p> 
      <!-- <br style="line-height:3px;"/> -->
      <p>
      My research thus focused on investigating whether new generalization of the existing construction could improve the lower bound, leveraging tools from combinatorics, probability, and linear algebra given the diverse characterizations of matroids. I proved a number of new results that <i> rule out </i>  generalizations and new constructions from improving the lower bound, providing new insights into the substructure of the existing hardness construction and narrowing down which directions are most promising for the future.
      </p> 
      <h5> <b> Senior Thesis: Sample Complexity of Blackbox Reductions in Mechanism Design </b>  <a href="../assets/pdf/Thesis_Slides.pdf" target="_blank">[slides]</a>  <a href="../assets/pdf/EC25_Poster.pdf" target="_blank">[poster]</a></h5>
      <p> I'm now working on a senior thesis on improving the sample complexity of the blackbox reductions in in auction mechanisms for additive buyers. Existing reductions are based on the so-called <i> replica-surrogate bipartite matching </i> procedure, which requires exponentially-many samples from input distributions. Our work shows that under additional structural assumptions (in particular, for additive buyers over independent items), we can improve to polynomial sample complexity via a new variant of replica-surrogate matching. Stay tuned for a paper on our formal results!</p>
    </div>
  </div>
  <div class="project">
    <div class="project-header" id="project-graphs">
      <span class="triangle" onclick="toggleDetails(this)">▶</span>
      <span class="project-title">2. Algorithmic Graph Theory: Hypergraphic Degree Sequences <a href="https://arxiv.org/abs/2411.19049" target="_blank">[arXiv]</a></span>
    </div>
    <div class="details" style="display: none;">
      <p> I worked on this project with Prof. István Miklós (Rényi Institute) and two other students while at the Budapest Semesters in Mathematics. We studied the <i>degree sequence graphicality</i> problem for 3-uniform hypergraphs, which asks whether a given degree sequence is realized by a 3-uniform hypergraph. We proved a <i> dichotomy theorem </i> on the complexity of this decision problem over all possible degree intervals, showing that the problem is either solvable in linear time (very easily) or NP-complete (and characterizing exactly when each case happens).</p>
      <p><b>Publication</b>: In submission to Journal of Combinatorial Theory. Upcoming presentation at Joint Mathematics Meeting 2025. Preprint on arXiv <a href="https://arxiv.org/abs/2411.19049" target="_blank">here</a></p>
    </div>
  </div>
  <div class="project">
    <div class="project-header" id="project-qc">
      <span class="triangle" onclick="toggleDetails(this)">▶</span>
      <span class="project-title">3. Quantum Computing: Space-Depth Tradeoffs in Hamiltonian Simulation Circuits</span>
    </div>
    <div class="details" style="display: none;">
      <p> I worked on both theoretical research and implementations for new quantum compilation algorithms at IBM Quantum with Dr. Ali Javadi-Abhari. I proved a new result on the <i>space-depth tradeoff</i> between additional qubits and additional depth in parity synthesis for Hamiltonian simulation circuits. Specifically, I devised a new algorithmic framework for extending the block algorithm for isometry synthesis of <a href="https://arxiv.org/pdf/2201.06380">de Brugière et al.</a> in a way that enables finer-grained control of the space-depth tradeoff than previously possible, by leveraging additional ancilla to proportionally parallelize the existing computations.</p>
      <p> <b>Publication:</b> Paper on theoretical results currently being drafted. Code used for benchmarks in another recent <a href="https://arxiv.org/pdf/2404.03280">paper</a>.</p>
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